# FEF-FGR-002-EP-005-FFICR-001 — EP-005 Frozen Fingerprint Integrity Correction Record

| Control Field                         | Recorded Value                                             |
| ------------------------------------- | ---------------------------------------------------------- |
| Correction record identifier          | FEF-FGR-002-EP-005-FFICR-001                               |
| Review identifier                     | FEF-FGR-002                                                |
| Domain                                | D5 — Governance Lifecycle and Evolution                    |
| Pack identifier                       | FEF-FGR-002-EP-005                                         |
| Pack version                          | 1.0                                                        |
| Correction date                       | 2026-07-31                                                 |
| Preparation capacity                  | FEF-FGR-002-RA-002 — Review Administrator                  |
| Validator                             | FEF-FGR-002-RA-006 — non-independent combination disclosed |
| Repository baseline before correction | `663297a1f9d194bf85fcad9cb98d5dfccd95b86f`                 |
| Correction outcome                    | **Corrected — Pass with Conditions**                       |

## A. Discovery

### A.1 Detection

The mismatch was detected during task **FEF-FGR-002 D5 Post-Freeze Session-Entry Readiness Reconciliation**, which verified the repository entry state against the controlling frozen fingerprints declared in the original FEF-FGR-002-EP-005-FR-001 v1.0 and FEF-FGR-002-EP-005-VR-001 v1.0.

The entry-state verification task stopped before modifying any file, as required by the governing instructions when frozen fingerprints do not match.

### A.2 Mismatch

The current working-tree (and git blob at commit `663297a1f9d194bf85fcad9cb98d5dfccd95b86f`) SHA-256 digests of the Evidence Pack and Manifest do not match the controlling frozen fingerprints declared in FR-001 and VR-001:

| Artefact             | Declared Frozen SHA-256 (FR-001 v1.0)                              | Actual SHA-256 at freeze commit                                    | Match  |
| -------------------- | ------------------------------------------------------------------ | ------------------------------------------------------------------ | ------ |
| EP-005 Evidence Pack | `edcc5a94e652a9a15784ee7318f72946a140ea1450c4f4a1132856ebfc0d7f4e` | `1e86b9fbd888c17c8368df289364cb460e4066472a1dffd2c0f1d5b923971b09` | **NO** |
| EP-005 Manifest      | `4b9538a9debcbfbaaf8bdab7dfdd6544bca672a6e090f11e017456a470b3f9a8` | `e0caaad8a79cb13c9cdb30b8c1b2cd6787078bfd8497894342d1592398c293b9` | **NO** |

### A.3 Verification Task Stopped

The verification task followed the governing instruction:

> "If either fingerprint differs: **STOP.** Do not repair or refreeze the pack. Report the mismatch."

This task is the separately authorised correction and revalidation response to that stop report.

## B. Root Cause

### B.1 Freeze Annotations Changed Whole-File Bytes

The DG-3 freeze commit (`663297a1f9d194bf85fcad9cb98d5dfccd95b86f`) modified both the Evidence Pack and the Manifest to add lifecycle-state annotations:

**Evidence Pack (`663297a` vs `d9982b5`):** 5 hunks, 50 lines changed

- Lifecycle state: "Assembled — Not Frozen" → "Frozen"
- Freeze state: "Not Frozen" → "Frozen — 2026-07-31"
- Freeze record reference: "None — not yet frozen" → link to FR-001
- Freeze validation reference: added
- Pack effect description: updated
- Section 2 Purpose and Boundary: updated to describe freeze
- Non-effects disclaimer: rewritten from assembly-era language to freeze-era language
- Section 3 heading: "Assembled Membership" → "Closed Membership"
- Section 3 membership description: "assembled membership" → "frozen membership"
- Section 9 heading: "Pack Fingerprint (Assembled — Pending Freeze)" → "Pack Fingerprint (Frozen)"
- Section 9 narrative: updated from assembly-era to freeze-era
- Section 10 heading: "State after Assembly" → "State after Freeze"
- Section 10 RQ state: "Packed in EP-005 v1.0" → "Evidence Pack Frozen — EP-005 v1.0"
- Section 10 EP-005 state: "Assembled — v1.0 — Not Frozen" → "Frozen — v1.0"
- Section 11 Revision History: freeze row added
- Section 12 Pack Conditions: rewritten for frozen operation
- Section 12 closing state: "Assembled — Not Frozen — Pass with Conditions (pending DG-3 freeze authorisation)" → "Frozen — v1.0 — Pass with Conditions"

