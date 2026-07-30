# FEF-FGR-002-D5-RQ034-EMQR-001 — RQ-034 Evidence Mobilisation and Qualification Record

| Control Field | Recorded Value |
|---|---|
| Record identifier | FEF-FGR-002-D5-RQ034-EMQR-001 |
| Review identifier | FEF-FGR-002 |
| Domain | D5 — Governance Lifecycle and Evolution |
| Execution loop | 003 |
| Review Question | FEF-FGR-002-RQ-034 only |
| Record version | 1.0 |
| Acquisition and qualification date | 2026-07-30 |
| Starting repository baseline | `42de97ed065f44f7e89cf6c32637f0aacaee93df` |
| Preparation capacity | FEF-FGR-002-RA-003 — Review Analyst |
| Evidence Custodian | FEF-FGR-002-RA-005 |
| Validator | FEF-FGR-002-RA-006 — non-independent combination disclosed |
| Candidate sources assessed | 6 |
| Existing Evidence Records reused | 4 |
| New Evidence Records registered | 2 |
| Evidence Pack effect | None |
| Examination effect | None |
| Status | **Evidence Mobilised — Qualified with Conditions; Not Packed; Not Examined** |

## 1. Entry Gate

The gate was verified before candidate-source identification:

| Entry Condition | Result |
|---|---|
| Branch and repository | Pass — `main`, clean at task start |
| Local/remote synchronization | Pass — `0/0` divergence |
| Merge or rebase | Pass — none in progress |
| D5 mobilisation | Pass — Mobilised — Effective, subject to four Founder conditions |
| D5 Review Question Admission | Pass — Complete |
| RQ-032, RQ-033 | Pass — Admitted; Evidence Mobilised and Qualified with Conditions (unchanged by this loop) |
| RQ-034 | Pass — Admitted; Evidence Mobilisation Not Started |
| RQ-035 through RQ-037 | Pass — Admitted; Evidence Mobilisation Not Started; outside this loop |
| D5 Evidence Pack | Pass — no D5 pack exists or is frozen |
| D5 session / examination | Pass — none created or commenced |

## 2. RQ-034 Boundary

### Exact Question

> What versioning and release-state conventions, if any, should apply uniformly across FEF governance instruments, and how does this relate to the version-history practice already separately operated by the Master Programme and individual review records?

### Candidate-Set Generic Evidence Guidance (Not a Derived Requirement)

> Master Programme's own `v0.NN` revision log; FEF-RGS-000's `Draft v0.2` field; FEF-FGR-002 register version-field practice — source-preserved generic classes only.

This generic guidance, inherited from FEF-FGR-002-D5-RQC-001, is a candidate-preparation aid only. It is not treated as an already-derived requirement. Section 3 below derives the actual requirements for this loop independently, using the exact question, purpose, scope, exclusions, and dependencies recorded in FEF-FGR-002-D5-RQS-001.

The search was limited to the four requirement domains identified in Section 3. It did not identify evidence for RQ-035 through RQ-037 and did not determine the answer to RQ-034.

## 3. Evidence Requirements for This Loop

| Requirement | Required Source Characteristic | Purpose | Candidate Treatment |
|---|---|---|---|
| D5-RQ034-EVR-001 | A source exposing programme-level versioning practice as actually operated | Establish what a "programme-level" version convention looks like in practice, using the single clearest operated example | EV-080 |
| D5-RQ034-EVR-002 | Sources exposing register-level versioning practice, including whether an overall register version and independent per-item version fields coexist | Test whether the review's own registers operate a dual-axis versioning model (register version plus per-entry version) and whether that model is documented anywhere as a rule | EV-073, EV-081 |
| D5-RQ034-EVR-003 | Sources exposing document/instrument-level versioning outside the review's own machinery, including a mixed-format index across many document types | Test whether draft standards and other instruments use a materially different versioning convention from the review's own registers, and whether the repository already discloses that fragmentation anywhere | EV-013, EV-072 |
| D5-RQ034-EVR-004 | The exact existing Open Question already posing a version of this question | Preserve the one directly on-point existing question without treating it as resolved | EV-012 |

No requirement is padded with duplicate sources. The requirements describe the evidence needed for RQ-034 only and do not predetermine a versioning convention, release-state model, or finding.

## 4. Candidate Source Catalogue

