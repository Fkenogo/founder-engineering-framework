# FEF-FGR-002-EP-005-PMCVR-001 — EP-005 v2.0 Provenance and Membership-Control Remediation Validation Report

| Control Field | Recorded Value |
|---|---|
| Validation identifier | FEF-FGR-002-EP-005-PMCVR-001 |
| Remediation validated | FEF-FGR-002-EP-005-PMCR-001 |
| Pack identifier and version | FEF-FGR-002-EP-005 v2.0 |
| Companion manifest | FEF-FGR-002-EP-005-MAN-002 |
| Domain | D5 — Governance Lifecycle and Evolution |
| Validation date | 2026-07-31 |
| Submitted repository baseline | `9c7d22ab19628f9b9456bb61814b3b7503987a9f` |
| Validator | FEF-FGR-002-RA-006 — non-independent combination disclosed |
| Verdict | **Pass with Conditions** |

## 1. Purpose, Authority, and Boundary

The Founder accepted PMCR-001 and the prepared successor artefacts and separately authorised bounded remediation revalidation. This report performs that revalidation against the exact submitted files at commit `9c7d22a`.

This report does not perform DG-3, freeze or modify the successor, create frozen-state fingerprints, resume DG-4, allocate S05, create or open a session, authorise or commence examination, answer a Review Question, create a Governance Finding or Founder Decision, close D5, or commence D6/D7.

## 2. Governing Method and Precedent

| Control | Requirement | Validation application |
|---|---|---|
| FEF-EPS-001 §7.2 | A changed post-freeze integrity value requires a major version and re-freeze | v2.0 is the required major-version successor; re-freeze remains separate |
| FEF-EPS-001 §7.3 | Never overwrite a frozen pack; link corrections to a successor | v1.0 and MAN-001 are preserved; v2.0 and MAN-002 are linked successors |
| FEF-EPS-001 §11.2 | Preserve, open successor, state trigger, identify changes, reassess, revalidate, re-freeze, notify roles | PMCR-001 completed construction and impact assessment; this report performs revalidation only |
| FEF-EPS-001 §12.3 | Check integrity at acquisition, freeze, session entry, transfer, and final assembly; mismatch is Critical until resolved or bounded | Historical acquisitions, submitted files, predecessor files, and the reconstructed ledger were directly rechecked |
| FEF-FGRER-001 §§5–5.2 | Validation must not create missing evidence or change lifecycle by assumption; failure preserves and returns the failed version | No evidence was created or silently repaired; no failed-validation correction was needed |
| FEF-FGRER-001 §§10 and 15 | Critical integrity failures stop affected execution; defects remain traceable | DG-4 remains stopped and v1.0 remains reliance-blocked |

Precedent establishes `Pass`, `Pass with Conditions`, and `Fail` as validation verdicts, RA-006 as validator under a disclosed non-independent combined capacity, paired validation identifiers ending `VR-001`, registration in the Document Manifest, and a separate later DG-3 control. The collision-free paired identifier is `FEF-FGR-002-EP-005-PMCVR-001`.

A Supplemental Pack is not adequate: it would add a child control while leaving the parent pack's own provenance and membership input defective. The complete linked major-version successor is the applicable correction mechanism.

## 3. Repository and Submitted-Baseline Verification

| Check | Result |
|---|---|
| Branch and entry SHA | Pass — `main` at `9c7d22ab19628f9b9456bb61814b3b7503987a9f` |
| Remote alignment | Pass — `origin/main` matched; divergence `0/0` |
| Entry worktree and operations | Pass — clean; no staged, untracked, deleted, conflicted, merge, rebase, cherry-pick, revert, or lock state |
| Submitted v2.0 SHA-256 | Pass — `5595bee43f5b88c4d3536371f498b5bd7b84b1808c9b2307a5a0136dbf134dc6` |
| Submitted MAN-002 SHA-256 | Pass — `38705706c03026325d86467282ef28e9931567c7a469e55069a5a1974c418827` |
| Byte identity to `9c7d22a` | Pass — both files unchanged |

These are validated construction-state controls, not frozen-state fingerprints. No annotation was added to either submitted artefact. Their embedded `Validation Pending` wording records their submitted construction state; this validation report and the Evidence Pack Register record the later current lifecycle state **Remediation-Validated — Not Frozen** without changing their bytes.

## 4. Historical EV-072 Provenance Reproduction

Each digest was independently generated over the raw historical Git object for `docs/programme/FEF-DOCUMENT-MANIFEST.md`. No live file was substituted.

