# FEF-FGR-002-D5-RQ033-EMQR-001 — RQ-033 Evidence Mobilisation and Qualification Record

| Control Field | Recorded Value |
|---|---|
| Record identifier | FEF-FGR-002-D5-RQ033-EMQR-001 |
| Review identifier | FEF-FGR-002 |
| Domain | D5 — Governance Lifecycle and Evolution |
| Execution loop | 002 |
| Review Question | FEF-FGR-002-RQ-033 only |
| Record version | 1.0 |
| Acquisition and qualification date | 2026-07-30 |
| Starting repository baseline | `3953aa75e98f24a093a68b200d75314a5a19951f` |
| Preparation capacity | FEF-FGR-002-RA-003 — Review Analyst |
| Evidence Custodian | FEF-FGR-002-RA-005 |
| Validator | FEF-FGR-002-RA-006 — non-independent combination disclosed |
| Candidate sources assessed | 8 |
| Existing Evidence Records reused | 6 |
| New Evidence Records registered | 2 |
| Evidence Pack effect | None |
| Examination effect | None |
| Status | **Evidence Mobilised — Qualified with Conditions; Not Packed; Not Examined** |

## 1. Entry Gate

The gate was verified before candidate-source identification:

| Entry Condition | Result |
|---|---|
| Branch and repository | Pass — `main`, clean at task start |
| Local/remote synchronization | Pass — `0/0` divergence, verified after the authorised push of `3953aa7` |
| Merge or rebase | Pass — none in progress |
| D5 mobilisation | Pass — Mobilised — Effective, subject to four Founder conditions |
| D5 Review Question Admission | Pass — Complete |
| RQ-032 | Pass — Admitted; Evidence Mobilised and Qualified with Conditions (unchanged by this loop) |
| RQ-033 | Pass — Admitted; Evidence Mobilisation Not Started |
| RQ-034 through RQ-037 | Pass — Admitted; Evidence Mobilisation Not Started; outside this loop |
| D5 Evidence Pack | Pass — no D5 pack exists or is frozen |
| D5 session / examination | Pass — none created or commenced |

## 2. RQ-033 Boundary

### Exact Question

> When a FEF governance instrument is approved, amended, or withdrawn, does it apply retrospectively to work already underway, only to work commenced after its effective date, or under some other transitional rule, and who decides which rule applies?

### Candidate-Set Generic Evidence Guidance (Not a Derived Requirement)

> OQ-017's own recorded wording; FEF-RGS-000's current "not approved" status; FAR-001/FAR-002 as examples of scoped, non-retrospective architectural decisions — source-preserved generic classes only.

This generic guidance, inherited from FEF-FGR-002-D5-RQC-001, is a candidate-preparation aid only. It is not treated as an already-derived requirement. Section 3 below derives the actual requirements for this loop independently, using the exact question, purpose, scope, exclusions, and dependencies recorded in FEF-FGR-002-D5-RQS-001, and the sub-questions enumerated in the authorising task.

The search was limited to the four requirement domains identified in Section 3. It did not identify evidence for RQ-034 through RQ-037 and did not determine the answer to RQ-033.

## 3. Evidence Requirements for This Loop

| Requirement | Required Source Characteristic | Purpose | Candidate Treatment |
|---|---|---|---|
| D5-RQ033-EVR-001 | Attributable Founder decisions or approvals that could expose whether an effective date is ever declared distinct from an approval/record date, and what applicability rule (if any) accompanies a scoped decision | Test whether current practice distinguishes approval date from effective date, and whether a decision's applicability to prior or ongoing work is ever stated | EV-009, EV-010 |
| D5-RQ033-EVR-002 | Operated examples of prior review actions or artefacts being corrected, invalidated, or restored after a later discovery, and any accompanying non-effects treatment | Test whether work already underway has, in practice, been treated retrospectively, prospectively, or under some other rule when a correction occurred | EV-078, EV-079 |
| D5-RQ033-EVR-003 | Sources demonstrating whether the review preserves which version of an instrument governed a decision at the time it was made, and whether transitional determinations are made by the Founder or by another capacity | Test version-at-decision traceability and the attributable authority (if any) behind a transitional determination | EV-070, EV-073 |
| D5-RQ033-EVR-004 | The exact existing Open Question already posing this question for one specific instrument, and that instrument's own current approval state | Preserve the one directly on-point existing question and the one instrument it names, without treating either as resolved | EV-012, EV-013 |

