# FEF-FGR-002-EP-004-MAN-001 — EP-004 Evidence Pack Manifest

| Control Field | Recorded Value |
|---|---|
| Manifest identifier | FEF-FGR-002-EP-004-MAN-001 |
| Pack identifier | FEF-FGR-002-EP-004 |
| Pack version | 1.0 |
| Domain | D4 — Records and Information Governance |
| State | **Frozen** |
| Freeze date | 2026-07-28 |
| Input repository baseline | `ff601b91a89c6ff05672e19eab2387d96e5a4d14` |
| Evidence Register input | FEF-FGR-002-EVIDENCE-REGISTER.md v1.13 |
| D4 RQ Set input | FEF-FGR-002-D4-REVIEW-QUESTION-SET.md v1.8 |
| Review Question Register input | FEF-FGR-002-REVIEW-QUESTION-REGISTER.md v1.31 |
| Corpus | 19 Evidence Records; 65 source-to-RQ mappings; 72 source-to-requirement links |
| Hash algorithm | SHA-256 |
| Access treatment | Repository |

## Input Control Baseline

The assembly inputs are fixed to the exact files at repository baseline
`ff601b91a89c6ff05672e19eab2387d96e5a4d14`:

| Input | Version / State | SHA-256 at Input Baseline |
|---|---|---|
| `FEF-FGR-002-EVIDENCE-REGISTER.md` | v1.13 | `0c8ec1c89a8e5ca8a8d13a793d7b824ba8b906a009c7e03ecda5ba7f9ba812d0` |
| `FEF-FGR-002-D4-REVIEW-QUESTION-SET.md` | v1.8 | `279c4498461f64150925215c289e470922398d59a6b2d073b2e6d8e1bd1a370f` |
| `FEF-FGR-002-REVIEW-QUESTION-REGISTER.md` | v1.31 | `ed5c9b3cb879030da9085cc6bed952e8d9043421abe3c6ebb0f2ebe26831b482` |
| `FEF-FGR-002-D4-EVIDENCE-MOBILISATION-COMPLETION-REVIEW.md` | Complete — Pack Preparation Ready with Conditions | `0994c8fed0302a5bffc5ef1eef06d749e64ea7dd10352749f0fab70558720154` |
| `FEF-FGR-002-D4-EVIDENCE-PACK-READINESS-VALIDATION-REPORT.md` | Pass with Conditions | `feb11b2112571cbbbf5232f861967b06fdbf5de560c23978bcdc8314333511ee` |

The later evidence-status synchronization does not change this captured
assembly-input baseline.

## 1. Exact Evidence Membership

