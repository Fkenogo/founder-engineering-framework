# FEF-FGR-002-D5-RQ036-EMQR-001 — RQ-036 Evidence Mobilisation and Qualification Record

| Control Field | Recorded Value |
|---|---|
| Record identifier | FEF-FGR-002-D5-RQ036-EMQR-001 |
| Review identifier | FEF-FGR-002 |
| Domain | D5 — Governance Lifecycle and Evolution |
| Execution loop | 005 |
| Review Question | FEF-FGR-002-RQ-036 only |
| Record version | 1.0 |
| Acquisition and qualification date | 2026-07-30 |
| Starting repository baseline | `517551787e47c2e4ad410c428a6ad7bd49648b2e` |
| Preparation capacity | FEF-FGR-002-RA-003 — Review Analyst |
| Evidence Custodian | FEF-FGR-002-RA-005 |
| Validator | FEF-FGR-002-RA-006 — non-independent combination disclosed |
| Candidate sources assessed | 6 |
| Existing Evidence Records reused | 5 |
| New Evidence Records registered | 1 |
| Evidence Pack effect | None |
| Examination effect | None |
| Status | **Evidence Mobilised — Qualified with Conditions; Not Packed; Not Examined** |

## 1. Entry Gate

The gate was verified before candidate-source identification:

| Entry Condition | Result |
|---|---|
| Branch and repository | Pass — `main`, clean at task start, no staged changes |
| Local/remote synchronization | Pass — `2/0` (local two commits ahead, unpushed, per standing authorization pattern) |
| Merge or rebase | Pass — none in progress |
| D5 mobilisation | Pass — Mobilised — Effective, subject to four Founder conditions |
| D5 Review Question Admission | Pass — Complete |
| RQ-032, RQ-033, RQ-034, RQ-035 | Pass — Admitted; Evidence Mobilised and Qualified with Conditions (unchanged by this loop) |
| RQ-036 | Pass — Admitted; Evidence Mobilisation Not Started |
| RQ-037 | Pass — Admitted; Evidence Mobilisation Not Started; outside this loop |
| D5 Evidence Pack | Pass — no D5 pack exists or is frozen |
| D5 session / examination | Pass — none created or commenced |

## 2. RQ-036 Boundary

### Exact Question

> What exception, deviation, or expiry mechanism, if any, should apply when a governance instrument is temporarily or conditionally departed from, and what distinguishes a bounded exception from controlled evolution of the framework itself?

### Candidate-Set Generic Evidence Guidance (Not a Derived Requirement)

> FD-001 through FD-032 "Conditions" fields as operated examples of bounded exceptions; FEF-FEV-001's own establishment as the intake mechanism for controlled evolution — source-preserved generic classes only.

This generic guidance, inherited from FEF-FGR-002-D5-RQC-001, is a candidate-preparation aid only. It is not treated as an already-derived requirement. Section 3 below derives the actual requirements for this loop independently, using the exact question, purpose, scope, exclusions, and dependencies recorded in FEF-FGR-002-D5-RQS-001.

The search was limited to the four requirement domains identified in Section 3. It did not identify evidence for RQ-037 and did not determine the answer to RQ-036. Consistent with this loop's mandatory exclusion, no evaluation of FEF-FEV-001-FEC-001, FEF-CCF-001, or CE1–CE6 was performed; FEF-FEV-001 material is used only for its structural, mechanism-level status.

## 3. Evidence Requirements for This Loop

