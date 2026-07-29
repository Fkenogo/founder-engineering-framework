# FEF-FGR-002-D5-RQ032-EMQR-001 — RQ-032 Evidence Mobilisation and Qualification Record

| Control Field | Recorded Value |
|---|---|
| Record identifier | FEF-FGR-002-D5-RQ032-EMQR-001 |
| Review identifier | FEF-FGR-002 |
| Domain | D5 — Governance Lifecycle and Evolution |
| Execution loop | 001 |
| Review Question | FEF-FGR-002-RQ-032 only |
| Record version | 1.0 |
| Acquisition and qualification date | 2026-07-29 |
| Starting repository baseline | `bb47b0bc514f9f147b37b7131720cbca5590f800` |
| Preparation capacity | FEF-FGR-002-RA-003 — Review Analyst |
| Evidence Custodian | FEF-FGR-002-RA-005 |
| Validator | FEF-FGR-002-RA-006 — non-independent combination disclosed |
| Candidate sources assessed | 9 |
| Existing Evidence Records reused | 6 |
| New Evidence Records registered | 3 |
| Evidence Pack effect | None |
| Examination effect | None |
| Status | **Evidence Mobilised — Qualified with Conditions; Not Packed; Not Examined** |

## 1. Entry Gate

The gate was verified before candidate-source identification:

| Entry Condition | Result |
|---|---|
| Branch and repository | Pass — `main`, clean |
| Local/remote synchronization | Pass — `0/0` divergence, verified after the authorised push of `bb47b0b` |
| Merge or rebase | Pass — none in progress |
| D5 mobilisation | Pass — Mobilised — Effective, subject to four Founder conditions |
| D5 Review Question Admission | Pass — Complete |
| RQ-032 | Pass — Admitted; Evidence Mobilisation Not Started |
| RQ-033 through RQ-037 | Pass — Admitted; Evidence Mobilisation Not Started; outside this loop |
| D5 Evidence Pack | Pass — no D5 pack exists or is frozen |
| D5 session / examination | Pass — none created or commenced |

## 2. RQ-032 Boundary

### Exact Question

> What drafting, review, and operational states, if any, do FEF governance instruments pass through, and by what Founder or delegated authority is each state transition confirmed?

### Candidate-Set Generic Evidence Guidance (Not a Derived Requirement)

> Master Programme, Dashboard, and Manifest status fields; FEF-RGS-000's status field; Governance Finding/Founder Decision Register "Decision Record Validated" vs "Pending" distinction — source-preserved generic classes only.

This generic guidance, inherited from FEF-FGR-002-D5-RQC-001, is a candidate-preparation aid only. It is not treated as an already-derived requirement. Section 3 below derives the actual requirements for this loop independently, using the exact question, purpose, scope, exclusions, and dependencies recorded in FEF-FGR-002-D5-RQS-001.

The search was limited to the four requirement domains identified in Section 3. It did not identify evidence for RQ-033 through RQ-037 and did not determine the answer to RQ-032.

## 3. Evidence Requirements for This Loop

| Requirement | Required Source Characteristic | Purpose | Candidate Treatment |
|---|---|---|---|
| D5-RQ032-EVR-001 | Current controlled FEF review instruments that define the review's own gate/lifecycle model and the vocabulary used to describe instrument readiness or effect | Establish the applicable normative baseline for what "state" vocabulary is already approved, without inventing a general lifecycle model | EV-005, EV-007, EV-008 |
| D5-RQ032-EVR-002 | Attributable Founder-confirmed records demonstrating the exact authority behind an observed state transition (mobilisation, disposition, milestone approval) | Test whether observed transitions are genuinely confirmed by Founder or delegated authority, and what that confirmation looks like in practice | EV-074, EV-076 |
| D5-RQ032-EVR-003 | Operated repository sources that track more than one kind of lifecycle-state field side by side (e.g., document status, session state, register version) so the distinct axes can be compared | Distinguish instrument lifecycle state from review-question, evidence/pack, session, finding/decision, validation, and programme-management status, per RQ-032's explicit scope | EV-072, EV-075, EV-077 |
| D5-RQ032-EVR-004 | A source exposing draft/legacy status vocabulary and any authority or approval limitation attached to it | Preserve available terminology while distinguishing unapproved proposals and legacy material from current controlling instruments | EV-013; explicit gap retained |

No requirement is padded with duplicate sources. The requirements describe the evidence needed for RQ-032 only and do not predetermine a status vocabulary, approval model, or finding.