| Evidence | Title | Controlled Path | Provenance Commit | SHA-256 | Class | Admissibility | D4 RQs |
|---|---|---|---|---|---|---|---|
| EV-005 | FEF-FGRC-001 Founder Governance Review Charter | `docs/governance/reviews/FEF-FGRC-001-FOUNDER-GOVERNANCE-REVIEW-CHARTER.md` | `0407110759ab74da308b4de3a8daf27fa10c8d5d` | `e007510ba3eb3a115177522c041bb91284f5f0efe3fdd3f185c7565c09c52d72` | E2 | Admitted | RQ-025, RQ-026, RQ-027, RQ-028, RQ-029, RQ-030, RQ-031 |
| EV-007 | FEF-FGRP-001 Founder Governance Review Plan | `docs/governance/reviews/FEF-FGRP-001-FOUNDER-GOVERNANCE-REVIEW-PLAN.md` | `0407110759ab74da308b4de3a8daf27fa10c8d5d` | `eb1e59544a32888bc3b20b5f87a0bb5342f350539946782196d5a31757ba6568` | E2 | Admitted | RQ-025, RQ-027, RQ-028, RQ-029 |
| EV-008 | FEF-FGRER-001 Review Execution Rules | `docs/governance/reviews/FEF-FGRER-001-REVIEW-EXECUTION-RULES.md` | `0407110759ab74da308b4de3a8daf27fa10c8d5d` | `625cbd574e8354fc8ed6191b4c87cdce9d66d781ebfe1f43c3ac0b31e643a35f` | E2 | Admitted | RQ-025, RQ-026, RQ-027, RQ-028, RQ-029, RQ-030, RQ-031 |
| EV-012 | Open Questions Register | `docs/records/work-packages/FEF-WPK-001/FEF-WPK-001-OPEN-QUESTIONS-REGISTER.md` | `e5199eb18567799e30ef57a3546da6690b74a0c0` | `c14ff1a7508af23259f498b6d0a5305f9f3f7bde94892e933b7d526ee20f6be5` | E2 | Admitted | RQ-027, RQ-028, RQ-029, RQ-030, RQ-031 |
| EV-013 | FEF-RGS-000 Research Governance Standard | `docs/governance/research/FEF-RGS-000-RESEARCH-GOVERNANCE-STANDARD.md` | `e5199eb18567799e30ef57a3546da6690b74a0c0` | `ed20b516270839d8ce24561548de0c345a9fb28e7cc76312aa9e4e65e8f3d56b` | E2 | Conditionally Admitted | RQ-025, RQ-027, RQ-028, RQ-029, RQ-030, RQ-031 |
| EV-016 | Operational Governance Roles | `docs/governance/reviews/FEF-FGR-002/FEF-FGR-002-OGRS-001-OPERATIONAL-GOVERNANCE-ROLES.md` | `40f776057c2ac84f8db79d2657ecd40bc4ab1e42` | `252b85ac40628fb4d8d8a88da876d3ce81ccbc6a48186f26db936786daf80b26` | E2 | Admitted | RQ-026, RQ-027, RQ-028, RQ-030 |
| EV-017 | Operational Authority Boundary | `docs/governance/reviews/FEF-FGR-002/FEF-FGR-002-OAB-001-OPERATIONAL-AUTHORITY-BOUNDARY.md` | `40f776057c2ac84f8db79d2657ecd40bc4ab1e42` | `415f61a8fa11fb2792e1d87c4b0f4a10c60ad242c82b69aefbfdebb17b3b94e6` | E2 | Admitted | RQ-026 |
| EV-019 | Governance Responsibility Matrix | `docs/governance/reviews/FEF-FGR-002/FEF-FGR-002-GRM-001-GOVERNANCE-RESPONSIBILITY-MATRIX.md` | `40f776057c2ac84f8db79d2657ecd40bc4ab1e42` | `b42d6d5117f89d5d84416ffe769c4367bb9af3db5661a3a953d832840eb08747` | E2 | Admitted | RQ-026 |
| EV-020 | Role Assignment Procedure | `docs/governance/reviews/FEF-FGR-002/FEF-FGR-002-RAP-001-ROLE-ASSIGNMENT-PROCEDURE.md` | `40f776057c2ac84f8db79d2657ecd40bc4ab1e42` | `905ba3dd91c3c6d443817edcbcb51761715420f9e12e0f757641d73da050d661` | E2 | Admitted | RQ-026, RQ-030 |
| EV-021 | Role Assignment Register | `docs/governance/reviews/FEF-FGR-002/FEF-FGR-002-RAR-001-ROLE-ASSIGNMENT-REGISTER.md` | `40f776057c2ac84f8db79d2657ecd40bc4ab1e42` | `9b4d857be97af6c5df0f4f8a61e0bf6088974064d44218c35f36033d0e2b13b5` | E2 | Admitted | RQ-026, RQ-030 |
| EV-023 | FEF-EPS-001 Evidence Pack Specification | `docs/governance/reviews/FEF-EPS-001-EVIDENCE-PACK-SPECIFICATION.md` | `0407110759ab74da308b4de3a8daf27fa10c8d5d` | `e70762664e0672f44cfdf1b7e99ea82a2ed249699900d54fad07a9a0f05e63fd` | E2 | Conditionally Admitted | RQ-027, RQ-028, RQ-029, RQ-031 |
| EV-059 | D3 Admission-Readiness Checkpoint (corrected) | `docs/governance/reviews/FEF-FGR-002/FEF-FGR-002-D3-C1-GOVERNANCE-ASSURANCE-STAGE-CLOSURE-AND-E1-READINESS-ASSESSMENT.md` | `38ff850080b113595e16059eb13a58a4a55f3f9a` | `1630eb575de4716b7a97061f780478a4851cbdf2ec77fe04376094868f054263` | E2 / E4 | Admitted — contradiction preserved | RQ-026, RQ-031 |
| EV-066 | FD-011 — Evidence Qualification and Permitted Reliance | `docs/governance/reviews/FEF-FGR-002/FEF-FGR-002-FD-011-EVIDENCE-QUALIFICATION-AND-PERMITTED-RELIANCE.md` | `9b0f23e89f4aca3eeb6d4fa794e902337446f7f3` | `1e3eb7286f6a07a38ee1c3bf4259bea0a755c64dd133ddd65204b788bfdee7f4` | E1 | Admitted | RQ-028, RQ-029 |
| EV-069 | FD-014 — Frozen Evidence Baselines and Change Control | `docs/governance/reviews/FEF-FGR-002/FEF-FGR-002-FD-014-FROZEN-EVIDENCE-BASELINES-AND-CHANGE-CONTROL.md` | `9b0f23e89f4aca3eeb6d4fa794e902337446f7f3` | `f0964bc93bb73530d4b85bf633d6e2e8217a19318b1c652327ff7e93496d63b1` | E1 | Admitted | RQ-027, RQ-029, RQ-031 |
| EV-070 | FD-015 — Evidence Traceability and Controlled Reuse | `docs/governance/reviews/FEF-FGR-002/FEF-FGR-002-FD-015-EVIDENCE-TRACEABILITY-AND-CONTROLLED-REUSE.md` | `9b0f23e89f4aca3eeb6d4fa794e902337446f7f3` | `7970e6e159cbf2de454c986d44af830fab65ef915066dc9b5b746d04e55bae16` | E1 | Admitted | RQ-030, RQ-031 |
| EV-071 | FD-016 — Evidence Custody and Authority Boundary | `docs/governance/reviews/FEF-FGR-002/FEF-FGR-002-FD-016-EVIDENCE-CUSTODY-AND-AUTHORITY-BOUNDARY.md` | `9b0f23e89f4aca3eeb6d4fa794e902337446f7f3` | `53e25bf979a74b330b2ff5130f2455d94bddc77a8dd61a3e61e4a29ae9a16dd0` | E1 | Admitted | RQ-026, RQ-027, RQ-028, RQ-029, RQ-030, RQ-031 |
| EV-072 | FEF Document Manifest | `docs/programme/FEF-DOCUMENT-MANIFEST.md` | `533b694d75db4a3377edc7a6dccf5ec2b41ebbd5` | `31807d1de36002ebf359348bea764f8711476405de5c08669f0586c48853502d` | E2 | Conditionally Admitted | RQ-025 |
| EV-073 | D3 Governance Assurance Traceability Register | `docs/governance/reviews/FEF-FGR-002/FEF-FGR-002-D3-TRACEABILITY-REGISTER.md` | `e3af7b55955b28febd6e504eaddb014d56a0c5a5` | `5e98e29ffda20ac4fb87d50b0eeea5abb45e2963e570a08a0e9c2627465f8b30` | E4 | Admitted | RQ-025, RQ-026, RQ-030, RQ-031 |
| EV-074 | Phase 2 Founder Decision Record | `docs/governance/reviews/FEF-FGR-002/FEF-FGR-002-PHASE-2-FOUNDER-DECISION-RECORD.md` | `e610d7924893b1220fa261f7b3ee2c7523354895` | `c2755fa642c6ae0854a618aa0cc0e85f237bd60f91982125aa7415d1688e3aa5` | E1 | Admitted | RQ-030, RQ-031 |