| Evidence | Source | Controlled Path | Current Authority / State | Class | Requirement | Candidate Result |
|---|---|---|---|---|---|---|
| EV-012 — reuse | FEF-WPK-001 Open Questions Register | `docs/records/work-packages/FEF-WPK-001/FEF-WPK-001-OPEN-QUESTIONS-REGISTER.md` | Controlled record; 23-question baseline; all open | E2 | D5-RQ034-EVR-004 | Admitted |
| EV-013 — reuse | FEF-RGS-000 Research Governance Standard | `docs/governance/research/FEF-RGS-000-RESEARCH-GOVERNANCE-STANDARD.md` | Draft v0.2; Founder Review Required; Not Approved | E2 | D5-RQ034-EVR-003 | Conditionally Admitted |
| EV-072 — reuse | FEF Document Manifest | `docs/programme/FEF-DOCUMENT-MANIFEST.md` | Draft; non-authoritative document index; continuously updated | E2 | D5-RQ034-EVR-003 | Conditionally Admitted |
| EV-073 — reuse | D3 Governance Assurance Traceability Register | `docs/governance/reviews/FEF-FGR-002/FEF-FGR-002-D3-TRACEABILITY-REGISTER.md` | v1.1; D3 Closed; DG-6 Complete | E4 | D5-RQ034-EVR-002 | Admitted |
| EV-080 — new | FEF Master Programme | `docs/programme/FEF-MASTER-PROGRAMME.md` | v0.58 at acquisition; append-only revision log since v0.20 | E2 | D5-RQ034-EVR-001 | Admitted |
| EV-081 — new | FEF-FGR-002 Review Question Register | `docs/governance/reviews/FEF-FGR-002/FEF-FGR-002-REVIEW-QUESTION-REGISTER.md` | v1.46 at acquisition; dual-axis register/per-RQ versioning | E4 | D5-RQ034-EVR-002 | Admitted |