| Requirement | Required Source Characteristic | Purpose | Candidate Treatment |
|---|---|---|---|
| D5-RQ036-EVR-001 | A source stating an approved rule for what any exception to a governance instrument must identify, and confirming that an exception cannot delegate Founder decision authority | Establish whether an approved exception model already exists, independent of any single operated example | EV-005 |
| D5-RQ036-EVR-002 | Sources exposing an operated example of the "Accept with Conditions" / "Approve with Conditions" disposition pattern as a bounded, conditional departure from a strict outcome | Test what a bounded exception actually looks like in this repository's own operated practice | EV-066, EV-074 |
| D5-RQ036-EVR-003 | A source confirming that authority to grant an exception is exercised by a specific reserved capacity and cannot be exercised by implication or operational role | Establish who must approve an exception, mirroring the authority boundary already tested for transitions in RQ-035 | EV-017 |
| D5-RQ036-EVR-004 | A source exposing the exact existing open question already posing a version of this exception/expiry question, and a source exposing the existing structural mechanism established for controlled evolution of the framework itself | Test the boundary between a bounded exception and controlled evolution without evaluating any specific submitted candidate | EV-012, EV-083 |

No requirement is padded with duplicate sources. The requirements describe the evidence needed for RQ-036 only and do not predetermine an exception, deviation, or expiry model, or a finding.

## 4. Candidate Source Catalogue

| Evidence | Source | Controlled Path | Current Authority / State | Class | Requirement | Candidate Result |
|---|---|---|---|---|---|---|
| EV-005 — reuse | FEF-FGRC-001 Charter | `docs/governance/reviews/FEF-FGRC-001-FOUNDER-GOVERNANCE-REVIEW-CHARTER.md` | Founder approved; Draft v0.1 content approved; §21.3 "Exceptions" rule | E2 | D5-RQ036-EVR-001 | Admitted |
| EV-012 — reuse | FEF-WPK-001 Open Questions Register | `docs/records/work-packages/FEF-WPK-001/FEF-WPK-001-OPEN-QUESTIONS-REGISTER.md` | Controlled record; 23-question baseline; all open | E2 | D5-RQ036-EVR-004 | Admitted |
| EV-017 — reuse | Operational Authority Boundary | `docs/governance/reviews/FEF-FGR-002/FEF-FGR-002-OAB-001-OPERATIONAL-AUTHORITY-BOUNDARY.md` | v1.0; FEF-FGR-002 operational | E2 | D5-RQ036-EVR-003 | Admitted |
| EV-066 — reuse | FEF-FGR-002-FD-011 — Evidence Qualification and Permitted Reliance | `docs/governance/reviews/FEF-FGR-002/FEF-FGR-002-FD-011-EVIDENCE-QUALIFICATION-AND-PERMITTED-RELIANCE.md` | v1.0; Accept with Conditions | E1 | D5-RQ036-EVR-002 | Admitted |
| EV-074 — reuse | FEF-FGR-002 Phase 2 Founder Decision Record | `docs/governance/reviews/FEF-FGR-002/FEF-FGR-002-PHASE-2-FOUNDER-DECISION-RECORD.md` | Recorded — Validation Passed; Approve with Conditions | E1 | D5-RQ036-EVR-002 | Admitted |
| EV-083 — new | FEF-FEV-001 — Framework Evolution Intake Programme Overview | `docs/programme/FEF-FEV-001-FRAMEWORK-EVOLUTION-INTAKE-PROGRAMME-OVERVIEW.md` | Active — Intake Established; Phase 1 — Intake Foundation | E2 | D5-RQ036-EVR-004 | Admitted |

## 5. Provenance and Integrity

