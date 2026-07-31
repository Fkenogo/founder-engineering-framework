# FEF-FGR-002-EP-005-FR-001 — EP-005 Freeze Record

| Control Field             | Recorded Value                                             |
| ------------------------- | ---------------------------------------------------------- |
| Freeze record identifier  | FEF-FGR-002-EP-005-FR-001                                  |
| Pack identifier           | FEF-FGR-002-EP-005                                         |
| Pack version              | 1.0                                                        |
| Domain                    | D5 — Governance Lifecycle and Evolution                    |
| Freeze date               | 2026-07-31                                                 |
| Input repository baseline | `d9982b592ed5375cdc47a6c48f59c3d0d455dbc2`                 |
| Owner / Coordinator       | FEF-FGR-002-RA-002 — Review Administrator                  |
| Custodian                 | FEF-FGR-002-RA-005 — Evidence Custodian                    |
| Validator                 | FEF-FGR-002-RA-006 — non-independent combination disclosed |
| Freeze state              | **Frozen**                                                 |
| Validation verdict        | **Pass with Conditions**                                   |

## 1. Freeze Declaration

FEF-FGR-002-EP-005 v1.0 is frozen as the D5 Governance Lifecycle and Evolution evidence baseline.

The frozen membership is exactly 25 unique Evidence Records with 41 source-to-RQ mappings and 42 source-to-requirement links across 24 evidence requirements for RQ-032 through RQ-037. The membership, mappings, identities, paths, provenance commits, SHA-256 digests (including both disclosed acquisition-point digests each for EV-072 and EV-080, and the pre-loop acquisition digest for EV-081), authority classes, admissibility states, limitations, permitted uses, Open Question mappings, and D6/D7 interfaces are fixed by the pack and manifest.

This freeze follows the separately governed D5 EP-005 Evidence Pack Assembly (FEF-FGR-002-EP-005-AR-001, validated in FEF-FGR-002-EP-005-AVR-001) and the D5 EP-005 Pre-Freeze Programme and RQ-State Reconciliation (FEF-FGR-002-D5-PFRR-001, validated in FEF-FGR-002-D5-PFRVR-001), both of which confirmed the pack and manifest content unchanged from assembly through this freeze.

## 2. Frozen Artefact Fingerprints

### Correction Notice (v1.1)

> **FFICR-001 Correction:** v1.0 of this record incorrectly described the assembly-state (pre-freeze) whole-file hashes as the final frozen whole-file fingerprints. The DG-3 freeze commit (`663297a1f9d194bf85fcad9cb98d5dfccd95b86f`) added lifecycle-state annotations to both the Evidence Pack and Manifest, changing their byte content and therefore their SHA-256 digests. The assembly-state hashes remain valid historical controls but are not the final frozen whole-file fingerprints. This v1.1 correction records the actual frozen-state whole-file hashes as the controlling values for all downstream purposes, including DG-4 session-entry verification. The evidence-membership fingerprint is unaffected by the lifecycle annotations and remains unchanged. See [FEF-FGR-002-EP-005-FFICR-001](FEF-FGR-002-D5-EP-005-FROZEN-FINGERPRINT-INTEGRITY-CORRECTION-RECORD.md) and [FEF-FGR-002-EP-005-FFICVR-001](FEF-FGR-002-D5-EP-005-FROZEN-FINGERPRINT-INTEGRITY-CORRECTION-VALIDATION-REPORT.md) for full detail.

### Assembly-State Whole-File Fingerprints (Historical)

These fingerprints identify the final assembled, pre-freeze files at assembly commit `b8490aa434eec518fbb110e21b55e0a3e7335262` and pre-freeze reconciliation commit `d9982b592ed5375cdc47a6c48f59c3d0d455dbc2`. They remain valid historical controls.

| Assembly Artefact                        | SHA-256                                                            |
| ---------------------------------------- | ------------------------------------------------------------------ |
| `FEF-FGR-002-D5-EP-005-EVIDENCE-PACK.md` | `edcc5a94e652a9a15784ee7318f72946a140ea1450c4f4a1132856ebfc0d7f4e` |
| `FEF-FGR-002-D5-EP-005-MANIFEST.md`      | `4b9538a9debcbfbaaf8bdab7dfdd6544bca672a6e090f11e017456a470b3f9a8` |

### Controlling Frozen Whole-File Fingerprints

These fingerprints identify the final lifecycle-annotated frozen files produced by the DG-3 freeze commit (`663297a1f9d194bf85fcad9cb98d5dfccd95b86f`). They are the controlling values for all downstream purposes, including any future DG-4 session-entry verification.

| Frozen Artefact                          | SHA-256                                                            |
| ---------------------------------------- | ------------------------------------------------------------------ |
| `FEF-FGR-002-D5-EP-005-EVIDENCE-PACK.md` | `1e86b9fbd888c17c8368df289364cb460e4066472a1dffd2c0f1d5b923971b09` |
| `FEF-FGR-002-D5-EP-005-MANIFEST.md`      | `e0caaad8a79cb13c9cdb30b8c1b2cd6787078bfd8497894342d1592398c293b9` |

### Membership Fingerprint (Unchanged)