## 2. Exact Source-to-Requirement Map

| Requirement | RQ | Evidence |
|---|---|---|
| D4-RQ025-EVR-001 | RQ-025 | EV-005, EV-007, EV-008 |
| D4-RQ025-EVR-002 | RQ-025 | EV-072, EV-073 |
| D4-RQ025-EVR-003 | RQ-025 | EV-013; explicit gap retained |
| D4-RQ026-EVR-001 | RQ-026 | EV-005, EV-016, EV-017, EV-019, EV-071 |
| D4-RQ026-EVR-002 | RQ-026 | EV-008, EV-020, EV-021 |
| D4-RQ026-EVR-003 | RQ-026 | EV-059, EV-073 |
| D4-RQ027-EVR-001 | RQ-027 | EV-005, EV-012, EV-071 |
| D4-RQ027-EVR-002 | RQ-027 | EV-008, EV-016, EV-023, EV-069 |
| D4-RQ027-EVR-003 | RQ-027 | EV-007, EV-013, EV-069 |
| D4-RQ028-EVR-001 | RQ-028 | EV-005, EV-008, EV-012, EV-066 |
| D4-RQ028-EVR-002 | RQ-028 | EV-013, EV-023, EV-066, EV-071 |
| D4-RQ028-EVR-003 | RQ-028 | EV-007, EV-016, EV-023, EV-071 |
| D4-RQ029-EVR-001 | RQ-029 | EV-005, EV-069, EV-071 |
| D4-RQ029-EVR-002 | RQ-029 | EV-007, EV-008, EV-012, EV-013, EV-066 |
| D4-RQ029-EVR-003 | RQ-029 | EV-005, EV-023, EV-069 |
| D4-RQ030-EVR-001 | RQ-030 | EV-005, EV-008, EV-070, EV-073 |
| D4-RQ030-EVR-002 | RQ-030 | EV-016, EV-020, EV-021, EV-071 |
| D4-RQ030-EVR-003 | RQ-030 | EV-012, EV-013, EV-074 |
| D4-RQ031-EVR-001 | RQ-031 | EV-005, EV-008, EV-059, EV-069 |
| D4-RQ031-EVR-002 | RQ-031 | EV-023, EV-069, EV-071 |
| D4-RQ031-EVR-003 | RQ-031 | EV-012, EV-013, EV-070, EV-073, EV-074 |

