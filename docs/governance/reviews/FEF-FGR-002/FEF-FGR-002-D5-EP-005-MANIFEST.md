# FEF-FGR-002-EP-005-MAN-001 — EP-005 Evidence Pack Manifest

| Control Field | Recorded Value |
|---|---|
| Manifest identifier | FEF-FGR-002-EP-005-MAN-001 |
| Pack identifier | FEF-FGR-002-EP-005 |
| Pack version | 1.0 |
| Domain | D5 — Governance Lifecycle and Evolution |
| State | **Frozen** |
| Assembly date | 2026-07-30 |
| Freeze date | 2026-07-31 |
| Input repository baseline | `f04c29d98f24a7c38a38b52b36a1fe43aded431d` |
| Evidence Register input | FEF-FGR-002-EVIDENCE-REGISTER.md v1.19 |
| D5 Review Question Set input | FEF-FGR-002-D5-REVIEW-QUESTION-SET.md v1.6 |
| Review Question Register input | FEF-FGR-002-REVIEW-QUESTION-REGISTER.md v1.50 |
| Corpus | 25 Evidence Records; 41 source-to-RQ mappings; 42 source-to-requirement links |
| Hash algorithm | SHA-256 |
| Access treatment | Repository |

## Input Control Baseline

The assembly inputs are fixed to the exact files at repository baseline `f04c29d98f24a7c38a38b52b36a1fe43aded431d`:

| Input | Version / State | SHA-256 at Input Baseline |
|---|---|---|
| `FEF-FGR-002-EVIDENCE-REGISTER.md` | v1.19 | not independently re-derived here; controlled by its own change history |
| `FEF-FGR-002-D5-REVIEW-QUESTION-SET.md` | v1.6 | not independently re-derived here; controlled by its own change history |
| `FEF-FGR-002-REVIEW-QUESTION-REGISTER.md` | v1.50 | not independently re-derived here; controlled by its own change history |
| `FEF-FGR-002-D5-EVIDENCE-MOBILISATION-COMPLETION-REVIEW.md` | v1.1 — Complete — Pack Preparation Ready with Conditions — corrected | not independently re-derived here; controlled by its own change history |
| `FEF-FGR-002-D5-EVIDENCE-PACK-READINESS-VALIDATION-REPORT.md` | v1.1 — Pass with Conditions — corrected | not independently re-derived here; controlled by its own change history |
| `FEF-FGR-002-D5-POST-COMPLETION-ADMINISTRATIVE-RECONCILIATION-RECORD.md` | v1.0 — Pass with Conditions | not independently re-derived here; controlled by its own change history |
| `FEF-FGR-002-D5-POST-COMPLETION-ADMINISTRATIVE-RECONCILIATION-VALIDATION-REPORT.md` | v1.0 — Pass with Conditions | not independently re-derived here; controlled by its own change history |

The later evidence-status synchronization (Section 12 register updates accompanying this assembly) does not change this captured assembly-input baseline.

## 1. Exact Evidence Membership

Ordered numerically by Evidence Record identifier, per Section 14's deterministic ordering method.