| Acquisition | Full Git commit | Reproduced SHA-256 | Disposition |
|---|---|---|---|
| D4 RQ-025 | `533b694d75db4a3377edc7a6dccf5ec2b41ebbd5` | `31807d1de36002ebf359348bea764f8711476405de5c08669f0586c48853502d` | Pass — historical D4 input; excluded from successor D5 membership |
| D5 RQ-032 | `bb47b0bc514f9f147b37b7131720cbca5590f800` | `c26de951d3a14d10954505bb035ac7dd38e2c2ae0c1b521c0907c009a8beb8ac` | Pass — first D5 acquisition |
| D5 RQ-034 | `42de97ed065f44f7e89cf6c32637f0aacaee93df` | `543ec7643017f6a2e8fc4bd2eb5a4681e1056814786049b0d63b1296a4a99a98` | Pass — second D5 acquisition |

The D5 commits and digests are distinct and ordered by Execution Loop 001 before Execution Loop 003.

## 5. Independent Canonical Membership Reconstruction

The validated algorithm is SHA-256 over 25 numerically ordered UTF-8 lines in `EV-NNN:<digest>` form, dual acquisition digests joined with `|`, and one trailing newline.

```text
EV-005:e007510ba3eb3a115177522c041bb91284f5f0efe3fdd3f185c7565c09c52d72
EV-007:eb1e59544a32888bc3b20b5f87a0bb5342f350539946782196d5a31757ba6568
EV-008:625cbd574e8354fc8ed6191b4c87cdce9d66d781ebfe1f43c3ac0b31e643a35f
EV-009:ab32f0527d7c99c7562c2c959e1426c10d6dd81a9fa4d2518c9c3059fff3a237
EV-010:41f5b4eb4c3d553ea1e6b3c1566153541ecc74ad3468f7dfe281f3e354165bf3
EV-012:c14ff1a7508af23259f498b6d0a5305f9f3f7bde94892e933b7d526ee20f6be5
EV-013:ed20b516270839d8ce24561548de0c345a9fb28e7cc76312aa9e4e65e8f3d56b
EV-014:ade6b4ed4ff1af5c234d851c23d46a8b89322461e6f5fe02f48f8d62b368c145
EV-017:415f61a8fa11fb2792e1d87c4b0f4a10c60ad242c82b69aefbfdebb17b3b94e6
EV-066:1e3eb7286f6a07a38ee1c3bf4259bea0a755c64dd133ddd65204b788bfdee7f4
EV-070:7970e6e159cbf2de454c986d44af830fab65ef915066dc9b5b746d04e55bae16
EV-072:c26de951d3a14d10954505bb035ac7dd38e2c2ae0c1b521c0907c009a8beb8ac|543ec7643017f6a2e8fc4bd2eb5a4681e1056814786049b0d63b1296a4a99a98
EV-073:5e98e29ffda20ac4fb87d50b0eeea5abb45e2963e570a08a0e9c2627465f8b30
EV-074:c2755fa642c6ae0854a618aa0cc0e85f237bd60f91982125aa7415d1688e3aa5
EV-075:95701a0eafeee644aad38925bbadf9e41702b72ebbcd73281c6a1c4d9cb7f331
EV-076:44bc7c365fe20c80f116222629e087027f742145ad0f3f57e40655db0fbd5acf
EV-077:428fc9073d85c2a2cfa02de5f98c4021bfbf57b2065b0f66b22d1454364f1d59
EV-078:c79385ffba6698dfe77959a2331799e017ef6b89c5cb55965a601474b13946f9
EV-079:1630eb575de4716b7a97061f780478a4851cbdf2ec77fe04376094868f054263
EV-080:7f4e7edfeeb7768f8822e9599ac92c0f082061562279f752544bbf123aee97b0|39d2e70426cc91edd1a0c2b7d84756e2bcf7d3883991cc09aca67cc70c9f895e
EV-081:f25d51c0785c565613123d2a8eeb762fb7ddf6e86009f0772a46721a5c0b77f5
EV-082:c45c3877923ac551347b21d9c6002c45d0d3d98324f7b1f1d6f0f5cc326c6288
EV-083:b2689e9821d54612354202e9af9e4ec212a7aec5afabfebe2d80f72b7ecebfd4
EV-084:79420c304f8cc6f7db3229cf8027d332b18344e502124657c91ddf516be6164f
EV-085:787193af41822a4c5de33770a19e9f11f7cb5b714392ab76935d55e7be990614
```

Two independent calculations reproduced:

`c3a88eb9cbb2c8e4b38ee18cdc9c5f92a11087dcfd2ea66a32ea668766571a0f`

The calculation preserves EV-080 order and every non-EV-072 input. Replacing only the corrected EV-072 line with v1.0's defective pair reconstructs the historical fingerprint `59414d0803ed114171c35a821d4581a80e8df92121260d868eaee4fd76e925fc`. This proves that only EV-072's selected pair changed.

The candidate fingerprint is now validated for successor v2.0, but it is not a frozen-state control and cannot support session reliance until DG-3 is separately authorised and completed.

## 6. Corpus and Treatment Preservation