No requirement is padded with duplicate sources. The requirements describe the evidence needed for RQ-033 only and do not predetermine a transitional rule, an effective-date model, or a finding.

## 4. Candidate Source Catalogue

| Evidence | Source | Controlled Path | Current Authority / State | Class | Requirement | Candidate Result |
|---|---|---|---|---|---|---|
| EV-009 — reuse | FEF-FAR-001 Founder Architectural Review | `docs/records/founder-reviews/FEF-FAR-001-FOUNDER-ARCHITECTURAL-REVIEW.md` | Founder-recorded architectural decision | E1 | D5-RQ033-EVR-001 | Admitted |
| EV-010 — reuse | FEF-FAR-002 Programme Governance Pilot | `docs/records/founder-reviews/FEF-FAR-002-PROGRAMME-GOVERNANCE-PILOT.md` | Founder-recorded pilot-recognition decision | E1 | D5-RQ033-EVR-001 | Admitted |
| EV-012 — reuse | FEF-WPK-001 Open Questions Register | `docs/records/work-packages/FEF-WPK-001/FEF-WPK-001-OPEN-QUESTIONS-REGISTER.md` | Controlled record; 23-question baseline; all open | E2 | D5-RQ033-EVR-004 | Admitted |
| EV-013 — reuse | FEF-RGS-000 Research Governance Standard | `docs/governance/research/FEF-RGS-000-RESEARCH-GOVERNANCE-STANDARD.md` | Draft v0.2; Founder Review Required; Not Approved | E2 | D5-RQ033-EVR-004 | Conditionally Admitted |
| EV-070 — reuse | FEF-FGR-002-FD-015 — Evidence Traceability and Controlled Reuse | `docs/governance/reviews/FEF-FGR-002/FEF-FGR-002-FD-015-EVIDENCE-TRACEABILITY-AND-CONTROLLED-REUSE.md` | v1.0; Accept with Conditions; Founder Decision | E1 | D5-RQ033-EVR-003 | Admitted |
| EV-073 — reuse | D3 Governance Assurance Traceability Register | `docs/governance/reviews/FEF-FGR-002/FEF-FGR-002-D3-TRACEABILITY-REGISTER.md` | v1.1; D3 Closed; DG-6 Complete | E4 | D5-RQ033-EVR-003 | Admitted |
| EV-078 — new | FEF-FGR-002-D3-QM-001 — D3 Quarantine Manifest | `docs/governance/reviews/FEF-FGR-002/FEF-FGR-002-D3-QUARANTINE-2026-07-25/FEF-FGR-002-D3-QUARANTINE-MANIFEST.md` | v1.0; Quarantined artefacts preserved, not deleted, not reused | E1 | D5-RQ033-EVR-002 | Admitted |
| EV-079 — new | FEF-FGR-002-D3-C1 — Governance Assurance Stage Closure and E1 Readiness Assessment (Corrected) | `docs/governance/reviews/FEF-FGR-002/FEF-FGR-002-D3-C1-GOVERNANCE-ASSURANCE-STAGE-CLOSURE-AND-E1-READINESS-ASSESSMENT.md` | v1.1; Corrected — Domain Not Closed | E1 | D5-RQ033-EVR-002 | Admitted |

The D3 quarantine manifest (EV-078) is a valid, current governance record describing a correction event. It is distinguished from the six voided artefacts it describes, which remain quarantined, not deleted, not reused, and are not themselves relied upon as evidence here.

## 5. Provenance and Integrity