| Evidence | Origin / Acquisition Route | Repository Commit | SHA-256 at Qualification |
|---|---|---|---|
| EV-005 | Existing Evidence Record; local read and digest revalidation | `517551787e47c2e4ad410c428a6ad7bd49648b2e` | `e007510ba3eb3a115177522c041bb91284f5f0efe3fdd3f185c7565c09c52d72` (matches prior recorded digest — unchanged) |
| EV-012 | Existing Evidence Record; local read and digest revalidation | `517551787e47c2e4ad410c428a6ad7bd49648b2e` | `c14ff1a7508af23259f498b6d0a5305f9f3f7bde94892e933b7d526ee20f6be5` (matches prior recorded digest — unchanged) |
| EV-017 | Existing Evidence Record; local read and digest revalidation | `517551787e47c2e4ad410c428a6ad7bd49648b2e` | `415f61a8fa11fb2792e1d87c4b0f4a10c60ad242c82b69aefbfdebb17b3b94e6` (matches prior recorded digest — unchanged) |
| EV-066 | Existing Evidence Record; local read and digest revalidation | `517551787e47c2e4ad410c428a6ad7bd49648b2e` | `1e3eb7286f6a07a38ee1c3bf4259bea0a755c64dd133ddd65204b788bfdee7f4` |
| EV-074 | Existing Evidence Record; local read and digest revalidation | `517551787e47c2e4ad410c428a6ad7bd49648b2e` | `c2755fa642c6ae0854a618aa0cc0e85f237bd60f91982125aa7415d1688e3aa5` (matches prior recorded digest — unchanged) |
| EV-083 | Controlled repository path; local read; new Evidence Record | `517551787e47c2e4ad410c428a6ad7bd49648b2e` | `b2689e9821d54612354202e9af9e4ec212a7aec5afabfebe2d80f72b7ecebfd4` |

Access treatment for every source is `Repository`. No copy, transformation, excerpt file, or derivative evidence artefact was created.

EV-066's D3-era register row records its integrity only as "Repository-committed `9b0f23e`" (a commit-hash-based control), not a printed SHA-256 value — a formatting practice distinct from both the D1-era "SHA-256 reverified" disclosure (seen for EV-005 and EV-017 before Execution Loop 004) and the D4/D5-era literal-digest convention. This loop is the first to record a literal SHA-256 digest for EV-066. This is disclosed as a pre-existing register-formatting observation, not a new gap, and does not imply the source's content has changed.

## 6. D2 Admissibility Tests

| Evidence | Identity | Provenance | Integrity | Authority | Relevance | Temporal Applicability | Accessibility | Conflict Treatment | Uncertainty | Permitted Use |
|---|---|---|---|---|---|---|---|---|---|---|
| EV-005 | Pass | Pass | Pass | Pass — Founder approved | Pass — §21.3 states every exception must identify clause, reason, scope, duration, risks, compensating controls, approval authority, and "expiry or review trigger," and that "an exception cannot delegate Founder decision authority" | Pass — unchanged since original qualification | Pass | No source contradiction identified | §21.3 is scoped to exceptions from *this Charter*, not stated as a general rule for every FEF governance instrument | Pass |
| EV-012 | Pass | Pass | Pass | Pass — controlled record | Pass — direct; contains OQ-012's exact wording | Pass — 23-question baseline, unchanged | Pass | No source contradiction identified | OQ-012 remains open and is scoped to research standards specifically; its presence is evidence of an unresolved question, not an answer | Pass |
| EV-017 | Pass | Pass | Pass | Pass — FEF-FGR-002 operational, admitted | Pass — states "Founder Decision Authority... Founder only... Cannot be exercised by implication or operational role" | Pass — v1.0, unchanged | Pass | No source contradiction identified | States the general authority-layer boundary; does not name exception-granting specifically | Pass |
| EV-066 | Pass | Pass | Pass | Pass — E1, direct attributable Founder Decision | Pass — direct operated example: an "Accept with Conditions" disposition attaching specific, named conditions to an otherwise-binding position | Pass — v1.0, unchanged | Pass | No source contradiction identified | A conditioned acceptance of a governance-finding disposition; not itself framed as an "exception" to a named clause in the EV-005 §21.3 sense | Pass |
| EV-074 | Pass | Pass | Pass | Pass — E1, direct attributable Founder Decision | Pass — direct operated example: an "Approve with Conditions" disposition at Phase-2-milestone scope | Pass — unchanged since D4 qualification | Pass | No source contradiction identified | Same limitation as EV-066: a conditioned approval, not an exception invoking a named clause | Pass |
| EV-083 | Pass | Pass | Pass | Pass — Founder-authorised programme record; explicit authority boundary | Pass — direct, on-point example: "Active — Intake Established," "Authority boundary: Intake mechanism only; no framework amendment; no constitutional effect," used strictly for its structural/mechanism status | Pass — observed at its current recorded state (2026-07-29 established, unchanged) | Pass | No source contradiction identified | Used only as a mechanism-level structural fact; no candidate routed through it (FEF-FEV-001-FEC-001) is evaluated or dispositioned here | Pass |