The 21 requirement rows contain 72 source-to-requirement links. Controlled
reuse across the seven RQs produces 65 source-to-RQ mappings and 19 unique
Evidence Records. No mapping is added, removed, combined, or inferred.

## 3. Mobilisation Control Linkage

| RQ | Mobilisation Record | Validation Report | Verdict |
|---|---|---|---|
| RQ-025 | [FEF-FGR-002-D4-RQ025-EMQR-001](FEF-FGR-002-D4-RQ-025-EVIDENCE-MOBILISATION-AND-QUALIFICATION-RECORD.md) | [FEF-FGR-002-D4-RQ025-EMVR-001](FEF-FGR-002-D4-RQ-025-EVIDENCE-MOBILISATION-VALIDATION-REPORT.md) | Pass with Conditions |
| RQ-026 | [FEF-FGR-002-D4-RQ026-EMQR-001](FEF-FGR-002-D4-RQ-026-EVIDENCE-MOBILISATION-AND-QUALIFICATION-RECORD.md) | [FEF-FGR-002-D4-RQ026-EMVR-001](FEF-FGR-002-D4-RQ-026-EVIDENCE-MOBILISATION-VALIDATION-REPORT.md) | Pass with Conditions |
| RQ-027 | [FEF-FGR-002-D4-RQ027-EMQR-001](FEF-FGR-002-D4-RQ-027-EVIDENCE-MOBILISATION-AND-QUALIFICATION-RECORD.md) | [FEF-FGR-002-D4-RQ027-EMVR-001](FEF-FGR-002-D4-RQ-027-EVIDENCE-MOBILISATION-VALIDATION-REPORT.md) | Pass with Conditions |
| RQ-028 | [FEF-FGR-002-D4-RQ028-EMQR-001](FEF-FGR-002-D4-RQ-028-EVIDENCE-MOBILISATION-AND-QUALIFICATION-RECORD.md) | [FEF-FGR-002-D4-RQ028-EMVR-001](FEF-FGR-002-D4-RQ-028-EVIDENCE-MOBILISATION-VALIDATION-REPORT.md) | Pass with Conditions |
| RQ-029 | [FEF-FGR-002-D4-RQ029-EMQR-001](FEF-FGR-002-D4-RQ-029-EVIDENCE-MOBILISATION-AND-QUALIFICATION-RECORD.md) | [FEF-FGR-002-D4-RQ029-EMVR-001](FEF-FGR-002-D4-RQ-029-EVIDENCE-MOBILISATION-VALIDATION-REPORT.md) | Pass with Conditions |
| RQ-030 | [FEF-FGR-002-D4-RQ030-EMQR-001](FEF-FGR-002-D4-RQ-030-EVIDENCE-MOBILISATION-AND-QUALIFICATION-RECORD.md) | [FEF-FGR-002-D4-RQ030-EMVR-001](FEF-FGR-002-D4-RQ-030-EVIDENCE-MOBILISATION-VALIDATION-REPORT.md) | Pass with Conditions |
| RQ-031 | [FEF-FGR-002-D4-RQ031-EMQR-001](FEF-FGR-002-D4-RQ-031-EVIDENCE-MOBILISATION-AND-QUALIFICATION-RECORD.md) | [FEF-FGR-002-D4-RQ031-EMVR-001](FEF-FGR-002-D4-RQ-031-EVIDENCE-MOBILISATION-VALIDATION-REPORT.md) | Pass with Conditions |

