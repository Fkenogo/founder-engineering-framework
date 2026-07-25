# FEF-FGR-002 — Evidence Pack Register

| Control Field | Recorded Value |
|---|---|
| Register identifier | FEF-FGR-002-EPR-001 |
| Register class | Evidence Pack Register |
| Review identifier | FEF-FGR-002 |
| Register version | 1.4 |
| Lifecycle state | Active |
| Created date | 2026-07-24 |
| Controlling instruments | FEF-FGRC-001; FEF-FGRA-001; FEF-FGRP-001 |
| Applicable specification | [FEF-EPS-001](../FEF-EPS-001-EVIDENCE-PACK-SPECIFICATION.md) |
| Control owner | FEF-FGR-002-RA-005 — Evidence Custodian |
| Validator | FEF-FGR-002-RA-006 — Validator; non-independent combination disclosed |
| Access treatment | Repository-controlled governance record; pack-specific treatment required |
| Integrity control | Pack SHA-256 recorded in domain Evidence Mobilisation Validation Reports |
| Last validation date | 2026-07-25 |
| Substantive entry count | 2 |

## Register

| Pack ID | Version | Domain | Related RQs | Manifest | Lifecycle State | Freeze Date | Session Use | Integrity Record | Access Treatment | Supersedes | Validation |
|---|---:|---|---|---|---|---|---|---|---|---|---|
| FEF-FGR-002-EP-001 | 1.0 | D1 — Governance Authority | RQ-001–RQ-008 | 21 Evidence Records | Frozen | 2026-07-24 | S01 — Closed | Source and pack hashes recorded | Repository-controlled | None | Pass with disclosed non-independent condition |
| FEF-FGR-002-EP-002 | 1.0 | D2 — Evidence Governance | RQ-009–RQ-015 | 21 Evidence Records | Frozen | 2026-07-25 | S02 entry validated; session not opened and zero examination use | Source and pack hashes recorded in FEF-FGR-002-D2-EMVR-001 and reverified in FEF-FGR-002-S02-EVR-001 | Repository-controlled | None | Pass with disclosed non-independent condition |

## Change History

| Version | Date | Change | Authority |
|---|---|---|---|
| 1.0 | 2026-07-24 | Empty register instantiated | FD-2026-07-24-009 and FEF-FRCD-001 |
| 1.1 | 2026-07-24 | Initial D1 Evidence Pack v1.0 registered as Frozen | RA-005 and RA-006 |
| 1.2 | 2026-07-24 | Frozen pack use recorded for closed Session S01 | FEF-FGR-002-S01 |
| 1.3 | 2026-07-25 | D2 Evidence Pack EP-002 v1.0 registered as Frozen and validated; no session use | FEF-FGR-002-D2-EMVR-001 |
| 1.4 | 2026-07-25 | EP-002 fingerprint, membership, treatments, and RQ coverage reverified for S02 entry; session remains unopened | FEF-FGR-002-S02-EVR-001 |

## Non-Effects

This register contains two Frozen Evidence Packs. EP-001 use is closed with
S01. EP-002 is assigned only to the entry-validated S02 identity; it has zero
examination use and does not itself open a D2 session. Post-freeze change
requires a successor or Supplemental Pack.
