# FEF-FGR-002 — Evidence Pack Register

| Control Field | Recorded Value |
|---|---|
| Register identifier | FEF-FGR-002-EPR-001 |
| Register class | Evidence Pack Register |
| Review identifier | FEF-FGR-002 |
| Register version | 1.31 |
| Lifecycle state | Active |
| Created date | 2026-07-24 |
| Controlling instruments | FEF-FGRC-001; FEF-FGRA-001; FEF-FGRP-001 |
| Applicable specification | [FEF-EPS-001](../FEF-EPS-001-EVIDENCE-PACK-SPECIFICATION.md) |
| Control owner | FEF-FGR-002-RA-005 — Evidence Custodian |
| Validator | FEF-FGR-002-RA-006 — Validator; non-independent combination disclosed |
| Access treatment | Repository-controlled governance record; pack-specific treatment required |
| Integrity control | Pack SHA-256 recorded in domain validation records; EP-003 records its Integrity Manifest in-pack; EP-004 pack, manifest, and freeze fingerprints are controlled by FEF-FGR-002-EP-004-FR-001 and reverified in FEF-FGR-002-EP-004-VR-001; EP-005 v1.0 whole-file and membership fingerprints remain historical and reliance-blocked; FR-002/VR-002 control successor v2.0 Frozen whole-file hashes `d4504f3b1983d5076054b479b565d6dc758edadb239603b86347c608d09b8ada` / `ce6e5b40cbe1c52cf263ccaddd97d0c8461a77d3a71402fbdc7aad60f337ac52` and membership fingerprint `c3a88eb9cbb2c8e4b38ee18cdc9c5f92a11087dcfd2ea66a32ea668766571a0f`; EP-006 v1.0 pack and manifest fingerprints are controlled by FEF-FGR-002-EP-006-FR-001 and reverified in FEF-FGR-002-EP-006-VR-001 |
| Last validation date | 2026-08-05 |
| Substantive entry count | 7 pack versions across six pack identities |

## Register

| Pack ID | Version | Domain | Related RQs | Manifest | Lifecycle State | Freeze Date | Session Use | Integrity Record | Access Treatment | Supersedes | Validation |
|---|---:|---|---|---|---|---|---|---|---|---|---|
| FEF-FGR-002-EP-001 | 1.0 | D1 — Governance Authority | RQ-001–RQ-008 | 21 Evidence Records | Frozen | 2026-07-24 | S01 — Closed | Source and pack hashes recorded | Repository-controlled | None | Pass with disclosed non-independent condition |
| FEF-FGR-002-EP-002 | 1.0 | D2 — Evidence Governance | RQ-009–RQ-015 | 21 Evidence Records | Frozen | 2026-07-25 | S02 — Closed; sole examination baseline | Source and pack hashes recorded in FEF-FGR-002-D2-EMVR-001 and reverified at entry and post-session validation | Repository-controlled | None | Pass with disclosed non-independent condition |
| FEF-FGR-002-EP-003 | 1.0 | D3 — Governance Assurance | RQ-016–RQ-024 | 39 Evidence Records (17 reused, 22 new) | Frozen | 2026-07-26 | S03 — Closed; sole examination baseline | SHA-256 digests recorded in the pack's own Integrity Manifest (§11); reused items carry forward D1/D2 integrity values | Repository-controlled | None | Pass with Conditions — non-independent; RQ-018 gap and EV-058/EV-059 contradictions disclosed |
| FEF-FGR-002-EP-004 | 1.0 | D4 — Records and Information Governance | RQ-025–RQ-031 | 19 Evidence Records; 65 source-to-RQ mappings; 72 source-to-requirement links | Frozen | 2026-07-28 | S04 — Closed; sole examination baseline | Pack and manifest SHA-256 recorded in FEF-FGR-002-EP-004-FR-001; source and frozen-artefact hashes reverified in FEF-FGR-002-EP-004-VR-001 | Repository-controlled | None | Pass with Conditions — non-independent; evidence gaps, EV-059 contradiction, EV-074 boundary, Open Questions, and D5/D6 interfaces preserved |
| FEF-FGR-002-EP-005 | 1.0 | D5 — Governance Lifecycle and Evolution | RQ-032–RQ-037 | 25 Evidence Records; 41 source-to-RQ mappings; 42 source-to-requirement links | Frozen — historical predecessor; reliance blocked | 2026-07-31 | None — no session use; reliance blocked | Historical pack/manifest SHA-256 controlled by FR-001/VR-001 v1.1; historical membership fingerprint `59414d0803ed114171c35a821d4581a80e8df92121260d868eaee4fd76e925fc` contains the defective EV-072 pair | Repository-controlled | None | Historical Pass with Conditions overtaken for session reliance by the DG-4 integrity discovery; v1.0 remains immutable |
| FEF-FGR-002-EP-005 | 2.0 | D5 — Governance Lifecycle and Evolution | RQ-032–RQ-037 | 25 Evidence Records; 41 source-to-RQ mappings; 42 source-to-requirement links; corrected EV-072 D5 acquisition pair | Frozen | 2026-07-31 | S05 — Closed — Examination Complete; Governance Findings Presented; sole examination baseline for Loops 001–006 | FR-002/VR-002: pack `d4504f3b1983d5076054b479b565d6dc758edadb239603b86347c608d09b8ada`; MAN-002 `ce6e5b40cbe1c52cf263ccaddd97d0c8461a77d3a71402fbdc7aad60f337ac52`; membership `c3a88eb9cbb2c8e4b38ee18cdc9c5f92a11087dcfd2ea66a32ea668766571a0f` | Repository-controlled | EP-005 v1.0 | Pass with Conditions — non-independent; all conditions remain binding |
| FEF-FGR-002-EP-006 | 1.0 | D6 — Framework Administration | RQ-038–RQ-043 | 13 Evidence Records; 22 source-to-RQ mappings | Frozen | 2026-08-05 | FEF-FGR-002-S06 — Closed — Examination Complete; Governance Findings Presented; sole baseline for all six Evidence Examination Loops | FR-001: pack `a97c3e367fb727771d9dd85794a6cfaaf766b4b013213c66210c76babad14bc4`; manifest `9db934232cd156237266ff63ac070966f45ac60e4544eb70e030e840a7735caf` | Repository-controlled | None | Pass with Conditions — non-independent; smallest domain corpus to date; Administrative Evidence Sufficiency Check 13/13 retained |