## 7. Qualification Dispositions

### EV-005 — FEF-FGRC-001 Charter

**Class:** E2. **Disposition:** Admitted. **Permitted use:** its §21.3 "Exceptions" clause — the required elements of any exception (clause, reason, scope, duration, risks, compensating controls, approval authority, expiry or review trigger) and the explicit statement that "an exception cannot delegate Founder decision authority or permit evidence reconstruction" — as the one existing approved exception model located. Its scope is exceptions to the Charter itself; it is not read as an already-approved, FEF-wide exception standard for every governance instrument.

### EV-012 — Open Questions Register

**Class:** E2. **Disposition:** Admitted. **Permitted use:** the exact, unaltered wording of OQ-012 ("What exception, deviation, expiry, and escalation mechanism applies to research standards?") as the one existing open question closest to RQ-036, scoped to research standards specifically. Its open, unresolved status is controlling.

### EV-017 — Operational Authority Boundary

**Class:** E2. **Disposition:** Admitted. **Permitted use:** its authority-layer table, specifically that Founder Decision Authority is exercised by "Founder only" and "cannot be exercised by implication or operational role," as evidence bearing on who may grant an exception. It does not itself name exception-granting as a category requiring this authority; that connection is left for examination, not asserted here.

### EV-066 — FEF-FGR-002-FD-011

**Class:** E1. **Disposition:** Admitted. **Permitted use:** the operated example of an "Accept with Conditions" Founder Decision — a bounded, conditional disposition attaching named conditions rather than an unconditional grant or refusal. Used only as an example of the review's own conditional-disposition pattern; not treated as an "exception" in the EV-005 §21.3 sense, since it does not invoke a named Charter clause, duration, or expiry trigger.

### EV-074 — FEF-FGR-002 Phase 2 Founder Decision Record

**Class:** E1. **Disposition:** Admitted. **Permitted use:** the operated example of an "Approve with Conditions" disposition at programme-milestone scope, alongside EV-066, to show the same conditional-disposition pattern recurring at a different governance level. Not treated as an exception invoking a named clause.

### EV-083 — FEF-FEV-001 Framework Evolution Intake Programme Overview

**Class:** E2. **Disposition:** Admitted. **Permitted use:** its own status and authority-boundary fields ("Active — Intake Established"; "Authority boundary: Intake mechanism only; no framework amendment; no constitutional effect") as the existing structural mechanism through which controlled evolution of the framework itself is channelled, distinct from a bounded exception to a single instrument. Used strictly as a mechanism-level fact; no submitted candidate is evaluated.

## 8. Qualification Totals

| Disposition | Count |
|---|---:|
| Admitted | 6 |
| Conditionally Admitted | 0 |
| Context Only | 0 |
| Rejected | 0 |
| Total | 6 |

Evidence class constrains permitted use but does not determine weight. No ranking, score, or substantive conclusion is produced by this qualification.

## 9. Limitations, Conflicts, and Gaps

### 9.1 Limitations

- EV-005's exception rule is scoped to exceptions from the Charter itself, not stated as a general FEF-wide rule.
- EV-012's open question is scoped to research standards, not all FEF governance instruments.
- EV-017 states a general authority boundary without naming exception-granting specifically.
- EV-066 and EV-074 are conditioned-disposition examples, not operated examples of an "exception" invoking a named clause, duration, or expiry trigger in the EV-005 §21.3 sense.
- EV-083 establishes only that a controlled-evolution intake mechanism exists; it does not itself state what distinguishes a "bounded exception" from "controlled evolution."
- All qualification and validation in this loop is performed by the same combined acting capacity; no independent evidence validation exists.