| Evidence | Origin / Acquisition Route | Repository Commit | SHA-256 at Qualification |
|---|---|---|---|
| EV-009 | Existing Evidence Record; local read and digest revalidation | `3953aa75e98f24a093a68b200d75314a5a19951f` | `ab32f0527d7c99c7562c2c959e1426c10d6dd81a9fa4d2518c9c3059fff3a237` |
| EV-010 | Existing Evidence Record; local read and digest revalidation | `3953aa75e98f24a093a68b200d75314a5a19951f` | `41f5b4eb4c3d553ea1e6b3c1566153541ecc74ad3468f7dfe281f3e354165bf3` |
| EV-012 | Existing Evidence Record; local read and digest revalidation | `3953aa75e98f24a093a68b200d75314a5a19951f` | `c14ff1a7508af23259f498b6d0a5305f9f3f7bde94892e933b7d526ee20f6be5` |
| EV-013 | Existing Evidence Record; local read and digest revalidation | `3953aa75e98f24a093a68b200d75314a5a19951f` | `ed20b516270839d8ce24561548de0c345a9fb28e7cc76312aa9e4e65e8f3d56b` (matches prior recorded digest — unchanged) |
| EV-070 | Existing Evidence Record; local read and digest revalidation | `3953aa75e98f24a093a68b200d75314a5a19951f` | `7970e6e159cbf2de454c986d44af830fab65ef915066dc9b5b746d04e55bae16` |
| EV-073 | Existing Evidence Record; local read and digest revalidation | `3953aa75e98f24a093a68b200d75314a5a19951f` | `5e98e29ffda20ac4fb87d50b0eeea5abb45e2963e570a08a0e9c2627465f8b30` (matches prior recorded digest — unchanged) |
| EV-078 | Controlled repository path; local read; new Evidence Record | `3953aa75e98f24a093a68b200d75314a5a19951f` | `c79385ffba6698dfe77959a2331799e017ef6b89c5cb55965a601474b13946f9` |
| EV-079 | Controlled repository path; local read; new Evidence Record | `3953aa75e98f24a093a68b200d75314a5a19951f` | `1630eb575de4716b7a97061f780478a4851cbdf2ec77fe04376094868f054263` |

Access treatment for every source is `Repository`. No copy, transformation, excerpt file, or derivative evidence artefact was created.

## 6. D2 Admissibility Tests

| Evidence | Identity | Provenance | Integrity | Authority | Relevance | Temporal Applicability | Accessibility | Conflict Treatment | Uncertainty | Permitted Use |
|---|---|---|---|---|---|---|---|---|---|---|
| EV-009 | Pass | Pass | Pass | Pass — attributable Founder record | Pass — a scoped, dated architectural decision with no stated distinct effective date | Pass as a 2026-07-24 snapshot | Pass | No source contradiction identified | One early decision; does not establish that later decisions follow the same pattern | Pass |
| EV-010 | Pass | Pass | Pass | Pass — attributable Founder record | Pass — a scoped pilot-recognition decision with no stated distinct effective date | Pass as a 2026-07-24 snapshot | Pass | No source contradiction identified | One decision; does not establish a general rule | Pass |
| EV-012 | Pass | Pass | Pass | Pass — controlled record | Pass — direct; contains OQ-017's exact wording | Pass — 23-question baseline, unchanged | Pass | No source contradiction identified | OQ-017 remains open; its presence is evidence of an unresolved question, not an answer | Pass |
| EV-013 | Pass | Pass | Pass | Limited — non-authoritative draft | Pass — contextual; the one instrument OQ-017 names | Pass | Pass | Draft status does not conflict with approved instruments because no approval is claimed | Not yet approved; has no effective date because it has not taken effect | Pass within limitation |
| EV-070 | Pass | Pass | Pass | Pass — attributable Founder Decision | Pass — establishes mandatory traceability as a controlling requirement, relevant to version-at-decision preservation | Pass as a 2026-07-26 disposition | Pass | No source contradiction identified | Establishes a traceability requirement; does not itself state a transitional-applicability rule | Pass |
| EV-073 | Pass | Pass | Pass | Pass — validated D3 operational record | Pass — direct operated example of version-stamped RQ/Evidence/Pack/Session/Finding/Decision chains | Pass as a 2026-07-28 D3-closure snapshot | Pass | No source contradiction identified | One domain's traceability example; does not establish a cross-instrument model | Pass |
| EV-078 | Pass | Pass | Pass | Pass — attributable governance-recovery record | Pass — direct, operated example of prior in-progress work (an unauthorised RQ admission and evidence registration) being retrospectively treated as not validly having occurred, while preserved for audit | Pass as a 2026-07-25 correction snapshot | Pass | The correction itself is the resolution of a prior conflict; no residual contradiction in this record | This is a correction of an unauthorised action, not an ordinary amendment of a validly approved instrument; the two categories are not distinguished by this evidence set | Pass |
| EV-079 | Pass | Pass | Pass | Pass — attributable correction record with its own Correction Notice | Pass — direct, operated example of a document's own prior claim (D3 "formally closed") being found inaccurate and corrected, without deleting the original artefact | Pass as a 2026-07-25 correction snapshot | Pass | The v1.0/v1.1 relationship is itself the disclosed correction; not a contradiction requiring further resolution here | A second, independent correction example, distinct in kind from EV-078 (a narrative/status claim rather than a register admission action) | Pass |