| Check | Expected | Reproduced | Result |
|---|---:|---:|---|
| Evidence Records | 25 | 25 | Pass |
| Source-to-RQ mappings | 41 | 41 | Pass |
| Source-to-requirement links | 42 | 42 | Pass |
| Evidence requirements | 24 | 24 | Pass |
| RQ scope | 6 | RQ-032 through RQ-037 | Pass |

The v1.0 and v2.0 manifest catalogues were compared field-by-field. Every non-EV-072 membership row is identical. EV-072 retains its identity, title, path, E2 class, Conditionally Admitted state, and RQ-032/RQ-034 mappings; only its two provenance inputs are corrected. All 24 requirement rows are identical.

Evidence class, authority, admissibility, qualification, RQ and requirement mappings, limitations, uncertainty, permitted uses, special-evidence constraints, eight Open Questions, and D6/D7 boundaries are unchanged. Exact RQ wording was rechecked for all six questions. RQ-032 through RQ-037 remain Admitted, Pending, Unexamined, and assigned to no session.

## 7. Predecessor Protection and Fingerprint Control

| Artefact/control | Result |
|---|---|
| Frozen v1.0 pack | Pass — byte-identical to `663297a`; SHA-256 `1e86b9fbd888c17c8368df289364cb460e4066472a1dffd2c0f1d5b923971b09` |
| Frozen MAN-001 | Pass — byte-identical to `663297a`; SHA-256 `e0caaad8a79cb13c9cdb30b8c1b2cd6787078bfd8497894342d1592398c293b9` |
| Historical membership fingerprint | Preserved — `59414d0803ed114171c35a821d4581a80e8df92121260d868eaee4fd76e925fc` |
| v1.0 reliance | Blocked; historical traceability only |
| v2.0 successor | Remediation-Validated — Not Frozen; unusable for DG-4 |

No two fingerprint sets are represented as concurrently controlling. The v1.0 set is historical and reliance-blocked. The validated v2.0 membership value is not controlling for session use until separately authorised DG-3 re-freeze establishes the successor frozen-state control set.

## 8. Programme-Control Reconciliation and Correction

Master Programme §7 contained one stale current-state paragraph before its historical narrative heading: “EP-005 is Frozen — v1.0. DG-4 remains unperformed…”. The Founder expressly authorised its correction. The minimum paragraph was replaced to record v1.0 as the frozen historical reliance-blocked predecessor, the incomplete attempted DG-4 and absence of verdict, the v2.0/MAN-002 validation state, S05 and session/examination non-effects, and D6/D7 boundaries. Master Programme v0.71 records that correction transparently.

PMCR-001, the Evidence Pack Register, Review Identity, Review Question Register, D5 RQ Set, Master Programme, Founder Dashboard, Document Manifest, and unchanged Session Register were reconciled. Current controls now distinguish the successor's submitted `Validation Pending` annotation from its post-report **Remediation-Validated — Not Frozen** state. The submitted pack and manifest were not modified.

## 9. Prohibited-Activity and Protected-State Verification

| Boundary | Result |
|---|---|
| Modify v1.0 or MAN-001 | Not performed |
| Modify submitted v2.0 or MAN-002 | Not performed |
| DG-3 or successor freeze | Not performed |
| Declare successor frozen-state hashes | Not performed |
| Resume or complete DG-4 | Not performed; incomplete with no verdict |
| Allocate S05 or create/open a session | Not performed |
| Authorise or commence examination | Not performed |
| Answer an RQ or create a GF/FD | Not performed |
| Close D5 or commence D6/D7 | Not performed |
| Change RQ wording, Open Questions, evidence treatment, D1–D4, Framework Evolution, FRAS, or constitutional material | Not performed |

## 10. Conditions

1. EP-005 v2.0 and MAN-002 remain **Not Frozen** and unusable for DG-4 or examination.
2. Separate Founder authorisation is required before DG-3 re-freeze; this validation does not authorise or perform it.
3. DG-3 must verify the exact remediation-validated submitted artefacts and establish successor frozen-state fingerprints; the construction hashes above must not be relabelled as frozen-state controls.
4. The validated membership fingerprint must remain associated only with the corrected D5 EV-072 pair and must be reverified at DG-3.
5. All evidence authority, admissibility, qualification, limitation, uncertainty, permitted-use, special-evidence, Open Question, and D6/D7 controls remain binding.
6. Non-independent validation by FEF-FGR-002-RA-006 remains disclosed.

## 11. Verdict and Next Governed Activity

**Pass with Conditions.**

FEF-FGR-002-EP-005 v2.0 and MAN-002 are remediation-validated and ready for a separately authorised DG-3 re-freeze. They remain Not Frozen and unusable for DG-4. The next governed activity is Founder review of this report and separate DG-3 re-freeze authorisation.