| Evidence | Title | Controlled Path | Provenance Commit (first D5 acquisition) | SHA-256 (first / primary D5 acquisition) | Class | Admissibility | D5 RQs |
|---|---|---|---|---|---|---|---|
| EV-005 | FEF-FGRC-001 Founder Governance Review Charter | `docs/governance/reviews/FEF-FGRC-001-FOUNDER-GOVERNANCE-REVIEW-CHARTER.md` | `bb47b0bc514f9f147b37b7131720cbca5590f800` | `e007510ba3eb3a115177522c041bb91284f5f0efe3fdd3f185c7565c09c52d72` | E2 | Admitted | RQ-032, RQ-035, RQ-036 |
| EV-007 | FEF-FGRP-001 Founder Governance Review Plan | `docs/governance/reviews/FEF-FGRP-001-FOUNDER-GOVERNANCE-REVIEW-PLAN.md` | `bb47b0bc514f9f147b37b7131720cbca5590f800` | `eb1e59544a32888bc3b20b5f87a0bb5342f350539946782196d5a31757ba6568` | E2 | Admitted | RQ-032 |
| EV-008 | FEF-FGRER-001 Review Execution Rules | `docs/governance/reviews/FEF-FGRER-001-REVIEW-EXECUTION-RULES.md` | `bb47b0bc514f9f147b37b7131720cbca5590f800` | `625cbd574e8354fc8ed6191b4c87cdce9d66d781ebfe1f43c3ac0b31e643a35f` | E2 | Admitted | RQ-032 |
| EV-009 | FEF-FAR-001 Founder Architectural Review | `docs/records/founder-reviews/FEF-FAR-001-FOUNDER-ARCHITECTURAL-REVIEW.md` | `3953aa75e98f24a093a68b200d75314a5a19951f` | `ab32f0527d7c99c7562c2c959e1426c10d6dd81a9fa4d2518c9c3059fff3a237` | E2 | Admitted | RQ-033 |
| EV-010 | FEF-FAR-002 Programme Governance Pilot | `docs/records/founder-reviews/FEF-FAR-002-PROGRAMME-GOVERNANCE-PILOT.md` | `3953aa75e98f24a093a68b200d75314a5a19951f` | `41f5b4eb4c3d553ea1e6b3c1566153541ecc74ad3468f7dfe281f3e354165bf3` | E2 | Admitted | RQ-033 |
| EV-012 | FEF-WPK-001 Open Questions Register | `docs/records/work-packages/FEF-WPK-001/FEF-WPK-001-OPEN-QUESTIONS-REGISTER.md` | `3953aa75e98f24a093a68b200d75314a5a19951f` | `c14ff1a7508af23259f498b6d0a5305f9f3f7bde94892e933b7d526ee20f6be5` | E2 | Admitted | RQ-033, RQ-034, RQ-036, RQ-037 |
| EV-013 | FEF-RGS-000 Research Governance Standard | `docs/governance/research/FEF-RGS-000-RESEARCH-GOVERNANCE-STANDARD.md` | `bb47b0bc514f9f147b37b7131720cbca5590f800` | `ed20b516270839d8ce24561548de0c345a9fb28e7cc76312aa9e4e65e8f3d56b` | E2 | Conditionally Admitted | RQ-032, RQ-033, RQ-034 |
| EV-014 | FEF-FGR-001 Founder Governance Review Record | `docs/governance/reviews/FEF-FGR-001-Founder-Governance-Review.md` | `9f3b0ed5d17d67330a2e8eaa508e63c825a745fd` | `ade6b4ed4ff1af5c234d851c23d46a8b89322461e6f5fe02f48f8d62b368c145` | E2 | Context Only | RQ-037 |
| EV-017 | Operational Authority Boundary | `docs/governance/reviews/FEF-FGR-002/FEF-FGR-002-OAB-001-OPERATIONAL-AUTHORITY-BOUNDARY.md` | `c64db2829c1e5f98d0486230c3c8ba67ed8cd31b` | `415f61a8fa11fb2792e1d87c4b0f4a10c60ad242c82b69aefbfdebb17b3b94e6` | E2 | Admitted | RQ-035, RQ-036 |
| EV-066 | FD-011 — Evidence Qualification and Permitted Reliance | `docs/governance/reviews/FEF-FGR-002/FEF-FGR-002-FD-011-EVIDENCE-QUALIFICATION-AND-PERMITTED-RELIANCE.md` | `517551787e47c2e4ad410c428a6ad7bd49648b2e` | `1e3eb7286f6a07a38ee1c3bf4259bea0a755c64dd133ddd65204b788bfdee7f4` | E1 | Admitted | RQ-036 |
| EV-070 | FD-015 — Evidence Traceability and Controlled Reuse | `docs/governance/reviews/FEF-FGR-002/FEF-FGR-002-FD-015-EVIDENCE-TRACEABILITY-AND-CONTROLLED-REUSE.md` | `3953aa75e98f24a093a68b200d75314a5a19951f` | `7970e6e159cbf2de454c986d44af830fab65ef915066dc9b5b746d04e55bae16` | E1 | Admitted | RQ-033 |
| EV-072 | FEF Document Manifest | `docs/programme/FEF-DOCUMENT-MANIFEST.md` | Two acquisition points — see Pack §6.1 | Two acquisition digests — see Pack §6.1 | E2 | Conditionally Admitted | RQ-032, RQ-034 |
| EV-073 | D3 Governance Assurance Traceability Register | `docs/governance/reviews/FEF-FGR-002/FEF-FGR-002-D3-TRACEABILITY-REGISTER.md` | `3953aa75e98f24a093a68b200d75314a5a19951f` | `5e98e29ffda20ac4fb87d50b0eeea5abb45e2963e570a08a0e9c2627465f8b30` | E4 | Admitted | RQ-033, RQ-034 |
| EV-074 | Phase 2 Founder Decision Record | `docs/governance/reviews/FEF-FGR-002/FEF-FGR-002-PHASE-2-FOUNDER-DECISION-RECORD.md` | `bb47b0bc514f9f147b37b7131720cbca5590f800` | `c2755fa642c6ae0854a618aa0cc0e85f237bd60f91982125aa7415d1688e3aa5` | E1 | Admitted | RQ-032, RQ-035, RQ-036 |
| EV-075 | FEF-FGR-002-D5-MOB-001 — D5 Mobilisation Record | `docs/governance/reviews/FEF-FGR-002/FEF-FGR-002-D5-MOB-001-GOVERNANCE-LIFECYCLE-AND-EVOLUTION-MOBILISATION-RECORD.md` | `bb47b0bc514f9f147b37b7131720cbca5590f800` | `95701a0eafeee644aad38925bbadf9e41702b72ebbcd73281c6a1c4d9cb7f331` | E2 | Admitted | RQ-032 |
| EV-076 | FEF-FGR-002-D5-FMAR-001 — D5 Founder Mobilisation Authorisation Record | `docs/governance/reviews/FEF-FGR-002/FEF-FGR-002-D5-FOUNDER-MOBILISATION-AUTHORISATION-RECORD.md` | `bb47b0bc514f9f147b37b7131720cbca5590f800` | `44bc7c365fe20c80f116222629e087027f742145ad0f3f57e40655db0fbd5acf` | E1 | Admitted | RQ-032 |
| EV-077 | FEF-FGR-002 Session Register | `docs/governance/reviews/FEF-FGR-002/FEF-FGR-002-SESSION-REGISTER.md` | `bb47b0bc514f9f147b37b7131720cbca5590f800` | `428fc9073d85c2a2cfa02de5f98c4021bfbf57b2065b0f66b22d1454364f1d59` | E4 | Admitted | RQ-032 |
| EV-078 | FEF-FGR-002-D3-QM-001 — D3 Quarantine Manifest | `docs/governance/reviews/FEF-FGR-002/FEF-FGR-002-D3-QUARANTINE-2026-07-25/FEF-FGR-002-D3-QUARANTINE-MANIFEST.md` | `3953aa75e98f24a093a68b200d75314a5a19951f` | `c79385ffba6698dfe77959a2331799e017ef6b89c5cb55965a601474b13946f9` | E1 | Admitted | RQ-033, RQ-035, RQ-037 |
| EV-079 | FEF-FGR-002-D3-C1 — Governance Assurance Stage Closure and E1 Readiness Assessment (Corrected) | `docs/governance/reviews/FEF-FGR-002/FEF-FGR-002-D3-C1-GOVERNANCE-ASSURANCE-STAGE-CLOSURE-AND-E1-READINESS-ASSESSMENT.md` | `3953aa75e98f24a093a68b200d75314a5a19951f` | `1630eb575de4716b7a97061f780478a4851cbdf2ec77fe04376094868f054263` | E1 | Admitted | RQ-033, RQ-035 |
| EV-080 | FEF Master Programme | `docs/programme/FEF-MASTER-PROGRAMME.md` | Two acquisition points — see Pack §6.2 | Two acquisition digests — see Pack §6.2 | E2 | Admitted | RQ-034, RQ-037 |
| EV-081 | FEF-FGR-002 Review Question Register (observed pre-loop) | `docs/governance/reviews/FEF-FGR-002/FEF-FGR-002-REVIEW-QUESTION-REGISTER.md` | `42de97ed065f44f7e89cf6c32637f0aacaee93df` | `f25d51c0785c565613123d2a8eeb762fb7ddf6e86009f0772a46721a5c0b77f5` | E4 | Admitted | RQ-034 |
| EV-082 | Founder Repository Architecture Standard (FRAS) — Candidate Proposal | `docs/programme/FEF-FRAS-CANDIDATE-PROPOSAL.md` | `c64db2829c1e5f98d0486230c3c8ba67ed8cd31b` | `c45c3877923ac551347b21d9c6002c45d0d3d98324f7b1f1d6f0f5cc326c6288` | E2 | Admitted | RQ-035 |
| EV-083 | FEF-FEV-001 — Framework Evolution Intake Programme Overview | `docs/programme/FEF-FEV-001-FRAMEWORK-EVOLUTION-INTAKE-PROGRAMME-OVERVIEW.md` | `517551787e47c2e4ad410c428a6ad7bd49648b2e` | `b2689e9821d54612354202e9af9e4ec212a7aec5afabfebe2d80f72b7ecebfd4` | E2 | Admitted | RQ-036 |
| EV-084 | FEF Draft Foundational Principles | `docs/governance/FEF-DRAFT-PRINCIPLES.md` | `9f3b0ed5d17d67330a2e8eaa508e63c825a745fd` | `79420c304f8cc6f7db3229cf8027d332b18344e502124657c91ddf516be6164f` | E2 | Admitted | RQ-037 |
| EV-085 | FEF-FGR-002 Governance Finding Register | `docs/governance/reviews/FEF-FGR-002/FEF-FGR-002-GOVERNANCE-FINDING-REGISTER.md` | `9f3b0ed5d17d67330a2e8eaa508e63c825a745fd` | `787193af41822a4c5de33770a19e9f11f7cb5b714392ab76935d55e7be990614` | E4 | Admitted | RQ-037 |

