# FEF-FGR-002 — Evidence Pack Register

| Control Field | Recorded Value |
|---|---|
| Register identifier | FEF-FGR-002-EPR-001 |
| Register class | Evidence Pack Register |
| Review identifier | FEF-FGR-002 |
| Register version | 1.10 |
| Lifecycle state | Active |
| Created date | 2026-07-24 |
| Controlling instruments | FEF-FGRC-001; FEF-FGRA-001; FEF-FGRP-001 |
| Applicable specification | [FEF-EPS-001](../FEF-EPS-001-EVIDENCE-PACK-SPECIFICATION.md) |
| Control owner | FEF-FGR-002-RA-005 — Evidence Custodian |
| Validator | FEF-FGR-002-RA-006 — Validator; non-independent combination disclosed |
| Access treatment | Repository-controlled governance record; pack-specific treatment required |
| Integrity control | Pack SHA-256 recorded in domain validation records; EP-003 records its Integrity Manifest in-pack; EP-004 pack, manifest, and freeze fingerprints are controlled by FEF-FGR-002-EP-004-FR-001 and reverified in FEF-FGR-002-EP-004-VR-001; EP-005 pack, manifest, and freeze fingerprints are controlled by FEF-FGR-002-EP-005-FR-001 and reverified in FEF-FGR-002-EP-005-VR-001 |
| Last validation date | 2026-07-31 |
| Substantive entry count | 5 |

## Register

| Pack ID | Version | Domain | Related RQs | Manifest | Lifecycle State | Freeze Date | Session Use | Integrity Record | Access Treatment | Supersedes | Validation |
|---|---:|---|---|---|---|---|---|---|---|---|---|
| FEF-FGR-002-EP-001 | 1.0 | D1 — Governance Authority | RQ-001–RQ-008 | 21 Evidence Records | Frozen | 2026-07-24 | S01 — Closed | Source and pack hashes recorded | Repository-controlled | None | Pass with disclosed non-independent condition |
| FEF-FGR-002-EP-002 | 1.0 | D2 — Evidence Governance | RQ-009–RQ-015 | 21 Evidence Records | Frozen | 2026-07-25 | S02 — Closed; sole examination baseline | Source and pack hashes recorded in FEF-FGR-002-D2-EMVR-001 and reverified at entry and post-session validation | Repository-controlled | None | Pass with disclosed non-independent condition |
| FEF-FGR-002-EP-003 | 1.0 | D3 — Governance Assurance | RQ-016–RQ-024 | 39 Evidence Records (17 reused, 22 new) | Frozen | 2026-07-26 | Unassigned — no D3 session exists | SHA-256 digests recorded in the pack's own Integrity Manifest (§11); reused items carry forward D1/D2 integrity values | Repository-controlled | None | Pass with Conditions — non-independent; RQ-018 gap and EV-058/EV-059 contradictions disclosed |
| FEF-FGR-002-EP-004 | 1.0 | D4 — Records and Information Governance | RQ-025–RQ-031 | 19 Evidence Records; 65 source-to-RQ mappings; 72 source-to-requirement links | Frozen | 2026-07-28 | Unassigned — no D4 session exists | Pack and manifest SHA-256 recorded in FEF-FGR-002-EP-004-FR-001; source and frozen-artefact hashes reverified in FEF-FGR-002-EP-004-VR-001 | Repository-controlled | None | Pass with Conditions — non-independent; evidence gaps, EV-059 contradiction, EV-074 boundary, Open Questions, and D5/D6 interfaces preserved |
| FEF-FGR-002-EP-005 | 1.0 | D5 — Governance Lifecycle and Evolution | RQ-032–RQ-037 | 25 Evidence Records; 41 source-to-RQ mappings; 42 source-to-requirement links | Frozen | 2026-07-31 | Unassigned — no D5 session exists | Pack and manifest SHA-256 recorded in FEF-FGR-002-EP-005-FR-001; membership fingerprint recorded in-pack; reverified in FEF-FGR-002-EP-005-VR-001 | Repository-controlled | None | Pass with Conditions — non-independent; evidence gaps, Open Questions, EV-072/EV-080/EV-081 acquisition-point boundaries, and D6/D7 interfaces preserved |

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

## D4 Output Linkage

EP-004 v1.0 is Frozen with no session, Governance Finding, or Founder
Decision linkage. A separately governed D4 session-entry gate must reverify
the exact frozen pack, manifest, freeze record, source currency, and
fingerprints before authorising any examination. This register entry does
not itself authorise that step.

## D5 Output Linkage

EP-005 v1.0 is **Frozen**, with no session, Governance Finding, or Founder
Decision linkage. Like EP-001 through EP-004, freeze does not authorise
examination and does not imply that a session-entry gate may proceed. A
separately governed D5 session-entry validation must occur, reverifying
this exact frozen pack, manifest, freeze record, and their fingerprints,
before any examination may be authorised. This register entry does not
itself authorise session entry or examination.

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
| 1.8 | 2026-07-28 | D4 Evidence Pack EP-004 v1.0 registered as Frozen following exact assembly of the reconciled 19-record corpus with 65 source-to-RQ mappings and 72 source-to-requirement links; Pass with Conditions; no session use, examination, RQ answer, GF, or FD | FEF-FGR-002-EP-004-FR-001; FEF-FGR-002-EP-004-VR-001 |
| 1.9 | 2026-07-30 | D5 Evidence Pack EP-005 v1.0 registered as **Assembled — Not Frozen** following exact assembly of the reconciled 25-record corpus with 41 source-to-RQ mappings and 42 source-to-requirement links; Pass with Conditions; no freeze, session use, examination, RQ answer, GF, or FD; EV-072/EV-080/EV-081 acquisition-point boundaries and all D5 Open Questions and gaps preserved | FEF-FGR-002-EP-005-AR-001; FEF-FGR-002-EP-005-AVR-001 |
| 1.10 | 2026-07-31 | D5 Evidence Pack EP-005 v1.0 registered as **Frozen** following DG-3 (Pass with Conditions); the D5 EP-005 Pre-Freeze Programme and RQ-State Reconciliation (FEF-FGR-002-D5-PFRR-001) independently reverified the pack, manifest, and both fingerprints as byte-identical to assembly immediately before freeze; 25 Evidence Records (14 reused from D1–D4 catalogues, 11 newly registered in D5 as EV-075–EV-085); no session use, examination, GF, or FD | FEF-FGR-002-EP-005-FR-001; FEF-FGR-002-EP-005-VR-001 |

## Non-Effects

This register contains five Frozen Evidence Packs. EP-005, like EP-004,
has no session use, examination, Governance Finding, or Founder Decision
linkage. Frozen-pack registration changes no source evidence, mapping,
Open Question, or cross-domain boundary and does not authorise
examination. Post-freeze change to any frozen pack, including EP-005,
requires a successor or Supplemental Pack and revalidation.
