# FEF-FGR-002-D6-ERC-001 — D6 Evidence Requirement Matrix and Catalogue

| Control Field | Recorded Value |
|---|---|
| Record identifier | FEF-FGR-002-D6-ERC-001 |
| Review identifier | FEF-FGR-002 |
| Domain | D6 — Framework Administration |
| Record class | Evidence requirement matrix and candidate-source catalogue |
| Version | 1.0 |
| Preparation date | 2026-08-05 |
| Preparation capacity | FEF-FGR-002-RA-003 — Review Analyst (with RA-005 Evidence Custodian input) |
| Source RQs | FEF-FGR-002-RQ-038 through FEF-FGR-002-RQ-043 (canonical set FEF-FGR-002-D6-RQS-001) |
| Evidence conclusion effect | None — this record identifies requirements and candidate sources; it does not qualify, admit, or weigh evidence (see FEF-FGR-002-D6-EQR-001) |
| Record status | Prepared |

## 1. Purpose

This record derives the minimum evidence needed for a defensible future
examination of the six admitted D6 Review Questions, and catalogues
candidate sources located by repository search. Consistent with the
Founder's explicit direction for Framework Administration domains, this
matrix favours reuse of already-controlled administrative artefacts over
new evidence, and derives only the requirements genuinely needed to cover
RQ-038 through RQ-043 — not every artefact the Special D6 Guidance lists
as an example. It does not qualify or admit evidence (that is
FEF-FGR-002-D6-EQR-001), does not answer a Review Question, and does not
perform examination.

## 2. Review Question Extraction

Each RQ below is reproduced exactly from FEF-FGR-002-D6-RQS-001. No
wording, scope, exclusion, or dependency was rewritten.

| RQ | Title | Scope (verbatim) | Exclusions (verbatim) | OQ Interface |
|---|---|---|---|---|
| RQ-038 | Administrative Ownership and Stewardship | Ownership and stewardship boundaries for framework-wide administrative artefacts, as distinct from Founder-reserved authority and individual project authority | No owner or steward is assigned; no new role or authority is created; Founder-reserved and project authority boundaries are not altered | OQ-021 partial |
| RQ-039 | Maintenance and Current-State Integrity | Standing maintenance, synchronisation, and verification responsibility for current-state programme and governance control records, framed per Minimum Viable Administration and without presuming a standing verification mechanism | No maintenance procedure, verification tool, or responsibility is designed or adopted; the Single Source of Truth model itself is not redesigned | OQ-014 partial |
| RQ-040 | Programme Sequencing, Dependency Administration, and Release Readiness | Cross-project roadmap, release, and dependency relationships that are genuinely cross-project, refocused onto sequencing, dependency administration, and release readiness | FEF-P0-004 is not dispositioned; OQ-016 is not resolved; no roadmap, release, or delivery rule is adopted for any individual project | OQ-016 direct (administrative consequence only) |
| RQ-041 | Administrative Coherence | Identifier allocation practice, controlled-register state transitions, and document lifecycle/discoverability, refocused toward administrative coherence rather than relational mapping | No document is renumbered, migrated, or reconciled; no identifier-allocation standard is adopted; FEF-RCR-001's completed navigation audit is not reopened | OQ-015 direct (consistency question only) |
| RQ-042 | Simplicity, Reporting, and Proportional Tailoring | The boundary between common FEF-wide administrative practice and individual project administrative discretion | No FEF review machinery is made mandatory project governance; no specific reporting format is adopted; no project's existing practice is judged | None direct |
| RQ-043 | Governance Process for Administrative Practice Maturation | Whether a governance process exists, or should exist, to determine how an operationally demonstrated pattern matures into standing Framework Administration practice, using Single Source of Truth as the first examined example, not the predetermined subject | Does not adopt, generalise, or implement Single Source of Truth beyond its current application; does not amend Framework architecture or perform Framework Evolution | None direct |

## 3. Derived Evidence Requirements