**Manifest (`663297a` vs `d9982b5`):** 2 hunks, 9 lines changed

- State: "Assembled — Not Frozen" → "Frozen"
- Freeze date: added
- Section 7 heading: "Manifest Status" → "Manifest Closure"
- Section 7 narrative: updated from assembly-era to closed-at-freeze

### B.2 Assembly Hashes Incorrectly Described as Final Frozen Hashes

FR-001 v1.0 and VR-001 v1.0 both recorded the assembly-state hashes (`edcc5a94...` and `4b9538a9...`) as the controlling frozen whole-file fingerprints, even though:

1. The freeze commit itself modified both files;
2. The actual post-freeze files therefore have different hashes;
3. FR-001 and VR-001 were themselves created in the same freeze commit and should have been able to observe the actual final frozen files.

### B.3 Error Classification

This is an **integrity metadata defect in DG-3 freeze records**. The error is in FR-001 and VR-001, not in the pack or manifest. The pack and manifest are correct as frozen — their content changes are exactly the lifecycle annotations expected of a freeze action. The error is that the freeze records continued to cite the pre-freeze (assembly-state) hashes as the final frozen hashes rather than computing and recording the actual post-freeze-update hashes.

### B.4 Evidence Membership and Mappings Unchanged

The structured diff confirms that **no change was made to any evidence membership, evidence identifier, evidence title, controlled path, provenance commit, source digest, evidence class, admissibility, RQ mapping, requirement mapping, limitation, permitted use, Open Question, D6/D7 interface, or special-evidence acquisition-point control.**

The freeze commit changed only lifecycle/control annotations, not evidence content.

## C. Fingerprint Timeline

### C.1 Assembly-State Whole-File Fingerprints (Historical)

At assembly commit `b8490aa434eec518fbb110e21b55e0a3e7335262` and pre-freeze reconciliation commit `d9982b592ed5375cdc47a6c48f59c3d0d455dbc2`:

| Artefact             | Assembly-State SHA-256                                             |
| -------------------- | ------------------------------------------------------------------ |
| EP-005 Evidence Pack | `edcc5a94e652a9a15784ee7318f72946a140ea1450c4f4a1132856ebfc0d7f4e` |
| EP-005 Manifest      | `4b9538a9debcbfbaaf8bdab7dfdd6544bca672a6e090f11e017456a470b3f9a8` |

These remain valid **historical assembly-state fingerprints**. They identify the final assembled, pre-freeze files.

### C.2 Frozen-State Whole-File Fingerprints (Controlling)

At DG-3 freeze commit `663297a1f9d194bf85fcad9cb98d5dfccd95b86f`:

| Artefact             | Frozen-State SHA-256                                               |
| -------------------- | ------------------------------------------------------------------ |
| EP-005 Evidence Pack | `1e86b9fbd888c17c8368df289364cb460e4066472a1dffd2c0f1d5b923971b09` |
| EP-005 Manifest      | `e0caaad8a79cb13c9cdb30b8c1b2cd6787078bfd8497894342d1592398c293b9` |

These become the **controlling frozen whole-file fingerprints** for all purposes, including any future DG-4 session-entry verification.

### C.3 Membership Fingerprint (Unchanged)

`59414d0803ed114171c35a821d4581a80e8df92121260d868eaee4fd76e925fc`