## 7. Qualification Dispositions

### EV-009 — FEF-FAR-001

**Class:** E1. **Disposition:** Admitted. **Permitted use:** as one example of a scoped, dated Founder architectural decision that does not itself declare a distinct effective date or explicit transitional rule. It does not establish that no FEF decision ever has an effective date, only that this one does not.

### EV-010 — FEF-FAR-002

**Class:** E1. **Disposition:** Admitted. **Permitted use:** as a second example of the same pattern — a scoped, dated Founder decision (pilot recognition) without a stated distinct effective date.

### EV-012 — Open Questions Register

**Class:** E2. **Disposition:** Admitted. **Permitted use:** the exact, unaltered wording of OQ-017 as the one existing open question that already poses a version of RQ-033 for one specific instrument. Its open, unresolved status is controlling.

### EV-013 — FEF-RGS-000

**Class:** E2. **Disposition:** Conditionally Admitted. **Permitted use:** its own header status ("Draft v0.2 — Founder Review Required; not approved") as the reason OQ-017 remains unanswerable in practice — an unapproved instrument has not yet taken effect, so the retrospective/prospective question is not yet live for it. No proposed content is treated as current authority.

### EV-070 — FD-015 Evidence Traceability and Controlled Reuse

**Class:** E1. **Disposition:** Admitted. **Permitted use:** the attributable Founder decision establishing mandatory traceability and controlled reuse as enduring requirements, relevant to whether the review preserves which version of an instrument governed a decision. It does not itself state a transitional-applicability rule.

### EV-073 — D3 Traceability Register

**Class:** E4. **Disposition:** Admitted. **Permitted use:** an operated example of version-stamped, end-to-end traceability (RQ → Evidence → Pack → Session → Finding → Decision) as it existed at D3 closure. It demonstrates that version-at-decision information is preserved in at least one domain; it does not establish that this is a universal or approved requirement outside D3.

### EV-078 — D3 Quarantine Manifest

**Class:** E1. **Disposition:** Admitted. **Permitted use:** a direct, attributable example of a corrective action that treated prior in-progress work (an unauthorised canonical-RQ admission and evidence registration) as if it had not validly occurred, restoring the review to its last Founder-authorised boundary, while preserving the affected artefacts unchanged for audit rather than deleting them. This is one operated example of retrospective correction, not a declared general transitional rule, and it corrects an unauthorised action rather than amending a validly approved instrument.

### EV-079 — D3-C1 Corrected Closure Assessment

**Class:** E1. **Disposition:** Admitted. **Permitted use:** a second, independent example of the same pattern applied to a narrative/status claim rather than a register-admission action: a document's own v1.0 claim ("D3 formally closed") was found inconsistent with controlling rules and corrected to v1.1 with an explicit Correction Notice, without deleting or renumbering the original artefact identity. It demonstrates that a document's own prior assertion can be treated as never having been accurate, while the record itself remains preserved and traceable.

## 8. Qualification Totals

| Disposition | Count |
|---|---:|
| Admitted | 7 |
| Conditionally Admitted | 1 |
| Context Only | 0 |
| Rejected | 0 |
| Total | 8 |

Evidence class constrains permitted use but does not determine weight. No ranking, score, or substantive conclusion is produced by this qualification.

## 9. Limitations, Conflicts, and Gaps

### 9.1 Limitations

- EV-009 and EV-010 are each a single, early-stage Founder decision; neither establishes that all Founder decisions omit an effective date, only that these two do.
- EV-012 documents an open, unresolved question; it does not answer RQ-033 or OQ-017.
- EV-013 is research-specific, not approved, and has not yet taken effect; its applicability question remains hypothetical.
- EV-070 and EV-073 evidence traceability practice, not a transitional-applicability rule.
- EV-078 and EV-079 are each a correction of an identified defect (an unauthorised action; an inaccurate narrative claim), not an ordinary amendment of a validly approved, currently-effective instrument. Whether the same retrospective treatment would apply to an ordinary amendment is not evidenced either way.
- All qualification and validation in this loop is performed by the same combined acting capacity; no independent evidence validation exists.