## D2 Output Linkage

EP-002 v1.0 is the sole frozen evidence baseline for S02, GF-009 through
GF-014, and FD-011 through FD-016. Exact relationships are controlled by the
[D2 Traceability Register](FEF-FGR-002-D2-TRACEABILITY-REGISTER.md). This
linkage does not modify or re-freeze EP-002.

## D3 Output Linkage

EP-003 v1.0 was the sole frozen examination baseline for S03. S03 is Closed;
GF-015 through GF-023 were examined, dispositioned, and linked one-to-one to
issued and validated FD-017 through FD-025. DG-5 and DG-6 are complete and D3
is Closed. These linkages do not modify or re-freeze EP-003.

## D4 Output Linkage

EP-004 v1.0 was the sole frozen examination baseline for S04. S04 is Closed;
GF-024 through GF-030 were examined and dispositioned Accept with Conditions,
and FD-026 through FD-032 were issued and validated. DG-5 and DG-6 are complete
and D4 is Closed. These linkages do not modify or re-freeze EP-004.

## D5 Output Linkage

EP-005 v1.0 remains byte-preserved and Frozen as the historical predecessor,
but the attempted DG-4 integrity check found its EV-072 provenance pair and
membership input defective. It is blocked from session reliance. Successor
v2.0 is Frozen with the corrected D5 acquisition pair and controlling
membership fingerprint under FR-002/VR-002. PFSERR-002 was accepted and DG-4
subsequently passed with conditions. Following Founder acceptance and the
validated opening action, S05 opened. S05 Evidence Examination Loops 001
through 006 used v2.0/MAN-002 as their sole baseline for RQ-032 through RQ-037
and produced Presented GF-031 through GF-036, each validated Pass with
Conditions. The validated Session Exit Gate closed S05 — Examination Complete;
Governance Findings Presented. No Founder Decision exists for D5.

## D6 Output Linkage