## 4. Candidate Source Catalogue

| Evidence | Source | Controlled Path | Current Authority / State | Class | Requirement | Candidate Result |
|---|---|---|---|---|---|---|
| EV-005 — reuse | FEF-FGRC-001 Founder Governance Review Charter | `docs/governance/reviews/FEF-FGRC-001-FOUNDER-GOVERNANCE-REVIEW-CHARTER.md` | Founder-approved review Charter | E2 | D5-RQ032-EVR-001 | Admitted |
| EV-007 — reuse | FEF-FGRP-001 Founder Governance Review Plan | `docs/governance/reviews/FEF-FGRP-001-FOUNDER-GOVERNANCE-REVIEW-PLAN.md` | Founder-approved review Plan | E2 | D5-RQ032-EVR-001 | Admitted |
| EV-008 — reuse | FEF-FGRER-001 Review Execution Rules | `docs/governance/reviews/FEF-FGRER-001-REVIEW-EXECUTION-RULES.md` | Review preparation baseline operating under the approved Plan; DG-0 through DG-7 permitted-outcomes table | E2 | D5-RQ032-EVR-001 | Admitted |
| EV-013 — reuse | FEF-RGS-000 Research Governance Standard | `docs/governance/research/FEF-RGS-000-RESEARCH-GOVERNANCE-STANDARD.md` | Draft v0.2; Founder Review Required; Not Approved | E2 | D5-RQ032-EVR-004 | Conditionally Admitted |
| EV-072 — reuse | FEF Document Manifest | `docs/programme/FEF-DOCUMENT-MANIFEST.md` | Draft; non-authoritative document index; continuously updated since original qualification | E2 | D5-RQ032-EVR-003 | Conditionally Admitted |
| EV-074 — reuse | FEF-FGR-002 Phase 2 Founder Decision Record | `docs/governance/reviews/FEF-FGR-002/FEF-FGR-002-PHASE-2-FOUNDER-DECISION-RECORD.md` | Recorded — Validation Passed; Approve with Conditions | E1 | D5-RQ032-EVR-002 | Admitted |
| EV-075 — new | FEF-FGR-002-D5-MOB-001 — D5 Mobilisation Record | `docs/governance/reviews/FEF-FGR-002/FEF-FGR-002-D5-MOB-001-GOVERNANCE-LIFECYCLE-AND-EVOLUTION-MOBILISATION-RECORD.md` | v1.1; Mobilised — Effective, subject to four Founder conditions | E2 | D5-RQ032-EVR-001; D5-RQ032-EVR-003 | Admitted |
| EV-076 — new | FEF-FGR-002-D5-FMAR-001 — D5 Founder Mobilisation Authorisation Record | `docs/governance/reviews/FEF-FGR-002/FEF-FGR-002-D5-FOUNDER-MOBILISATION-AUTHORISATION-RECORD.md` | v1.1; Recorded — Validation Passed; Approve with Conditions | E1 | D5-RQ032-EVR-002 | Admitted |
| EV-077 — new | FEF-FGR-002 Session Register | `docs/governance/reviews/FEF-FGR-002/FEF-FGR-002-SESSION-REGISTER.md` | v1.34; Active; four registered/opened sessions | E4 | D5-RQ032-EVR-003 | Admitted |

## 5. Provenance and Integrity