EV-009, EV-010, EV-014, EV-017, and EV-066 each received their first literal SHA-256 digest recorded anywhere in this review during the D5 execution loop cited in the "Provenance Commit" column above (their original D1/D2/D3-era Evidence Register rows recorded only a non-numeric disclosure such as "SHA-256 recorded," "SHA-256 reverified," or a commit-hash reference). This is a pre-existing register-formatting observation, not a content change, and was disclosed at the time each digest was first recorded.

## 2. Exact Source-to-Requirement Map

| Requirement | RQ | Evidence |
|---|---|---|
| D5-RQ032-EVR-001 | RQ-032 | EV-005, EV-007, EV-008 |
| D5-RQ032-EVR-002 | RQ-032 | EV-074, EV-076 |
| D5-RQ032-EVR-003 | RQ-032 | EV-072, EV-075, EV-077 |
| D5-RQ032-EVR-004 | RQ-032 | EV-013 |
| D5-RQ033-EVR-001 | RQ-033 | EV-009, EV-010 |
| D5-RQ033-EVR-002 | RQ-033 | EV-078, EV-079 |
| D5-RQ033-EVR-003 | RQ-033 | EV-070, EV-073 |
| D5-RQ033-EVR-004 | RQ-033 | EV-012, EV-013 |
| D5-RQ034-EVR-001 | RQ-034 | EV-080 |
| D5-RQ034-EVR-002 | RQ-034 | EV-073, EV-081 |
| D5-RQ034-EVR-003 | RQ-034 | EV-013, EV-072 |
| D5-RQ034-EVR-004 | RQ-034 | EV-012 |
| D5-RQ035-EVR-001 | RQ-035 | EV-017 |
| D5-RQ035-EVR-002 | RQ-035 | EV-078, EV-079 |
| D5-RQ035-EVR-003 | RQ-035 | EV-005, EV-078 |
| D5-RQ035-EVR-004 | RQ-035 | EV-074, EV-082 |
| D5-RQ036-EVR-001 | RQ-036 | EV-005 |
| D5-RQ036-EVR-002 | RQ-036 | EV-066, EV-074 |
| D5-RQ036-EVR-003 | RQ-036 | EV-017 |
| D5-RQ036-EVR-004 | RQ-036 | EV-012, EV-083 |
| D5-RQ037-EVR-001 | RQ-037 | EV-084 |
| D5-RQ037-EVR-002 | RQ-037 | EV-080, EV-014 |
| D5-RQ037-EVR-003 | RQ-037 | EV-085, EV-078 |
| D5-RQ037-EVR-004 | RQ-037 | EV-012 |