FEF-FGR-002-EP-006 v1.0 is Frozen as the D6 evidence baseline for RQ-038
through RQ-043. Session FEF-FGR-002-S06 is now Closed — Examination
Complete; Governance Findings Presented — and used EP-006 v1.0 as the
sole baseline for Evidence Examination Loop 001 (RQ-038 only,
producing Presented GF-037), Loop 002 (RQ-039 only, producing Presented
GF-038), Loop 003 (RQ-040 only, producing Presented GF-039), Loop 004
(RQ-041 only, producing Presented GF-040), Loop 005 (RQ-042 only,
producing Presented GF-041), and Loop 006 (RQ-043 only, producing
Presented GF-042). All six admitted D6 Review Questions are now Answered
at finding level. This linkage does not modify or re-freeze EP-006.

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
| 1.11 | 2026-07-31 | Records the attempted DG-4 integrity stop and EP-005 v1.0 reliance block; registers methodology-compliant successor v2.0 and MAN-002 as Validation Pending, Not Frozen, with corrected EV-072 D5 provenance and reconstructed candidate membership fingerprint; no revalidation, re-freeze, DG-4 verdict, S05, session, examination, GF, or FD | Founder authorisation; FEF-FGR-002-EP-005-PMCR-001 |
| 1.12 | 2026-07-31 | Records PMCVR-001 Pass with Conditions: successor v2.0 and MAN-002 remediation-validated against their submitted construction hashes, corrected EV-072 provenance, canonical membership fingerprint, and preserved 25/41/42/24 corpus; still Not Frozen and unusable pending separately authorised DG-3 | Founder remediation-revalidation authorisation; FEF-FGR-002-EP-005-PMCVR-001 |
| 1.13 | 2026-07-31 | Registers DG-3 successor re-freeze: EP-005 v2.0 and MAN-002 Frozen under FR-002/VR-002 with new controlling whole-file hashes and corrected controlling membership fingerprint; construction hashes and v1.0 controls retained historically; no DG-4, S05, session, examination, RQ answer, GF, FD, D5 closure, or D6/D7 commencement | Founder DG-3 authorisation; FEF-FGR-002-EP-005-FR-002; FEF-FGR-002-EP-005-VR-002 |
| 1.14 | 2026-07-31 | Records PFSERR-002 Ready for DG-4 with Conditions for frozen successor v2.0/MAN-002; no session use is authorised; pack identity, fingerprints, corpus, evidence treatment, and v1.0 historical/reliance-blocked state unchanged | Founder bounded post-freeze readiness authority; FEF-FGR-002-D5-PFSERR-002 |
| 1.15 | 2026-07-31 | Links frozen EP-005 v2.0/MAN-002 as the sole permitted future examination baseline for S05 following DG-4 Pass with Conditions; S05 remains Prepared — Not Opened; v1.0 remains historical/reliance-blocked; no evidence change, opening, examination, RQ answer, GF, FD, or D6/D7 commencement | FEF-FGR-002-S05-ER-001; FEF-FGR-002-S05-EVR-001 |
| 1.16 | 2026-07-31 | Corrects stale current EP-003/S03/D3 and EP-004/S04/D4 session/output linkages and v1.0 no-use wording; records S05 Open — Evidence Examination Not Yet Started with frozen v2.0/MAN-002 as its sole baseline; no evidence, examination, RQ answer, GF, FD, D5 closure, or D6/D7 change | Founder pre-opening correction/opening authority; FEF-FGR-002-S05-OR-001; FEF-FGR-002-S05-OVR-001 |
| 1.17 | 2026-07-31 | Records use of frozen EP-005 v2.0/MAN-002 as the sole baseline for S05 Evidence Examination Loop 001 — RQ-032 Only; exact nine-record mapping and all qualifications retained; GF-031 Presented/Pending after Pass with Conditions validation; RQ-033 through RQ-037 unexamined; no pack, membership, treatment, FD, closure, or D6/D7 change | FEF-FGR-002-S05-RQ-032-ER-001; FEF-FGR-002-S05-GF-031-VR-001 |
| 1.18 | 2026-08-01 | Records use of frozen EP-005 v2.0/MAN-002 as the sole baseline for S05 Evidence Examination Loop 002 — RQ-033 Only; exact eight-record mapping and all qualifications retained; GF-031 unchanged and GF-032 Presented/Pending after Pass with Conditions validation; RQ-034 through RQ-037 unexamined; no pack, membership, treatment, FD, closure, or D6/D7 change | FEF-FGR-002-S05-RQ-033-ER-001; FEF-FGR-002-S05-GF-032-VR-001 |
| 1.19 | 2026-08-01 | Records use of frozen EP-005 v2.0/MAN-002 as the sole baseline for S05 Evidence Examination Loop 003 — RQ-034 Only; exact six-record historical-acquisition mapping and all qualifications retained; GF-031/GF-032 unchanged and GF-033 Presented/Pending after Pass with Conditions validation; RQ-035 through RQ-037 unexamined; no pack, membership, treatment, FD, closure, or D6/D7 change | FEF-FGR-002-S05-RQ-034-ER-001; FEF-FGR-002-S05-GF-033-VR-001 |
| 1.20 | 2026-08-01 | Records use of frozen EP-005 v2.0/MAN-002 as the sole baseline for S05 Evidence Examination Loop 004 — RQ-035 Only; exact six-record mapping, gate-time source currency, and all qualifications retained; GF-031–GF-033 unchanged and GF-034 Presented/Pending after Pass with Conditions validation; RQ-036/RQ-037 unexamined; no pack, membership, treatment, FD, closure, or D6/D7 change | FEF-FGR-002-S05-RQ-035-ER-001; FEF-FGR-002-S05-GF-034-VR-001 |
| 1.21 | 2026-08-01 | Records use of frozen EP-005 v2.0/MAN-002 as the sole baseline for S05 Evidence Examination Loop 005 — RQ-036 Only; exact six-record mapping, gate-time source currency, and all qualifications retained; GF-031–GF-034 unchanged and GF-035 Presented/Pending after Pass with Conditions validation; RQ-037 unexamined; no pack, membership, treatment, exception, FD, closure, or D6/D7 change | FEF-FGR-002-S05-RQ-036-ER-001; FEF-FGR-002-S05-GF-035-VR-001 |
| 1.22 | 2026-08-01 | Records use of frozen EP-005 v2.0/MAN-002 as the sole baseline for S05 Evidence Examination Loop 006 — RQ-037 Only; exact six-record historical-acquisition mapping, gate-time source currency, Context Only status, OQ-013/OQ-016, and all qualifications retained; GF-031–GF-035 unchanged and GF-036 Presented/Pending after Pass with Conditions validation; no legacy authority/validity determination, retrospective validation/invalidation, taxonomy, inventory, migration, pack, membership, treatment, FD, closure, or D6/D7 change | FEF-FGR-002-S05-RQ-037-ER-001; FEF-FGR-002-S05-GF-036-VR-001 |
| 1.23 | 2026-08-01 | Records S05 Session Exit Pass with Conditions after all six exact FEF-FGRP-001 §12.1 criteria passed; v2.0/MAN-002 remained the sole baseline across all six loops and all frozen/acquisition controls reproduced; S05 Closed — Examination Complete; Governance Findings Presented; no pack, fingerprint, membership, treatment, Open Question, finding disposition, FD, D5 closure, or D6/D7 change | FEF-FGR-002-S05-SER-001; FEF-FGR-002-S05-SEVR-001 |
| 1.24 | 2026-08-05 | D6 Evidence Pack EP-006 v1.0 registered as **Frozen** following DG-3 (Pass with Conditions); 13 Evidence Records (9 reused/reobserved, 4 newly registered EV-086–EV-089), 22 source-to-RQ mappings across all six admitted D6 RQs (RQ-038–RQ-043); smallest domain corpus to date; Founder-directed Administrative Evidence Sufficiency Check performed twice (pre-freeze and at freeze), 13/13 retained both times, zero removed; no session use, examination, GF, or FD | FEF-FGR-002-EP-006-FR-001; FEF-FGR-002-EP-006-VR-001 |
| 1.25 | 2026-08-05 | Records use of frozen EP-006 v1.0 as the sole baseline for S06 Evidence Examination Loop 001 — RQ-038 Only; exact eight-record mapping and all qualifications retained; GF-037 Presented/Pending after Pass with Conditions validation; RQ-039 through RQ-043 unexamined; no pack, membership, treatment, FD, closure, or D7 change | FEF-FGR-002-S06-RQ-038-ER-001; FEF-FGR-002-S06-GF-037-VR-001 |
| 1.26 | 2026-08-05 | Records use of frozen EP-006 v1.0 as the sole baseline for S06 Evidence Examination Loop 002 — RQ-039 Only; exact two-record mapping (EV-080, EV-087 version-pinned to pre-freeze v1.76) and all qualifications retained; GF-038 Presented/Pending after Pass with Conditions validation; RQ-040 through RQ-043 unexamined; no pack, membership, treatment, FD, closure, or D7 change | FEF-FGR-002-S06-RQ-039-ER-001; FEF-FGR-002-S06-GF-038-VR-001 |
| 1.27 | 2026-08-05 | Records use of frozen EP-006 v1.0 as the sole baseline for S06 Evidence Examination Loop 003 — RQ-040 Only; exact two-record mapping (EV-080, EV-088) and all qualifications retained; GF-039 Presented/Pending after Pass with Conditions validation; FEF-P0-004 disposition not decided; RQ-041 through RQ-043 unexamined; no pack, membership, treatment, FD, closure, or D7 change | FEF-FGR-002-S06-RQ-040-ER-001; FEF-FGR-002-S06-GF-039-VR-001 |
| 1.28 | 2026-08-05 | Records use of frozen EP-006 v1.0 as the sole baseline for S06 Evidence Examination Loop 004 — RQ-041 Only; exact four-record mapping (EV-072, EV-081, EV-087, EV-088; EV-072/EV-081/EV-087 version-pinned to their pre-freeze states) and all qualifications retained; GF-040 Presented/Pending after Pass with Conditions validation; OQ-015 not decided; RQ-042 and RQ-043 unexamined; no pack, membership, treatment, FD, closure, or D7 change | FEF-FGR-002-S06-RQ-041-ER-001; FEF-FGR-002-S06-GF-040-VR-001 |
| 1.29 | 2026-08-06 | Records use of frozen EP-006 v1.0 as the sole baseline for S06 Evidence Examination Loop 005 — RQ-042 Only; exact two-record mapping (EV-006, EV-086; EV-086 version-pinned to its frozen post-D6-DG-2 state) and all qualifications retained; GF-041 Presented/Pending after Pass with Conditions validation; RQ-043 unexamined; no pack, membership, treatment, FD, closure, or D7 change | FEF-FGR-002-S06-RQ-042-ER-001; FEF-FGR-002-S06-GF-041-VR-001 |
| 1.30 | 2026-08-06 | Records use of frozen EP-006 v1.0 as the sole baseline for S06 Evidence Examination Loop 006 — RQ-043 Only (final D6 examination loop); exact four-record mapping (EV-080, EV-086, EV-087, EV-089; EV-080/EV-086/EV-087 version-pinned to their frozen states) and all qualifications retained; GF-042 Presented/Pending after Pass with Conditions validation; all six admitted D6 RQs now Answered at finding level; no pack, membership, treatment, FD, closure, or D7 change | FEF-FGR-002-S06-RQ-043-ER-001; FEF-FGR-002-S06-GF-042-VR-001 |
| 1.31 | 2026-08-06 | Records S06 Session Exit (FEF-FGRP-001 §12.1), validated Pass with Conditions; EP-006's Session Use field corrected from a stale "Unassigned" value to record FEF-FGR-002-S06 as Closed — Examination Complete; Governance Findings Presented, the sole baseline used across all six Evidence Examination Loops; pack and manifest fingerprints reproduced byte-identical to freeze; no pack, membership, treatment, qualification, mapping, FD, or D7 change | FEF-FGR-002-S06-SER-001; FEF-FGR-002-S06-SEVR-001 |

## Non-Effects

This register contains six pack identities and seven registered versions.
EP-005 v1.0 remains Frozen but blocked from reliance; v2.0 is Frozen under
FR-002/VR-002 and linked as the sole baseline for S05. S05 is Closed after
Loops 001 through 006 and the validated Session Exit Gate; RQ-032 through
RQ-037 are linked to Presented GF-031 through GF-036. No Founder Decision
exists. The successor changes no source evidence,
mapping, Open Question, or cross-domain boundary and does not itself authorise
opening or examination. EP-006 v1.0 is Frozen (DG-3) as the D6 evidence
baseline for RQ-038 through RQ-043; no session use, no examination, no
Governance Finding, and no Founder Decision exists for D6.
