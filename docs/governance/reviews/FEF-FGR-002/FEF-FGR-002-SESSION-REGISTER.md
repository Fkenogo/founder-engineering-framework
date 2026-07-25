# FEF-FGR-002 — Session Register

| Control Field | Recorded Value |
|---|---|
| Register identifier | FEF-FGR-002-SR-001 |
| Register class | Session Register |
| Review identifier | FEF-FGR-002 |
| Register version | 1.2 |
| Lifecycle state | Active |
| Created date | 2026-07-24 |
| Controlling instruments | FEF-FGRC-001; FEF-FGRA-001; FEF-FGRP-001; FEF-FGRER-001 |
| Applicable template | [Founder Governance Review Session Record Template](../../../templates/FEF-FOUNDER-GOVERNANCE-REVIEW-SESSION-RECORD-TEMPLATE.md) |
| Control owner | FEF-FGR-002-RA-002 — Review Administrator |
| Validator | FEF-FGR-002-RA-006 — Validator; non-independent combination disclosed |
| Access treatment | Repository-controlled governance record |
| Integrity control | SHA-256 recorded in implementation validation report |
| Last validation date | 2026-07-25 |
| Registered session identity count | 2 |
| Opened session count | 1 |

## Register

| Session ID | Domain | Purpose | Related RQs | Evidence Pack | Planned State | Entry-Gate State | Session State | Record Location | Validation |
|---|---|---|---|---|---|---|---|---|---|
| FEF-FGR-002-S01 | D1 — Governance Authority | Examine the eight admitted D1 RQs and produce validated GFs | RQ-001–RQ-008 | EP-001 v1.0 — Frozen | Execute and close | Pass with condition | Closed — Validated with Condition | [Session Record](FEF-FGR-002-S01-SESSION-RECORD.md) | Pass with recorded non-independent condition |
| FEF-FGR-002-S02 | D2 — Evidence Governance | Examine the seven admitted D2 RQs using EP-002 only after separate opening | RQ-009–RQ-015 | EP-002 v1.0 — Frozen | Entry validate, then separately open | Pass with Conditions | Entry Validated — Not Opened | [Session Record](FEF-FGR-002-S02-SESSION-RECORD.md) | [Pass with Conditions](FEF-FGR-002-S02-ENTRY-VALIDATION-REPORT.md) |

## Change History

| Version | Date | Change | Authority |
|---|---|---|---|
| 1.0 | 2026-07-24 | Empty register instantiated | FD-2026-07-24-009 and FEF-FRCD-001 |
| 1.1 | 2026-07-24 | S01 created, opened after DG-4 pass, executed, and closed | FEF-FGR-002-003 |
| 1.2 | 2026-07-25 | Collision-safe S02 identity allocated and DG-4 entry validated with conditions; session not opened | FEF-FGR-002-S02-EVR-001 |

## Non-Effects

This register contains one closed session and one entry-validated session
identity that has not been opened. S02 registration and entry validation do
not examine evidence, answer an RQ, issue an FD, create or approve a GF, close
an OQ, or authorise downstream work beyond the separate operational opening.