The 24 requirement rows contain 42 source-to-requirement links (EV-078 appears in both `D5-RQ035-EVR-002` and `D5-RQ035-EVR-003`, the one case of a source supporting two requirements within the same RQ). Controlled reuse across the six RQs produces 41 source-to-RQ mappings and 25 unique Evidence Records. No mapping is added, removed, combined, or inferred.

## 3. Mobilisation Control Linkage

| RQ | Loop | Mobilisation Record | Validation Report | Verdict |
|---|---:|---|---|---|
| RQ-032 | 001 | [FEF-FGR-002-D5-RQ032-EMQR-001](FEF-FGR-002-D5-RQ-032-EVIDENCE-MOBILISATION-AND-QUALIFICATION-RECORD.md) | [FEF-FGR-002-D5-RQ032-EMVR-001](FEF-FGR-002-D5-RQ-032-EVIDENCE-MOBILISATION-VALIDATION-REPORT.md) | Pass with Conditions |
| RQ-033 | 002 | [FEF-FGR-002-D5-RQ033-EMQR-001](FEF-FGR-002-D5-RQ-033-EVIDENCE-MOBILISATION-AND-QUALIFICATION-RECORD.md) | [FEF-FGR-002-D5-RQ033-EMVR-001](FEF-FGR-002-D5-RQ-033-EVIDENCE-MOBILISATION-VALIDATION-REPORT.md) | Pass with Conditions |
| RQ-034 | 003 | [FEF-FGR-002-D5-RQ034-EMQR-001](FEF-FGR-002-D5-RQ-034-EVIDENCE-MOBILISATION-AND-QUALIFICATION-RECORD.md) | [FEF-FGR-002-D5-RQ034-EMVR-001](FEF-FGR-002-D5-RQ-034-EVIDENCE-MOBILISATION-VALIDATION-REPORT.md) | Pass with Conditions |
| RQ-035 | 004 | [FEF-FGR-002-D5-RQ035-EMQR-001](FEF-FGR-002-D5-RQ-035-EVIDENCE-MOBILISATION-AND-QUALIFICATION-RECORD.md) | [FEF-FGR-002-D5-RQ035-EMVR-001](FEF-FGR-002-D5-RQ-035-EVIDENCE-MOBILISATION-VALIDATION-REPORT.md) | Pass with Conditions |
| RQ-036 | 005 | [FEF-FGR-002-D5-RQ036-EMQR-001](FEF-FGR-002-D5-RQ-036-EVIDENCE-MOBILISATION-AND-QUALIFICATION-RECORD.md) | [FEF-FGR-002-D5-RQ036-EMVR-001](FEF-FGR-002-D5-RQ-036-EVIDENCE-MOBILISATION-VALIDATION-REPORT.md) | Pass with Conditions |
| RQ-037 | 006 | [FEF-FGR-002-D5-RQ037-EMQR-001](FEF-FGR-002-D5-RQ-037-EVIDENCE-MOBILISATION-AND-QUALIFICATION-RECORD.md) | [FEF-FGR-002-D5-RQ037-EMVR-001](FEF-FGR-002-D5-RQ-037-EVIDENCE-MOBILISATION-VALIDATION-REPORT.md) | Pass with Conditions |