EV-081's observed state is fixed at this loop's acquisition point (register version v1.46, before this loop's own RQ-034 row update). Its subsequent update to v1.47 by this same loop (Section 10) is a normal, disclosed register-maintenance action, not evidence tampering: the source is cited for its already-existing dual-axis versioning *structure*, which this loop's own edit does not change.

## 5. Provenance and Integrity

| Evidence | Origin / Acquisition Route | Repository Commit | SHA-256 at Qualification |
|---|---|---|---|
| EV-012 | Existing Evidence Record; local read and digest revalidation | `42de97ed065f44f7e89cf6c32637f0aacaee93df` | `c14ff1a7508af23259f498b6d0a5305f9f3f7bde94892e933b7d526ee20f6be5` (matches prior recorded digest — unchanged) |
| EV-013 | Existing Evidence Record; local read and digest revalidation | `42de97ed065f44f7e89cf6c32637f0aacaee93df` | `ed20b516270839d8ce24561548de0c345a9fb28e7cc76312aa9e4e65e8f3d56b` (matches prior recorded digest — unchanged) |
| EV-072 | Existing Evidence Record; local read and digest revalidation | `42de97ed065f44f7e89cf6c32637f0aacaee93df` | `543ec7643017f6a2e8fc4bd2eb5a4681e1056814786049b0d63b1296a4a99a98` (**changed** again since its D5-RQ032-era observation, consistent with its disclosed mutable-index limitation) |
| EV-073 | Existing Evidence Record; local read and digest revalidation | `42de97ed065f44f7e89cf6c32637f0aacaee93df` | `5e98e29ffda20ac4fb87d50b0eeea5abb45e2963e570a08a0e9c2627465f8b30` (matches prior recorded digest — unchanged) |
| EV-080 | Controlled repository path; local read; new Evidence Record | `42de97ed065f44f7e89cf6c32637f0aacaee93df` | `7f4e7edfeeb7768f8822e9599ac92c0f082061562279f752544bbf123aee97b0` |
| EV-081 | Controlled repository path; local read; new Evidence Record | `42de97ed065f44f7e89cf6c32637f0aacaee93df` | `f25d51c0785c565613123d2a8eeb762fb7ddf6e86009f0772a46721a5c0b77f5` |

Access treatment for every source is `Repository`. No copy, transformation, excerpt file, or derivative evidence artefact was created. EV-080 and EV-081 are themselves live, continuously-updated controlled programme/register documents (as EV-072 already is); their qualification is bounded strictly to their state at the commit identified above, not to any later state.

## 6. D2 Admissibility Tests

| Evidence | Identity | Provenance | Integrity | Authority | Relevance | Temporal Applicability | Accessibility | Conflict Treatment | Uncertainty | Permitted Use |
|---|---|---|---|---|---|---|---|---|---|---|
| EV-012 | Pass | Pass | Pass | Pass — controlled record | Pass — direct; contains OQ-014's exact wording | Pass — 23-question baseline, unchanged | Pass | No source contradiction identified | OQ-014 remains open; its presence is evidence of an unresolved question, not an answer | Pass |
| EV-013 | Pass | Pass | Pass | Limited — non-authoritative draft | Pass — its own `Draft v0.2` label is a direct instrument-level versioning example | Pass | Pass | No source contradiction identified | Has never been approved, so whether its numbering would change on approval is untested | Pass within limitation |
| EV-072 | Pass | Pass | Pass | Limited — non-authoritative index | Pass — direct evidence of a mixed versioning vocabulary across many document types as currently listed | Pass — observed 2026-07-30 state | Pass | Source records control if an index entry conflicts | Digest has changed twice since first qualified for D4; index is mutable and non-authoritative | Pass within limitation |
| EV-073 | Pass | Pass | Pass | Pass — validated D3 operational record | Pass — direct example of a register carrying its own header version distinct from the source records it traces | Pass as a 2026-07-28 D3-closure snapshot | Pass | No source contradiction identified | One domain's register example; does not establish a universal model | Pass |
| EV-080 | Pass | Pass | Pass | Pass — Founder-authorised controlling programme record | Pass — direct, primary example of programme-level versioning (`v0.NN`, append-only revision log per change) | Pass — observed at v0.58 | Pass | No source contradiction identified | Documents its own history exhaustively but does not state a rule for when the second decimal versus a hypothetical first decimal would change | Pass |
| EV-081 | Pass | Pass | Pass | Pass — validated FEF-FGR-002 operational register | Pass — direct example of a dual-axis model: one "Register version" field (`v1.46`) governing the whole document, and independent per-row "Version" fields (e.g., RQ-032 `v1.1`) governing individual entries | Pass — observed at v1.46, immediately before this loop's own RQ-034 addition | Pass | No source contradiction identified | Coexistence of the two axes is not itself explained or justified anywhere in the register | Pass |

## 7. Qualification Dispositions

### EV-012 — Open Questions Register

**Class:** E2. **Disposition:** Admitted. **Permitted use:** the exact, unaltered wording of OQ-014 ("What versioning, release-state, effective-date, and withdrawal model applies to research standards?") as the one existing open question closest to RQ-034, scoped to research standards specifically. Its open, unresolved status is controlling.

### EV-013 — FEF-RGS-000

**Class:** E2. **Disposition:** Conditionally Admitted. **Permitted use:** its own header field (`Draft v0.2`) as one operated example of instrument-level versioning outside the review's own registers. No proposed content is treated as current authority.

### EV-072 — FEF Document Manifest

**Class:** E2. **Disposition:** Conditionally Admitted. **Permitted use:** evidence of the range of version/status notation actually observed across document categories at the qualified date (e.g., "Current v0.58", "Active v1.46", "Draft v0.2", "Pilot v0.1", unnumbered "Candidate — Not Authored"). The index is non-authoritative and mutable; its digest has changed on each prior D4/D5 observation, and controlling source records prevail over any Manifest entry.

### EV-073 — D3 Traceability Register

**Class:** E4. **Disposition:** Admitted. **Permitted use:** an operated example of a controlled register carrying its own overall version field, distinct from the version state of the individual records it traces. It demonstrates the dual-axis pattern in one domain; it does not establish that this is a universal or approved requirement.

### EV-080 — FEF Master Programme

**Class:** E2. **Disposition:** Admitted. **Permitted use:** the primary, attributable example of programme-level versioning — an append-only log where each substantive change is recorded as a new `v0.NN` entry with its own dated narrative paragraph (Section 10). It does not itself state a rule for numbering scope, digit meaning, or when a version would ever be reset, retired, or reused.

### EV-081 — FEF-FGR-002 Review Question Register

**Class:** E4. **Disposition:** Admitted. **Permitted use:** the primary, attributable example of register-level, dual-axis versioning — one "Register version" field governing the document as a whole and independent per-row "Version" fields governing individual Review Questions, observed at its pre-loop state (`v1.46`). It does not itself state a rule reconciling this convention with the Master Programme's single-axis `v0.NN` model or with instrument-level `Draft vX.Y` labels.

## 8. Qualification Totals

| Disposition | Count |
|---|---:|
| Admitted | 4 |
| Conditionally Admitted | 2 |
| Context Only | 0 |
| Rejected | 0 |
| Total | 6 |

Evidence class constrains permitted use but does not determine weight. No ranking, score, or substantive conclusion is produced by this qualification.

## 9. Limitations, Conflicts, and Gaps

### 9.1 Limitations

- EV-012 documents an open, unresolved question scoped to research standards, not all FEF governance instruments.
- EV-013 has never been approved; whether its versioning convention would change upon approval is untested.
- EV-072 is a mutable, non-authoritative index whose digest has now changed on every prior observation (D4-era, D5-RQ032-era, and this loop).
- EV-073 and EV-081 each evidence one register's dual-axis convention; neither establishes that this is a universal or approved model.
- EV-080 documents its own extensive history but states no rule for what its numbering scheme means or when it would change format.
- All qualification and validation in this loop is performed by the same combined acting capacity; no independent evidence validation exists.

### 9.2 Conflicts and Conflation Risks (Preserved, Not Resolved)

- **At least three distinct, uncoordinated versioning conventions are observed side by side**, with no source reconciling them: (a) the Master Programme's single-axis `v0.NN` programme-level log (EV-080); (b) the review's registers' dual-axis "Register version" plus independent per-item "Version" model (EV-073, EV-081); and (c) instrument-level `Draft vX.Y` labels for standards such as FEF-RGS-000 (EV-013). Whether this fragmentation is deliberate (different conventions for different artefact classes) or an unaddressed gap is left open.
- **The Document Manifest (EV-072) mixes all of the above conventions in a single index** (e.g., "Current v0.58", "Active v1.46", "Draft v0.2"), which is itself evidence of the fragmentation rather than a resolution of it.
- **No source states a rule for what a version-number digit means** — for example, whether the Master Programme's `v0.NN` second-decimal increments correspond in any way to the significance implied by a register's or Review Question's `vX.Y` increments. This record does not assume they correspond.
- **No source documents a version number being reset, decremented, or reused after retirement**, at the document-version level. (This is distinct from the already-disclosed permanent-retirement practice for Evidence Record identifiers, e.g., EV-032 through EV-049, which is an identifier-allocation rule, not a document-versioning rule, and is not treated as the same thing here.)

### 9.3 Evidence Gaps

| Gap | Classification | Treatment |
|---|---|---|
| No approved FEF-wide versioning or release-state convention was located | Material and directly relevant | Preserve for examination; do not infer a convention from repository repetition |
| No source reconciles the Master Programme's, the registers', and instrument-level versioning conventions | Material and directly relevant | Preserve as a conflation risk for examination, not resolved here |
| No source states what a version-number digit is intended to signify | Material and directly relevant | Preserve as an open question |
| No operated example exists of a document version number being reset, decremented, or reused | Manageable limitation | Preserve as an untested scenario |
| Observed sources demonstrate current repository practice but do not establish its completeness, necessity, or sufficiency | Manageable limitation | Permit later evidence-bounded comparison; do not convert practice into policy |
| No independent qualification pass | Assurance limitation | Disclose; retain hashes, exact paths, and deterministic reconciliation as compensating controls |

These gaps do not prevent mobilisation and qualification. They remain unresolved inputs to later pack-readiness and examination gates.

## 10. Registration and RQ Mapping

- Existing Evidence Records reused: EV-012, EV-013, EV-072, EV-073.
- New Evidence Records registered: EV-080, EV-081.
- Related Review Question: RQ-034 only.
- RQ-032, RQ-033 mapping: unchanged (see their respective EMQR records).
- RQ-035 through RQ-037 mapping: none.
- Evidence Pack membership: none.
- Session, examination, GF, and FD linkage: none.

## 11. RQ-034 Lifecycle Effect

| State Item | State After Loop 003 |
|---|---|
| RQ-032, RQ-033 | Unchanged — Evidence Mobilised and Qualified with Conditions |
| RQ-034 lifecycle state | Admitted — unchanged |
| RQ-034 evidence state | **Evidence Mobilised — Qualified with Conditions; Not Packed; Not Examined** |
| RQ-035 through RQ-037 | Unchanged — Evidence Mobilisation Not Started |
| D5 Evidence Pack | Not assembled or frozen |
| D5 session / examination | Not created / not commenced |

## 12. Non-Effects

This record does not assemble or freeze an Evidence Pack, create a session, examine or answer RQ-034, reinterpret or amend RQ-032 or RQ-033, mobilise evidence for RQ-035 through RQ-037, produce a Governance Finding, prepare a Founder Decision, resolve OQ-014, establish a versioning or release-state standard, amend or renumber any existing instrument, evaluate FEF-FEV-001-FEC-001 or FEF-CCF-001, disposition CE1–CE6, amend constitutional governance, or commence D6 or D7.
