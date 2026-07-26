# FEF-FGR-002 — Evidence Pack Register

| Control Field | Recorded Value |
|---|---|
| Register identifier | FEF-FGR-002-EPR-001 |
| Register class | Evidence Pack Register |
| Review identifier | FEF-FGR-002 |
| Register version | 1.7 |
| Lifecycle state | Active |
| Created date | 2026-07-24 |
| Controlling instruments | FEF-FGRC-001; FEF-FGRA-001; FEF-FGRP-001 |
| Applicable specification | [FEF-EPS-001](../FEF-EPS-001-EVIDENCE-PACK-SPECIFICATION.md) |
| Control owner | FEF-FGR-002-RA-005 — Evidence Custodian |
| Validator | FEF-FGR-002-RA-006 — Validator; non-independent combination disclosed |
| Access treatment | Repository-controlled governance record; pack-specific treatment required |
| Integrity control | Pack SHA-256 recorded in domain Evidence Mobilisation Validation Reports and, for EP-003, in the pack's own Integrity Manifest (§11) |
| Last validation date | 2026-07-26 |
| Substantive entry count | 3 |

## Register

| Pack ID | Version | Domain | Related RQs | Manifest | Lifecycle State | Freeze Date | Session Use | Integrity Record | Access Treatment | Supersedes | Validation |
|---|---:|---|---|---|---|---|---|---|---|---|---|
| FEF-FGR-002-EP-001 | 1.0 | D1 — Governance Authority | RQ-001–RQ-008 | 21 Evidence Records | Frozen | 2026-07-24 | S01 — Closed | Source and pack hashes recorded | Repository-controlled | None | Pass with disclosed non-independent condition |
| FEF-FGR-002-EP-002 | 1.0 | D2 — Evidence Governance | RQ-009–RQ-015 | 21 Evidence Records | Frozen | 2026-07-25 | S02 — Closed; sole examination baseline | Source and pack hashes recorded in FEF-FGR-002-D2-EMVR-001 and reverified at entry and post-session validation | Repository-controlled | None | Pass with disclosed non-independent condition |
| FEF-FGR-002-EP-003 | 1.0 | D3 — Governance Assurance | RQ-016–RQ-024 | 39 Evidence Records (17 reused, 22 new) | Frozen | 2026-07-26 | Unassigned — no D3 session exists | SHA-256 digests recorded in the pack's own Integrity Manifest (§11); reused items carry forward D1/D2 integrity values | Repository-controlled | None | Pass with Conditions — non-independent; RQ-018 gap and EV-058/EV-059 contradictions disclosed |

## D2 Output Linkage

EP-002 v1.0 is the sole frozen evidence baseline for S02, GF-009 through
GF-014, and FD-011 through FD-016. Exact relationships are controlled by the
[D2 Traceability Register](FEF-FGR-002-D2-TRACEABILITY-REGISTER.md). This
linkage does not modify or re-freeze EP-002.

## D3 Output Linkage

EP-003 v1.0 is frozen but has **no session, Governance Finding, or Founder
Decision linkage yet** — no D3 session has been opened. It will become the
controlling evidence baseline only once a D3 session-entry validation
(DG-4) is separately performed and cites this exact frozen version. This
entry does not itself authorise that step.

## Change History

| Version | Date | Change | Authority |
|---|---|---|---|
| 1.0 | 2026-07-24 | Empty register instantiated | FD-2026-07-24-009 and FEF-FRCD-001 |
| 1.1 | 2026-07-24 | Initial D1 Evidence Pack v1.0 registered as Frozen | RA-005 and RA-006 |
| 1.2 | 2026-07-24 | Frozen pack use recorded for closed Session S01 | FEF-FGR-002-S01 |
| 1.3 | 2026-07-25 | D2 Evidence Pack EP-002 v1.0 registered as Frozen and validated; no session use | FEF-FGR-002-D2-EMVR-001 |
| 1.4 | 2026-07-25 | EP-002 fingerprint, membership, treatments, and RQ coverage reverified for S02 entry; session remains unopened | FEF-FGR-002-S02-EVR-001 |
| 1.5 | 2026-07-25 | Frozen EP-002 recorded as the sole evidence baseline used for closed S02; no post-freeze source used | FEF-FGR-002-S02 |
| 1.6 | 2026-07-25 | EP-002 linked to GF-009 through GF-014 and FD-011 through FD-016 without changing frozen content or treatment | Founder Directive — D2 Governance Finding Dispositions |
| 1.7 | 2026-07-26 | D3 Evidence Pack EP-003 v1.0 registered as Frozen following DG-3 (Pass with Conditions); 39 Evidence Records (17 reused, 22 new); RQ-018 gap and EV-058/EV-059 contradictions carried forward as disclosed conditions; no session use, no GF, no FD | FEF-FGR-002-EP-003; FEF-FGR-002-RA-002, RA-005, RA-006 — non-independent combination disclosed |

## Non-Effects

This register contains three Frozen Evidence Packs. EP-001 use is closed
with S01 and EP-002 use is closed with S02. EP-003 is frozen but has no
session use; no D3 session, Governance Finding, or Founder Decision exists.
No post-freeze evidence was used in S01 or S02. Post-freeze change requires
a successor or Supplemental Pack.