### 9.2 Conflicts and Conflation Risks (Preserved, Not Resolved)

- **No source reconciles EV-005's exception model (clause-specific, duration-bound, expiry-triggered) with the "Accept with Conditions" / "Approve with Conditions" disposition pattern observed in EV-066 and EV-074.** Whether the latter are a distinct governance mechanism from an "exception," an informal variant of one, or something else entirely is not addressed by any source.
- **No source states what distinguishes a "bounded exception" from "controlled evolution of the framework itself."** EV-083 shows that a controlled-evolution mechanism (FEF-FEV-001) exists as a structural fact, and EV-005 shows that a Charter-specific exception model exists, but no source draws the line between the two, or states which one applies when a departure could plausibly be characterized as either.
- **No operated example exists of an exception granted under the EV-005 §21.3 model** (naming a specific clause, duration, and expiry or review trigger); every conditioned-disposition example located (EV-066, EV-074) omits at least a stated duration and expiry trigger.
- **No source states whether an exception, once its stated duration or expiry trigger passes, is enforced automatically or requires an affirmative closing action.**

### 9.3 Evidence Gaps

| Gap | Classification | Treatment |
|---|---|---|
| No source reconciles the Charter's clause-specific exception model with the observed "Accept/Approve with Conditions" disposition pattern | Material and directly relevant | Preserve for examination; do not infer equivalence |
| No source states what distinguishes a bounded exception from controlled evolution of the framework itself | Material and directly relevant | Preserve as the central open question for examination |
| No operated example exists of an exception naming a specific clause, duration, and expiry or review trigger | Material and directly relevant | Preserve as an untested scenario |
| No source addresses enforcement of an exception's expiry (automatic vs. affirmative closing action) | Manageable limitation | Preserve as an open question |
| No independent qualification pass | Assurance limitation | Disclose; retain hashes, exact paths, and deterministic reconciliation as compensating controls |

These gaps do not prevent mobilisation and qualification. They remain unresolved inputs to later pack-readiness and examination gates.

## 10. Registration and RQ Mapping

- Existing Evidence Records reused: EV-005, EV-012, EV-017, EV-066, EV-074.
- New Evidence Records registered: EV-083.
- Related Review Question: RQ-036 only.
- RQ-032, RQ-033, RQ-034, RQ-035 mapping: unchanged (see their respective EMQR records).
- RQ-037 mapping: none.
- Evidence Pack membership: none.
- Session, examination, GF, and FD linkage: none.
- FEF-FEV-001-FEC-001, FEF-CCF-001, CE1–CE6: not evaluated or dispositioned; EV-083 is used only for FEF-FEV-001's own structural, mechanism-level status.

## 11. RQ-036 Lifecycle Effect

| State Item | State After Loop 005 |
|---|---|
| RQ-032, RQ-033, RQ-034, RQ-035 | Unchanged — Evidence Mobilised and Qualified with Conditions |
| RQ-036 lifecycle state | Admitted — unchanged |
| RQ-036 evidence state | **Evidence Mobilised — Qualified with Conditions; Not Packed; Not Examined** |
| RQ-037 | Unchanged — Evidence Mobilisation Not Started |
| D5 Evidence Pack | Not assembled or frozen |
| D5 session / examination | Not created / not commenced |

## 12. Non-Effects

This record does not assemble or freeze an Evidence Pack, create a session, examine or answer RQ-036, reinterpret or amend RQ-032 through RQ-035, mobilise evidence for RQ-037, produce a Governance Finding, prepare a Founder Decision, amend or renumber any existing instrument, activate or draft FRAS, evaluate FEF-FEV-001-FEC-001 or FEF-CCF-001, disposition CE1–CE6, amend constitutional governance, or commence D6 or D7.