[FEF-FGR-002-D5-EMCR-001](FEF-FGR-002-D5-EVIDENCE-MOBILISATION-COMPLETION-REVIEW.md) (v1.1) and [FEF-FGR-002-D5-EPRVR-001](FEF-FGR-002-D5-EVIDENCE-PACK-READINESS-VALIDATION-REPORT.md) (v1.1) reconcile the cumulative corpus and control the 25-record / 41-mapping / 42-link baseline. [FEF-FGR-002-D5-PCARR-001](FEF-FGR-002-D5-POST-COMPLETION-ADMINISTRATIVE-RECONCILIATION-RECORD.md) and [FEF-FGR-002-D5-PCARVR-001](FEF-FGR-002-D5-POST-COMPLETION-ADMINISTRATIVE-RECONCILIATION-VALIDATION-REPORT.md) confirm this baseline unaffected by the subsequent programme-metadata corrections.

## 4. Authority, Limitation, and Permitted-Use Controls

| Evidence | Preserved Boundary |
|---|---|
| EV-005 | Founder-approved Charter; RQ-032 general baseline, RQ-035 §8 preservation rule, RQ-036 §21.3 exceptions rule — each bounded separately |
| EV-007 | Founder-approved Plan scope only |
| EV-008 | Review execution-rule scope only |
| EV-009 | Approval-record example only |
| EV-010 | Approval-record example only |
| EV-012 | Open-question evidence only; records questions, not answers; each RQ cites a distinct OQ |
| EV-013 | Non-authoritative research draft; instrument-level versioning/status example only |
| EV-014 | "Incomplete — Missing Source Evidence" classification example only; Context Only |
| EV-017 | Review-operational authority boundary only |
| EV-066 | "Accept with Conditions" operated example only |
| EV-070 | Version-at-decision traceability example only |
| EV-072 | Mutable, non-authoritative programme index; source records control; both acquisition points bounded separately (Pack §6.1) |
| EV-073 | RQ-033 version-at-decision example; RQ-034 dual-axis versioning example |
| EV-074 | RQ-032 FEF-CCF-001 boundary; RQ-035 candidate-registration contrast; RQ-036 conditioned-disposition example — each bounded separately |
| EV-075 | Domain-level transition example only |
| EV-076 | Gate-level Founder-authority example only |
| EV-077 | One register's field design only |
| EV-078 | Correction/recovery example only, never an ordinary amendment; RQ-033, RQ-035 (two requirements), and RQ-037 uses preserved separately |
| EV-079 | Correction/supersession example with explicit Correction Notice |
| EV-080 | Mutable Master Programme; both acquisition points bounded separately (Pack §6.2); RQ-034 versioning example, RQ-037 legacy-plan classification example |
| EV-081 | Pre-loop dual-axis versioning example only; bounded to v1.46 observation |
| EV-082 | Sole pre-decision registration-only lifecycle-stage example |
| EV-083 | Structural, mechanism-level status only; no submitted candidate evaluated |
| EV-084 | Sole "exploratory draft" classification example |
| EV-085 | GF-001's already-dispositioned text cited only; not re-examined |