Requirements are consolidated across RQs where the same evidence
genuinely serves more than one question, avoiding duplicative or padded
requirements. Each requirement's "Status" reflects the state as of this
record only — qualification itself is performed in FEF-FGR-002-D6-EQR-001.

| Req ID | Requirement Statement | Purpose | Evidence Class Sought | Preferred Source Type | Candidate Sources (this record) | Related RQs | Status |
|---|---|---|---|---|---|---|---|
| D6-EVR-001 | Current role, authority, and custodianship controls (organisational roles, authority boundary, independence rules, responsibility matrix, role assignment register) must be evidenced before any ownership/stewardship question can be examined | RQ-038 asks what minimum ownership responsibility should exist and who should hold it; the existing controlling role model is the baseline that question must be tested against | E2 — Controlled FEF Record | Repository record (reuse) | FEF-FGR-002-OGRS-001, GRM-001, OAB-001, ICR-001, RAR-001 (EV-016, EV-017, EV-018, EV-019, EV-021, all reuse) | RQ-038 | Located |
| D6-EVR-002 | The current Master Programme, as the Founder-adopted Single Source of Truth and controlling programme-state record, must be evidenced at its current (post-D6-DG-2) state | Directly bears on RQ-038 (custodianship), RQ-039 (maintenance/synchronisation baseline), RQ-040 (dependency/work-package register), and RQ-043 (the operative Single Source of Truth precedent under examination) | E2 | Repository record (reobserve) | FEF-MASTER-PROGRAMME.md (EV-080, reobserve) | RQ-038, RQ-039, RQ-040, RQ-043 | Located |
| D6-EVR-003 | The current Document Manifest, as the repository's non-authoritative document-discoverability index, must be evidenced at its current state | Bears on RQ-038 (document custodianship) and RQ-041 (document lifecycle/discoverability) | E2 | Repository record (reobserve) | FEF-DOCUMENT-MANIFEST.md (EV-072, reobserve) | RQ-038, RQ-041 | Located |
| D6-EVR-004 | The current Review Question Register, as the operated example of identifier allocation and register-state transitions, must be evidenced at its current state | Directly grounds RQ-041's identifier/register-consistency question in an actually-operated register rather than an assumed one | E4 — Technical Evidence | Repository record (reobserve) | FEF-FGR-002-REVIEW-QUESTION-REGISTER.md (EV-081, reobserve) | RQ-041 | Located |
| D6-EVR-005 | The current Founder Dashboard, as the operated example of a "consumer, not controller" programme-control document under the Founder-adopted Single Source of Truth model, must be evidenced | Bears on RQ-038 (which document holds which administrative responsibility), RQ-042 (what is common versus project-specific reporting), and RQ-043 (an operated example of the pattern under examination) | E2 | Repository record (new) | FEF-FOUNDER-DASHBOARD.md (new — see §4) | RQ-038, RQ-042, RQ-043 | Located |
| D6-EVR-006 | The current Review Identity record, as the operated example of a domain-execution-state controlled document whose own Change History documents every maintenance/synchronisation correction performed to date, must be evidenced | Bears on RQ-039 (maintenance/synchronisation responsibility, evidenced by an operated correction history), RQ-041 (a second document-responsibility example), and RQ-043 (a second Single Source of Truth application example) | E2 / E4 | Repository record (new) | FEF-FGR-002-REVIEW-IDENTITY.md (new — see §4) | RQ-039, RQ-041, RQ-043 | Located |
| D6-EVR-007 | The D6 Mobilisation Planning Package's disclosed cross-project dependency table and its repeated ad hoc identifier collision-search disclosure pattern must be evidenced | Directly grounds RQ-040 (residual dependency relationships) and RQ-041 (identifier-allocation practice) in the same disclosure already made at D6 mobilisation, rather than a newly asserted one | E2 | Repository record (new) | FEF-FGR-002-D6-MPP-001 (new — see §4) | RQ-040, RQ-041 | Located |
| D6-EVR-008 | The Founder's own exact rationale and amendment instruction that the Single Source of Truth architecture is "the first examined example... rather than the predetermined subject" must be evidenced verbatim | RQ-043 asks what governance process should determine practice maturation, using Single Source of Truth as the first example; the Founder's own instruction is the controlling authority for that framing and must not be paraphrased from memory | E1 — Attributable Founder Evidence | Repository record (new) | FEF-FGR-002-D6-RQC-FDR-001 (new — see §4) | RQ-043 | Located |
| D6-EVR-009 | The Agenda's "Over-governance" named risk entry must be evidenced as the source of the proportionality question RQ-042 examines | RQ-042 asks what minimum common administrative practice should apply across projects; the Agenda already names excess governance as a risk this candidate was designed to mitigate | E2 | Repository record (reuse) | FEF-FGRA-001 §"Risks" (EV-006, reuse) | RQ-042 | Located |