| Evidence | Origin / Acquisition Route | Repository Commit | SHA-256 at Qualification |
|---|---|---|---|
| EV-005 | Existing Evidence Record; local read and digest revalidation | `bb47b0bc514f9f147b37b7131720cbca5590f800` | `e007510ba3eb3a115177522c041bb91284f5f0efe3fdd3f185c7565c09c52d72` (matches prior D4-era digest — unchanged) |
| EV-007 | Existing Evidence Record; local read and digest revalidation | `bb47b0bc514f9f147b37b7131720cbca5590f800` | `eb1e59544a32888bc3b20b5f87a0bb5342f350539946782196d5a31757ba6568` (matches prior D4-era digest — unchanged) |
| EV-008 | Existing Evidence Record; local read and digest revalidation | `bb47b0bc514f9f147b37b7131720cbca5590f800` | `625cbd574e8354fc8ed6191b4c87cdce9d66d781ebfe1f43c3ac0b31e643a35f` (matches prior D4-era digest — unchanged) |
| EV-013 | Existing Evidence Record; local read and digest revalidation | `bb47b0bc514f9f147b37b7131720cbca5590f800` | `ed20b516270839d8ce24561548de0c345a9fb28e7cc76312aa9e4e65e8f3d56b` (matches prior D4-era digest — unchanged) |
| EV-072 | Existing Evidence Record; local read and digest revalidation | `bb47b0bc514f9f147b37b7131720cbca5590f800` | `c26de951d3a14d10954505bb035ac7dd38e2c2ae0c1b521c0907c009a8beb8ac` (**changed** since D4-era qualification `31807d1d...`, consistent with its disclosed mutable-index limitation; observed state at this loop's baseline only) |
| EV-074 | Existing Evidence Record; local read and digest revalidation | `bb47b0bc514f9f147b37b7131720cbca5590f800` | `c2755fa642c6ae0854a618aa0cc0e85f237bd60f91982125aa7415d1688e3aa5` (matches prior D4-era digest — unchanged) |
| EV-075 | Controlled repository path; local read; new Evidence Record | `bb47b0bc514f9f147b37b7131720cbca5590f800` | `95701a0eafeee644aad38925bbadf9e41702b72ebbcd73281c6a1c4d9cb7f331` |
| EV-076 | Controlled repository path; local read; new Evidence Record | `bb47b0bc514f9f147b37b7131720cbca5590f800` | `44bc7c365fe20c80f116222629e087027f742145ad0f3f57e40655db0fbd5acf` |
| EV-077 | Controlled repository path; local read; new Evidence Record | `bb47b0bc514f9f147b37b7131720cbca5590f800` | `428fc9073d85c2a2cfa02de5f98c4021bfbf57b2065b0f66b22d1454364f1d59` |

Access treatment for every source is `Repository`. No copy, transformation, excerpt file, or derivative evidence artefact was created.

## 6. D2 Admissibility Tests

| Evidence | Identity | Provenance | Integrity | Authority | Relevance | Temporal Applicability | Accessibility | Conflict Treatment | Uncertainty | Permitted Use |
|---|---|---|---|---|---|---|---|---|---|---|
| EV-005 | Pass | Pass | Pass | Pass — within approved Charter scope | Pass — direct (domain table §6, DG model) | Pass | Pass | No source contradiction identified | Bound to review-scoped controls | Pass |
| EV-007 | Pass | Pass | Pass | Pass — within approved Plan scope | Pass — direct (domain mapping §6) | Pass | Pass | No source contradiction identified | Does not itself decide D5 | Pass |
| EV-008 | Pass | Pass | Pass | Pass — operational rule boundary | Pass — direct (DG-0 through DG-7 permitted-outcomes table) | Pass | Pass | No source contradiction identified | Gate labels are rule vocabulary, not evidence of an occurred gate | Pass |
| EV-013 | Pass | Pass | Pass | Limited — non-authoritative draft | Pass — contextual (its own "Draft v0.2 — Founder Review Required" status label) | Pass | Pass | Draft status does not conflict with approved instruments because no approval is claimed | Research-specific; its status label is not evidence of a FEF-wide model | Pass within limitation |
| EV-072 | Pass | Pass | Pass | Limited — non-authoritative index | Pass — direct evidence of listed document status/category fields as currently observed | Pass — observed 2026-07-29 state | Pass | Source records control if an index entry conflicts | Digest changed since original observation; index is mutable and non-authoritative | Pass within limitation |
| EV-074 | Pass | Pass | Pass | Pass — attributable Founder disposition | Pass — direct example of a Founder-confirmed milestone-level transition | Pass as a 2026-07-28 snapshot | Pass | No source contradiction identified | One milestone example; does not establish a universal transition-authority model | Pass |
| EV-075 | Pass | Pass | Pass | Pass — Founder-authorised mobilisation record | Pass — direct example distinguishing preparation authority from mobilisation authority and instrument-level from RQ/evidence/session state | Pass — current, v1.1 | Pass | No source contradiction identified | Domain-level example only; does not establish a cross-instrument model | Pass |
| EV-076 | Pass | Pass | Pass | Pass — attributable Founder disposition, exact wording preserved | Pass — direct example of the exact authority (Founder) and exact disposition options confirming a state transition | Pass — current, v1.1 | Pass | No source contradiction identified | One domain's mobilisation-gate example; the four other DG-labelled gates in EV-008 are not separately evidenced here | Pass |
| EV-077 | Pass | Pass | Pass | Pass — validated FEF-FGR-002 operational register | Pass — direct example of "Session State" tracked as a field distinct from instrument, RQ, and register version state | Pass — current, v1.34 | Pass | No source contradiction identified | One register's field design; does not establish that all state axes are consistently separated elsewhere | Pass |

## 7. Qualification Dispositions

### EV-005 — Charter

**Class:** E2. **Disposition:** Admitted. **Permitted use:** the domain table (§6) and its "Required Boundary" column as the controlling description of what each domain — including D5 itself — may and may not do; general review governance vocabulary. It does not itself define an instrument status/approval model.

### EV-007 — Plan

**Class:** E2. **Disposition:** Admitted. **Permitted use:** the Governance Domain Mapping (§6) and Decision Gate Model (§7) as the controlling operational sequence and exit-product classes. It does not answer which status vocabulary should become enduring outside this review.

### EV-008 — Execution Rules

**Class:** E2. **Disposition:** Admitted. **Permitted use:** the DG-0 through DG-7 Decision Gate table, including "Permitted Outcomes" (Approve, condition, return, defer, decline/reject, etc.) as the controlling, already-approved gate-outcome vocabulary. The record itself states gate identifiers "are rule labels, not review artefact identifiers or evidence that a gate has occurred" — this limitation is preserved, not resolved.

### EV-013 — FEF-RGS-000

**Class:** E2. **Disposition:** Conditionally Admitted. **Permitted use:** its own header status field ("Draft v0.2 — Founder Review Required; not approved") as one operated example of a pre-approval instrument state, distinct from and outside the FEF-FGR-002 review's own gate vocabulary. Its `Not Approved` status is controlling; no proposed content is treated as current authority.

### EV-072 — FEF Document Manifest

**Class:** E2. **Disposition:** Conditionally Admitted. **Permitted use:** evidence of the range of document status labels actually in use across the repository at the qualified observation date (e.g., "Draft," "Current," "Active," "Closed," "Approved for Pilot Use," "Candidate — Not Authored; Not Active"). The index is non-authoritative and mutable; its digest has already changed since the D4-era qualification, and controlling source records prevail over any Manifest entry.

### EV-074 — Phase 2 Founder Decision Record

**Class:** E1. **Disposition:** Admitted. **Permitted use:** a direct, attributable example of a Founder-confirmed milestone-level state transition ("Approve with Conditions" recorded and validated), showing the Founder as the confirming authority. It is one milestone-level example, not a universal model.

### EV-075 — FEF-FGR-002-D5-MOB-001

**Class:** E2. **Disposition:** Admitted. **Permitted use:** a direct, attributable example distinguishing "preparation authority" (task-level) from "mobilisation authority" (Founder-level) for the same instrument, and showing an instrument-level lifecycle state ("Mobilised — Effective, subject to four recorded conditions") that is explicitly not the same as any RQ, evidence, or session state recorded in the same review. Domain-level example only.

### EV-076 — FEF-FGR-002-D5-FMAR-001

**Class:** E1. **Disposition:** Admitted. **Permitted use:** the exact, attributable Founder disposition and the enumerated permitted-outcomes list (Approve / Approve with Conditions / Return for Clarification / Defer / Reject) as a direct example of the authority and options structure behind one instrument-level state transition. It documents one gate only; the other DG-labelled gates in EV-008 are not separately evidenced by this record.

### EV-077 — FEF-FGR-002 Session Register

**Class:** E4. **Disposition:** Admitted. **Permitted use:** an operated example of "Session State" tracked as its own field, distinct from "Entry-Gate State," and distinct from the Review Question, Evidence Pack, and Founder Decision states tracked in other registers — directly supporting the RQ-032 boundary requirement to distinguish these axes. It demonstrates one register's field design only.

## 8. Qualification Totals

| Disposition | Count |
|---|---:|
| Admitted | 7 |
| Conditionally Admitted | 2 |
| Context Only | 0 |
| Rejected | 0 |
| Total | 9 |

Evidence class constrains permitted use but does not determine weight. No ranking, score, or substantive conclusion is produced by this qualification.

## 9. Limitations, Conflicts, and Gaps

### 9.1 Limitations

- EV-005, EV-007, and EV-008 govern the Founder Governance Review's own procedure and do not by themselves establish a general FEF-wide instrument-status model.
- EV-013 is research-specific and expressly not approved; its status label is one data point, not a model.
- EV-072 is a mutable, non-authoritative index whose digest has already changed since it was first qualified for D4; its category/status columns are not a complete or stable metadata model.
- EV-074, EV-075, and EV-076 are each single, domain- or milestone-scoped examples of a Founder-confirmed transition; none establishes that every instrument-level transition follows the same pattern.
- EV-077 documents one register's field design; it does not establish that "state" is consistently separated from other axes everywhere in the repository.
- All qualification and validation in this loop is performed by the same combined acting capacity; no independent evidence validation exists.

### 9.2 Conflicts and Conflation Risks (Preserved, Not Resolved)

- **Terminology inconsistency:** the qualified sources use materially different words for states that may describe similar underlying conditions — "Mobilised — Effective" (D4/D5 domain mobilisation, EV-075), "Active" (FEF-FGR-002 review-level, EV-005/EV-008 usage), "Current" (Master Programme, referenced generically in the candidate-preparation guidance), and "Approved for Pilot Use" (EV-072 index entries). No source reconciles these terms, and this record does not attempt to.
- **Approval/validation conflation risk:** EV-008's DG-0 "Approve Review Plan" gate outcome and EV-074/EV-076's "Approve" / "Approve with Conditions" Founder dispositions use the same word for what may be procedurally distinct actions (approving a plan document versus approving a milestone or mobilisation record). Whether these are the same kind of "approval" or materially different is left open.
- **Delegated-authority gap:** no source in this loop documents an instance of a state transition confirmed by a *delegated* (non-Founder) authority, as distinct from an *operational* capacity acting under a disclosed non-independent role combination (e.g., RA-002 "controls sequence... and the next authority gate" is not the same as RA-002 confirming the transition itself). Whether any transition is ever delegated, versus always reserved to the Founder, is not established either way by this evidence set.

### 9.3 Evidence Gaps

| Gap | Classification | Treatment |
|---|---|---|
| No approved FEF-wide instrument-status/lifecycle vocabulary or model was located | Material and directly relevant | Preserve for examination; do not infer a model from repository repetition |
| No operated example of an instrument-level "Withdrawn" or "Superseded" state was located (the D3 quarantine treats voided *evidence artefacts*, not an instrument-level status, and is a distinct axis) | Material and directly relevant | Preserve as an untested lifecycle state; do not conflate evidence-quarantine treatment with instrument status |
| No source documents a delegated (non-Founder) confirmation of a state transition | Material and directly relevant | Preserve as an open question; absence is not evidence that delegation cannot or does not occur |
| Whether "Approve" as a DG-0 Plan-approval outcome and "Approve" as a Founder mobilisation disposition are the same kind of act is unresolved | Material and directly relevant | Preserve as a conflation risk for examination, not resolved here |
| Observed sources demonstrate current repository practice but do not establish its completeness, necessity, or sufficiency | Manageable limitation | Permit later evidence-bounded comparison; do not convert practice into policy |
| No independent qualification pass | Assurance limitation | Disclose; retain hashes, exact paths, and deterministic reconciliation as compensating controls |

These gaps do not prevent mobilisation and qualification. They remain unresolved inputs to later pack-readiness and examination gates.

## 10. Registration and RQ Mapping

- Existing Evidence Records reused: EV-005, EV-007, EV-008, EV-013, EV-072, EV-074.
- New Evidence Records registered: EV-075, EV-076, EV-077.
- Related Review Question: RQ-032 only.
- RQ-033 through RQ-037 mapping: none.
- Evidence Pack membership: none.
- Session, examination, GF, and FD linkage: none.

## 11. RQ-032 Lifecycle Effect

| State Item | State After Loop 001 |
|---|---|
| RQ-032 lifecycle state | Admitted — unchanged |
| RQ-032 evidence state | **Evidence Mobilised — Qualified with Conditions; Not Packed; Not Examined** |
| RQ-033 through RQ-037 | Unchanged — Evidence Mobilisation Not Started |
| D5 Evidence Pack | Not assembled or frozen |
| D5 session / examination | Not created / not commenced |

## 12. Non-Effects

This record does not assemble or freeze an Evidence Pack, create a session, examine or answer RQ-032, mobilise evidence for RQ-033 through RQ-037, produce a Governance Finding, prepare a Founder Decision, evaluate FEF-FEV-001-FEC-001 or FEF-CCF-001, disposition CE1–CE6, establish a lifecycle standard, amend constitutional governance, or commence D6 or D7.