The exact RQ-specific limitations, gaps, conflict treatments, uncertainties, and permitted uses in each linked mobilisation record remain part of this manifest by controlled reference and may not be compressed away during any later examination.

## 5. Open Question and Dependency Preservation

| RQ | Preserved Open Question Mapping |
|---|---|
| RQ-032 | OQ-004 direct; OQ-022 direct |
| RQ-033 | OQ-017 direct |
| RQ-034 | OQ-014 direct |
| RQ-035 | OQ-021 direct |
| RQ-036 | OQ-012 direct |
| RQ-037 | OQ-013 partial; OQ-016 partial |

All mappings preserve the Open Questions unchanged and open. D6 and D7 remain separately governed, unresolved, and not reached. FEF-FEV-001-FEC-001, FEF-CCF-001, and CE1–CE6 remain unevaluated and undispositioned.

## 6. Deterministic Ordering

Applied ordering, consistent with prior Evidence Pack precedent (FEF-FGR-002-EP-004):

1. RQ order: RQ-032 through RQ-037;
2. requirement order within each RQ (EVR-001 through EVR-004);
3. Evidence Record identifier order within each requirement, as originally recorded in the source EMQR;
4. the unique-membership catalogue in Section 1 above, ordered numerically by Evidence Record identifier.

The same inputs (the six EMQR records, the Evidence Register, and the Review Question Register at the baselines named above) always generate this same ordering and the fingerprint recorded in the pack's Section 9.

## 7. Manifest Closure

This manifest is closed at EP-005 v1.0 freeze (FEF-FGR-002-EP-005-FR-001), exactly as FEF-FGR-002-EP-004-MAN-001 was closed at its own freeze. No item, requirement, mapping, digest, provenance value, class, admissibility state, limitation, permitted use, Open Question mapping, or dependency boundary may be changed inside this frozen version. Change requires a governed successor or supplemental pack and revalidation. Between assembly (2026-07-30) and freeze (2026-07-31), the D5 EP-005 Pre-Freeze Programme and RQ-State Reconciliation (FEF-FGR-002-D5-PFRR-001) independently reverified this manifest's content, fingerprints, and every input listed above as byte-identical to assembly; no item, requirement, mapping, digest, provenance value, class, admissibility state, limitation, permitted use, Open Question mapping, or dependency boundary was changed, added, or removed at any point from assembly through freeze.