## 4. New Candidate Sources Not Yet in the Evidence Register

| Candidate | Path | Identifier | Version/State | Related Requirements |
|---|---|---|---|---|
| FEF Founder Dashboard | `docs/programme/FEF-FOUNDER-DASHBOARD.md` | (no independent identifier — Master Programme consumer view) | Current state, 2026-08-05 | D6-EVR-005 |
| FEF-FGR-002 Review Identity | `docs/governance/reviews/FEF-FGR-002/FEF-FGR-002-REVIEW-IDENTITY.md` | FEF-FGR-002 Review Identity | v1.76 | D6-EVR-006 |
| D6 Mobilisation Planning Package | `docs/governance/reviews/FEF-FGR-002/FEF-FGR-002-D6-MOBILISATION-PLANNING-PACKAGE.md` | FEF-FGR-002-D6-MPP-001 | v1.1 — Mobilised, Effective | D6-EVR-007 |
| D6 Founder Candidate Review Disposition Record | `docs/governance/reviews/FEF-FGR-002/FEF-FGR-002-D6-RQC-FOUNDER-CANDIDATE-REVIEW-DISPOSITION-RECORD.md` | FEF-FGR-002-D6-RQC-FDR-001 | v1.0 — Founder Candidate Review Complete | D6-EVR-008 |

## 5. Explicit Gaps

No genuine evidentiary gap was identified for any of the six admitted D6
Review Questions. Every requirement in §3 traces to at least one located
candidate source. This absence of a gap is itself a disclosed finding, not
an assumption: D6's subject matter (Framework Administration) is largely
self-referential to the Framework's own already-controlled administrative
records, all of which are accessible and current, unlike, for example,
D3's RQ-018 (which required evidence of an operated dissent record that
genuinely does not exist anywhere in the repository).

## 6. Proportionality Note

Nine requirements and thirteen candidate sources (nine reused, four new)
cover all six admitted D6 Review Questions — fewer requirements and fewer
sources than any prior domain in this review. This reflects the Founder's
explicit direction that D6's evidence base should be smaller than D5's,
not larger, and that unnecessary new evidence should not be introduced
merely because a controlled artefact exists. Several artefacts named as
illustrative examples in the governing task's Special D6 Guidance
(Session Register, Evidence Register, mobilisation and validation reports
beyond D6-MPP-001 and D6-RQC-FDR-001) were considered and excluded: their
administrative-operation content is already sufficiently evidenced by the
Master Programme, Review Question Register, Document Manifest, Review
Identity, D6-MPP-001, and D6-RQC-FDR-001 reused or newly registered above,
and adding them would not close any requirement gap.

## 7. Non-Effects

This record does not qualify, admit, weigh, or register an Evidence
Record; does not create an Evidence Pack; does not open a session; does
not answer a Review Question; and does not create a Governance Finding or
Founder Decision. Qualification is performed separately in
[FEF-FGR-002-D6-EQR-001](FEF-FGR-002-D6-EQR-001-EVIDENCE-QUALIFICATION-RECORD.md).