FEF-FGR-002-D4-EMCR-001 and FEF-FGR-002-D4-EPRVR-001 reconcile the
cumulative corpus and control the 19-record / 65-mapping / 72-link baseline.

## 4. Authority, Limitation, and Permitted-Use Controls

| Evidence | Preserved Boundary |
|---|---|
| EV-005 | Founder-approved Charter scope only |
| EV-007 | Founder-approved Plan scope only |
| EV-008 | Review execution-rule scope only |
| EV-012 | Open-question evidence only; records questions, not answers |
| EV-013 | Non-authoritative research draft; research-specific proposals only |
| EV-016 | Review-operational roles only |
| EV-017 | Review-operational authority boundary only |
| EV-019 | Review-operational responsibility matrix only |
| EV-020 | Review assignment and handover procedure only; no operated handover |
| EV-021 | Assignment snapshot; combined capacities disclosed; not a continuity test |
| EV-023 | Evidence Pack preparation baseline only; retained draft header; not a general lifecycle standard |
| EV-059 | One corrected D3 record; v1.0/v1.1 contradiction and single-case limitation retained |
| EV-066 | Exact permitted-reliance decision boundary; no external/restricted evidence policy supplied |
| EV-069 | Immutable Evidence Pack baseline boundary; detailed D5 mechanics remain provisional |
| EV-070 | Exact traceability and controlled-reuse boundary; no complete lifecycle model |
| EV-071 | Exact evidence-custody and authority boundary; no broader information-lifecycle inference |
| EV-072 | Mutable, non-authoritative programme index; source records control |
| EV-073 | One operated D3 traceability example; not current programme state or a general model |
| EV-074 | Prospective Framework Evolution and non-retrospective treatment only; no FEF-CCF-001 content |

The exact RQ-specific limitations, gaps, conflict treatments, uncertainties,
and permitted uses in Sections 6–10 of each linked mobilisation record remain
part of this manifest by controlled reference and may not be compressed away
during examination.

## 5. Open Question and Dependency Preservation

| RQ | Preserved Open Question Mapping |
|---|---|
| RQ-025 | OQ-023 partial |
| RQ-026 | OQ-002 partial; OQ-021 partial; OQ-023 direct |
| RQ-027 | OQ-011 direct |
| RQ-028 | OQ-010 direct |
| RQ-029 | OQ-011 direct; OQ-012 partial |
| RQ-030 | OQ-021 partial; OQ-023 partial |
| RQ-031 | OQ-021 direct; OQ-022 partial |

All mappings preserve the Open Questions unchanged and open. D5 and D6
remain separately governed, unresolved, and not reached. FEF-CCF-001 remains
a future Framework Evolution candidate only.

## 6. Manifest Closure

This manifest is closed at EP-004 v1.0 freeze. No item, requirement,
mapping, digest, provenance value, class, admissibility state, limitation,
permitted use, Open Question mapping, or dependency boundary may be changed
inside this frozen version. Change requires a governed successor or
supplemental pack and revalidation.