This fingerprint is computed from the ordered Evidence Record digest inputs, independent of lifecycle annotations. It remains **unchanged** across assembly (`b8490aa`), pre-freeze reconciliation (`d9982b5`), and freeze (`663297a`).

## D. Structured Diff Classification

### D.1 Evidence Pack Changed Hunks

| Hunk                  | Lines                                                     | Change Class                                                                                  |
| --------------------- | --------------------------------------------------------- | --------------------------------------------------------------------------------------------- |
| @@ -15,22 +15,23 @@   | Control field table                                       | Lifecycle state, Freeze state, Freeze record, Freeze validation, Pack effect                  |
| @@ -39,11 +40,11 @@   | Purpose and Boundary narrative                            | Freeze description; non-effects rewritten                                                     |
| @@ -178,7 +179,7 @@   | Section 3 heading and membership description              | "Assembled Membership" → "Closed Membership"; "assembled membership" → "frozen membership"    |
| @@ -188,15 +189,15 @@ | Section 9 heading and narrative                           | "Assembled — Pending Freeze" → "Frozen"; narrative updated                                    |
| @@ -208,17 +209,16 @@ | Lifecycle Effect table, Revision History, Pack Conditions | State labels updated; revision history entry added; conditions rewritten for frozen operation |

All five hunks are **lifecycle/control annotation changes only**.

### D.2 Manifest Changed Hunks

| Hunk                | Lines                           | Change Class                                              |
| ------------------- | ------------------------------- | --------------------------------------------------------- |
| @@ -6,8 +6,9 @@     | Control field table             | State, Freeze date                                        |
| @@ -166,6 +167,6 @@ | Section 7 heading and narrative | "Manifest Status" → "Manifest Closure"; narrative updated |

Both hunks are **lifecycle/control annotation changes only**.

### D.3 Evidence-Section Verification

| Section                                                                      | Changed? | Verdict   |
| ---------------------------------------------------------------------------- | -------- | --------- |
| Evidence Record membership (EV-005 through EV-085)                           | No       | Unchanged |
| Evidence identifiers                                                         | No       | Unchanged |
| Evidence titles                                                              | No       | Unchanged |
| Controlled paths                                                             | No       | Unchanged |
| Provenance commits                                                           | No       | Unchanged |
| Source digests                                                               | No       | Unchanged |
| Evidence classes                                                             | No       | Unchanged |
| Admissibility states                                                         | No       | Unchanged |
| RQ mappings                                                                  | No       | Unchanged |
| Requirement mappings                                                         | No       | Unchanged |
| Limitations                                                                  | No       | Unchanged |
| Permitted uses                                                               | No       | Unchanged |
| Open Questions                                                               | No       | Unchanged |
| D6/D7 interfaces                                                             | No       | Unchanged |
| Special-evidence acquisition-point controls (EV-072, EV-080, EV-081, EV-078) | No       | Unchanged |

**No substantive evidence or mapping section changed.**

## E. Severity and Effect

### E.1 Classification

**Integrity metadata defect in DG-3; recoverable without repeating evidence assembly or substantive freeze.**

### E.2 Effects

| Effect                                                                          | Assessment                                                                                                            |
| ------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------- |
| DG-3 was not reliable for downstream fingerprint verification before correction | Confirmed — any DG-4 task using v1.0 FR-001/VR-001 hashes would have detected a mismatch                              |
| DG-4 remained blocked                                                           | Confirmed — session-entry validation cannot proceed against knowingly incorrect fingerprint records                   |
| No evidence corruption found                                                    | Confirmed — all 25 Evidence Records, 41 mappings, 42 links, 24 requirements unchanged                                 |
| No successor or Supplemental Pack required                                      | Confirmed — the frozen pack and manifest at `663297a` are correct; only the integrity metadata needs correction       |
| No refreeze required                                                            | Confirmed — the files at `663297a` are the validated final frozen artefacts; a second freeze event would be incorrect |
| Membership fingerprint unchanged                                                | Confirmed — `59414d0803ed114171c35a821d4581a80e8df92121260d868eaee4fd76e925fc`                                        |