The evidence-membership fingerprint (`59414d0803ed114171c35a821d4581a80e8df92121260d868eaee4fd76e925fc`, recorded in the pack's own Section 9 and computed from the ordered Evidence Record digest inputs) is independent of lifecycle annotations and remains unchanged across assembly, pre-freeze reconciliation, and freeze.

## 3. Source Integrity at Freeze (v1.1)

Source integrity was independently reconfirmed unchanged in FEF-FGR-002-EP-005-FFICVR-001: the freeze commit changed only lifecycle/control annotations and did not alter any evidence membership, evidence identity, source digest, qualification, mapping, limitation, permitted use, Open Question, or special-evidence control.

| Check                                 | Result                                                                                    |
| ------------------------------------- | ----------------------------------------------------------------------------------------- |
| Evidence membership                   | 25/25 exact                                                                               |
| Evidence Register identity            | 25/25 present in v1.19                                                                    |
| Source paths                          | 25/25 exist                                                                               |
| Source SHA-256                        | 25/25 match qualification and manifest values                                             |
| Provenance commits                    | 25/25 preserved                                                                           |
| Authority classes                     | 25/25 preserved                                                                           |
| EV-072 dual acquisition-point digests | Both preserved and distinct from the Document Manifest's current live state               |
| EV-080 dual acquisition-point digests | Both preserved and distinct from the Master Programme's current live state (now v0.66)    |
| EV-081 pre-loop acquisition digest    | Preserved and distinct from the Review Question Register's current live state (now v1.51) |
| EV-078 two-requirement RQ-035 linkage | Preserved and unmerged                                                                    |

## 4. Special Evidence Controls Confirmed at Freeze

### 4.1 EV-072 and EV-080

Both remain live, continuously-updated controlled documents whose current repository state has continued to diverge from their disclosed D5 acquisition-point observations (the Document Manifest and Master Programme have each been further revised multiple times since EV-072's and EV-080's respective D5 qualification acquisitions). Freeze fixes only the disclosed acquisition-point digests recorded in the manifest; it does not adopt either document's current state as evidence, and does not require or imply that either document's later content be reconciled against the frozen pack.

### 4.2 EV-078

EV-078 remains `E1 — Admitted`, a correction/recovery example only, never an ordinary amendment precedent. Its RQ-033, RQ-035 (two requirement links), and RQ-037 uses remain distinct and unmerged in the frozen manifest.

## 5. Lifecycle Effect

| Item                  | State after Freeze                                                                  |
| --------------------- | ----------------------------------------------------------------------------------- |
| D5                    | Mobilised — Effective                                                               |
| RQ-032 through RQ-037 | Admitted; **Evidence Pack Frozen — EP-005 v1.0**; Not Examined; Disposition Pending |
| EP-005                | **Frozen — v1.0**                                                                   |
| D5 session            | Not created                                                                         |
| Examination           | Not commenced                                                                       |
| Governance Findings   | None                                                                                |
| Founder Decisions     | None                                                                                |
| D6 / D7               | Not reached                                                                         |

## 6. Non-Effects

This freeze does not answer a Review Question, evaluate evidence sufficiency, resolve a gap or Open Question, produce a Governance Finding, prepare a Founder Decision, create or open a session, commence examination, commence D6 or D7, activate or draft FRAS, evaluate FEF-FEV-001-FEC-001 or FEF-CCF-001, evaluate or disposition CE1–CE6, perform constitutional consolidation, adopt a lifecycle or legacy-classification rule, or retrospectively validate or invalidate any legacy governance material.

## 7. Post-Freeze Change Control

Any later membership, mapping, source-treatment, or source-content change to EP-005 requires an explicitly governed successor or supplemental pack and revalidation. The frozen v1.0 pack and manifest files must not be silently rewritten.

## 8. Conditions

1. A future session-entry gate must reverify this exact frozen pack, manifest, and their fingerprints before authorising examination.
2. Examination, once separately authorised, must use only each RQ's mapped EP-005 items.
3. All source authority, admissibility, limitation, uncertainty, and permitted-use controls, including the EV-072, EV-080, and EV-081 acquisition-point boundaries, must remain visible.
4. EV-078's correction/recovery-only character and its two distinct RQ-035 requirement links must remain explicit and unmerged.
5. All Open Questions, evidence gaps, and D6/D7 interfaces must remain unresolved unless a later authorised governance activity changes them.
6. Pack inclusion must not be treated as evidence sufficiency, truth, recommendation, or an RQ answer.
7. Non-independent preparation, assembly, and freeze must remain disclosed.

**Pack state: Frozen — v1.0 — Pass with Conditions.**

### Record Version History

| Version | Date       | Change                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       | Authority                                                                 |
| ------- | ---------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------- |
| 1.0     | 2026-07-31 | Original freeze declaration — incorrectly recorded assembly-state hashes as controlling frozen whole-file fingerprints                                                                                                                                                                                                                                                                                                                                                                       | FEF-FGR-002-RA-002, RA-005, RA-006; non-independent combination disclosed |
| 1.1     | 2026-07-31 | Corrected frozen whole-file fingerprints to the actual post-freeze-annotation hashes at commit `663297a1f9d194bf85fcad9cb98d5dfccd95b86f`; assembly-state hashes preserved as historical; membership fingerprint unchanged; correction recorded in [FEF-FGR-002-EP-005-FFICR-001](FEF-FGR-002-D5-EP-005-FROZEN-FINGERPRINT-INTEGRITY-CORRECTION-RECORD.md), validated in [FEF-FGR-002-EP-005-FFICVR-001](FEF-FGR-002-D5-EP-005-FROZEN-FINGERPRINT-INTEGRITY-CORRECTION-VALIDATION-REPORT.md) | FEF-FGR-002-RA-002, RA-006; non-independent combination disclosed         |