### 9.2 Conflicts and Conflation Risks (Preserved, Not Resolved)

- **Retrospective correction has been practised, at least twice (EV-078, EV-079), for defects and inaccurate claims** — this is directly relevant to RQ-033's "does it apply retrospectively" question, but both examples are corrections of error, not amendments of a valid, already-effective instrument. Whether the review would apply the *same* retrospective treatment to an ordinary, non-defective amendment is not evidenced either way, and this record does not assume it would.
- **No source distinguishes "effective date" from "approval date," "record date," or "decision date."** Every qualified source that carries a date (EV-009, EV-010, EV-070, EV-073, EV-078, EV-079) uses a single date field for all of these purposes. Whether this is a deliberate simplification or an unaddressed gap is left open.
- **No source documents an ordinary amendment of a still-valid instrument with explicit "grandfather" or transitional treatment for work already underway under the prior version.** The two closest analogues (EV-078, EV-079) both involve correcting something that was found invalid or inaccurate from the outset, not changing something that was valid and is now being updated.
- **No source documents a delegated (non-Founder) determination of a transitional or effective-date question**, consistent with the same gap already disclosed for RQ-032 (FEF-FGR-002-D5-RQ032-EMQR-001 §9.2).

### 9.3 Evidence Gaps

| Gap | Classification | Treatment |
|---|---|---|
| No approved FEF instrument or decision expressly states an effective date distinct from its approval/record date | Material and directly relevant | Preserve for examination; do not infer that no such distinction is intended |
| No operated example exists of an ordinary (non-corrective) amendment to a validly approved, already-effective instrument, with explicit transitional treatment for work already underway | Material and directly relevant | Preserve as an untested scenario; do not extrapolate from the two available correction examples |
| Whether the review's practised retrospective-correction pattern (EV-078, EV-079) would extend to ordinary amendments is unresolved | Material and directly relevant | Preserve as a conflation risk for examination, not resolved here |
| No source documents a delegated (non-Founder) transitional determination | Material and directly relevant | Preserve as an open question; absence is not evidence that delegation cannot or does not occur |
| Observed sources demonstrate current repository practice but do not establish its completeness, necessity, or sufficiency | Manageable limitation | Permit later evidence-bounded comparison; do not convert practice into policy |
| No independent qualification pass | Assurance limitation | Disclose; retain hashes, exact paths, and deterministic reconciliation as compensating controls |

These gaps do not prevent mobilisation and qualification. They remain unresolved inputs to later pack-readiness and examination gates.

## 10. Registration and RQ Mapping

- Existing Evidence Records reused: EV-009, EV-010, EV-012, EV-013, EV-070, EV-073.
- New Evidence Records registered: EV-078, EV-079.
- Related Review Question: RQ-033 only.
- RQ-032 mapping: unchanged (see FEF-FGR-002-D5-RQ032-EMQR-001).
- RQ-034 through RQ-037 mapping: none.
- Evidence Pack membership: none.
- Session, examination, GF, and FD linkage: none.

## 11. RQ-033 Lifecycle Effect

| State Item | State After Loop 002 |
|---|---|
| RQ-032 | Unchanged — Evidence Mobilised and Qualified with Conditions |
| RQ-033 lifecycle state | Admitted — unchanged |
| RQ-033 evidence state | **Evidence Mobilised — Qualified with Conditions; Not Packed; Not Examined** |
| RQ-034 through RQ-037 | Unchanged — Evidence Mobilisation Not Started |
| D5 Evidence Pack | Not assembled or frozen |
| D5 session / examination | Not created / not commenced |

## 12. Non-Effects

This record does not assemble or freeze an Evidence Pack, create a session, examine or answer RQ-033, reinterpret or amend RQ-032, mobilise evidence for RQ-034 through RQ-037, produce a Governance Finding, prepare a Founder Decision, resolve OQ-017, establish a retrospective or prospective transitional rule, apply any transition rule to FEF-RGS-000 or any other instrument, amend or supersede an existing instrument, evaluate FEF-FEV-001-FEC-001 or FEF-CCF-001, disposition CE1–CE6, amend constitutional governance, or commence D6 or D7.