## F. Corrective Action

### F.1 FR-001 Correction

FEF-FGR-002-EP-005-FR-001 advanced from v1.0 to v1.1:

- Correction Notice added, disclosing that v1.0 incorrectly described the assembly-state hashes as final frozen whole-file fingerprints.
- Assembly-state hashes preserved as historical Assembly-State Pack Fingerprint and Assembly-State Manifest Fingerprint.
- Actual frozen-state hashes recorded as Controlling Frozen Pack Fingerprint and Controlling Frozen Manifest Fingerprint.
- Membership fingerprint preserved unchanged.
- Frozen baseline commit `663297a1f9d194bf85fcad9cb98d5dfccd95b86f` recorded.
- Links to FFICR-001 and FFICVR-001 added.
- Statement added that later DG-4 must use the frozen-state hashes, not the assembly-state hashes.
- No change to pack identifier, pack version, frozen membership, freeze date, RQ scope, evidence controls, or substantive conditions.

### F.2 VR-001 Correction

FEF-FGR-002-EP-005-VR-001 advanced from v1.0 to v1.1:

- Correction Notice added, disclosing that v1.0 validated the wrong whole-file fingerprint pair as frozen.
- Assembly-state and frozen-state validation distinguished.
- Actual frozen files at commit `663297a` validated.
- Corrected frozen hashes recorded.
- Membership fingerprint verified unchanged.
- 25/41/42/24 counts verified unchanged.
- Overall verdict retained: **Pass with Conditions**.
- Links to FFICR-001 and FFICVR-001 added.
- Non-independent validation disclosure preserved.

### F.3 Integrity Model

Three distinct controls are now recorded:

1. **Assembly-State Whole-File Fingerprints** — identify the final assembled, pre-freeze files; remain historical.
2. **Frozen-State Whole-File Fingerprints** — identify the final lifecycle-annotated files produced by DG-3; controlling for DG-4.
3. **Membership Fingerprint** — identifies evidence-content membership independent of lifecycle annotations; unchanged.

These three controls are deliberately separated in the corrected records, not merged into a single "unchanged fingerprint" claim.

## G. Non-Effects

This correction:

- Does not alter EP-005 pack bytes;
- Does not alter EP-005 manifest bytes;
- Does not create a successor or Supplemental Pack;
- Does not perform another freeze action;
- Does not change the freeze date (remains 2026-07-31);
- Does not change pack version (remains v1.0);
- Does not perform DG-4;
- Does not allocate S05;
- Does not create a session;
- Does not open a session;
- Does not authorise examination;
- Does not examine RQ-032 through RQ-037;
- Does not answer an RQ;
- Does not create a Governance Finding;
- Does not prepare a Founder Review Package;
- Does not create a Founder Decision;
- Does not close D5;
- Does not commence D6 or D7;
- Does not evaluate Framework Evolution candidates;
- Does not evaluate FEF-FEV-001-FEC-001;
- Does not evaluate FEF-CCF-001;
- Does not evaluate or disposition CE1–CE6;
- Does not activate or draft FRAS;
- Does not perform constitutional consolidation;
- Does not adopt a lifecycle model;
- Does not classify legacy material.

## H. Correction Outcome

**Corrected — Pass with Conditions.**

The DG-3 freeze metadata is now internally consistent. The corrected frozen whole-file fingerprints at commit `663297a1f9d194bf85fcad9cb98d5dfccd95b86f` are the controlling values for all downstream verification. The assembly-state hashes remain valid historical references. The membership fingerprint remains unchanged.

See FEF-FGR-002-EP-005-FFICVR-001 for validation of this correction under the disclosed non-independent arrangement.

The post-freeze session-entry readiness reconciliation (FEF-FGR-002-D5-PFSERR-001) remains pending. DG-4 remains unperformed.
