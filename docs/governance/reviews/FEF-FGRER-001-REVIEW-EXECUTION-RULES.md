# FEF-FGRER-001 — Founder Governance Review Execution Rules

**Programme:** Founder Engineering Framework  
**Document identifier:** FEF-FGRER-001  
**Version:** 0.1  
**Status:** Founder Review Draft — Not Approved  
**Work package:** FEF-WPK-001G  
**Parent Plan:** [FEF-FGRP-001](FEF-FGRP-001-FOUNDER-GOVERNANCE-REVIEW-PLAN.md)  
**Review status:** Not Commenced  
**Execution effect:** None until Plan approval and separate Founder commencement

## 1. Purpose

Define the mandatory future execution workflow, decision gates, validation sequence, reopening and iteration controls, dependency handling, escalation, and stop rules for the Founder Governance Review.

These Rules specify future conduct. They do not execute any step.

## 2. Rule Precedence

During future execution:

1. attributable Founder Decisions control within their scope;
2. the approved Charter controls review governance;
3. the approved Agenda controls strategic priorities and sequence;
4. the approved Review Plan controls operations;
5. these Execution Rules control repeatable workflow;
6. approved specifications and templates control their artefact types.

A conflict shall be escalated. Lower-order records shall not silently reinterpret higher-order authority.

## 3. Execution Workflow

### Stage E0 — Founder Commencement

Required future outcomes:

- separate Founder commencement decision;
- review identifier assignment;
- approved instruments and conditions identified;
- Master Programme alignment;
- roles and repositories authorised.

No activity proceeds without E0.

### Stage E1 — Baseline Control

- instantiate empty controlled registers;
- fingerprint the Open Questions baseline;
- create the Evidence Register structure;
- establish change and integrity controls;
- validate no historical content was imported.

### Stage E2 — Review Question Admission

- identify candidate RQs;
- draft neutrally;
- map evidence needs and domains;
- validate;
- admit only questions within scope.

### Stage E3 — Evidence Pack Preparation

- register candidate sources;
- apply admissibility;
- assemble pack;
- validate and freeze;
- map to admitted RQs.

### Stage E4 — Session Entry

- assign future session identifier;
- complete Session Record control fields;
- validate roles, pack, RQs, dependencies, and risks;
- pass or stop.

### Stage E5 — Session Execution

- confirm authority;
- examine evidence;
- record discussion and uncertainty;
- prepare candidate findings;
- present decision-ready questions only at the proper gate;
- capture exact Founder dispositions.

### Stage E6 — Post-Session Control

- complete record;
- validate pack use and traceability;
- validate GFs;
- record and validate FDs;
- update mappings and deferrals;
- prevent downstream reliance until validation passes.

### Stage E7 — Domain Integration

- reconcile terminology and dependencies;
- validate domain coverage;
- update cross-domain and Open Question mappings;
- determine next-domain readiness or reopening.

### Stage E8 — Final Review Assembly

- assemble required artefacts;
- reconcile counts and statuses;
- validate completion criteria;
- prepare Founder final disposition package;
- stop pending Founder decision.

## 4. Decision Gates

| Gate | Decision | Reserved Authority | Required Inputs | Permitted Outcomes |
|---|---|---|---|---|
| DG-0 | Approve Review Plan | Founder | Plan and validation | Approve, condition, return, reject, defer |
| DG-1 | Commence Review and assign identifier | Founder | Approved instruments, Master Programme readiness, commencement package | Commence, condition, return, defer, decline |
| DG-2 | Admit RQ to execution | Review Coordinator under Plan; validation required | RQ record, evidence needs, scope | Admit, return, defer, reject |
| DG-3 | Freeze Evidence Pack | Evidence Custodian and Validator within assigned roles | Pack, manifest, admissibility, integrity | Freeze, return, block |
| DG-4 | Open future session | Assigned session authority after validation | Session entry record | Open, conditional open, block |
| DG-5 | Issue Founder Decision | Founder | Decision question, evidence, validated GF inputs where applicable | Decide, condition, defer, return, decline |
| DG-6 | Exit domain | Review Coordinator with validation | Domain record and traceability | Pass, conditional, return, block |
| DG-7 | Approve final review baseline | Founder | Complete review package and final validation | Approve, condition, partial approval, return, reject, defer |

Gate identifiers are rule labels, not review artefact identifiers or evidence that a gate has occurred.

## 5. Validation Sequence

The required sequence is:

```text
Instrument Validation
        ↓
Commencement Validation
        ↓
RQ Validation
        ↓
Evidence Pack Validation and Freeze
        ↓
Session Entry Validation
        ↓
Session Record Validation
        ↓
GF Validation
        ↓
FD Record Validation
        ↓
Domain Validation
        ↓
Final Review Validation
```

### 5.1 No Validation by Assumption

Validation shall not:

- create missing evidence;
- select an option;
- paraphrase Founder authority;
- resolve a contradiction by preference;
- close an Open Question;
- change lifecycle state without evidence.

### 5.2 Failed Validation

A failed checkpoint:

- records the defect;
- returns the affected artefact or blocks the gate;
- identifies correction authority;
- preserves the failed version;
- requires revalidation.

## 6. Reopening Rules

A previously dispositioned RQ, GF, domain conclusion, session output, or evidence treatment may be reopened only for:

- new material evidence;
- verified evidence error;
- integrity failure;
- attributable Founder direction;
- conflict discovered during integration;
- invalid lifecycle transition;
- scope or authority defect;
- downstream inconsistency.

The reopening record shall state:

- trigger;
- authority;
- affected artefacts;
- preserved prior state;
- new scope;
- evidence changes;
- validation required;
- downstream impact.

An FD may be changed only by a later attributable Founder Decision. Reopening analysis does not suspend or alter an FD automatically.

## 7. Iteration Rules

Iteration is permitted when:

- a later domain reveals an earlier dependency;
- new admitted evidence changes analysis;
- D8 mapping exposes incomplete domain treatment;
- validation returns an artefact;
- the Founder requests reconsideration.

Iteration shall:

- use new versions or linked records;
- preserve identifiers and history;
- avoid duplicate unresolved records;
- update traceability;
- revalidate affected downstream outputs;
- not bypass domain gates.

## 8. Dependency Handling

### 8.1 Dependency States

| State | Meaning | Treatment |
|---|---|---|
| Satisfied | Evidence or authority proves completion | Proceed |
| Conditional | Proceeding is permitted under explicit constraints | Record condition and monitor |
| Unsatisfied | Required input absent | Block dependent activity |
| Deferred | Attributable authority postpones dependency | Record effect and trigger |
| Out of Scope | Another controlled process owns it | Record destination |
| Invalidated | Previously satisfied dependency no longer reliable | Reopen affected work |

### 8.2 No Silent Workaround

An unsatisfied dependency shall not be treated as satisfied through:

- assumption;
- inferred Founder intent;
- placeholder text;
- repeated assertion;
- future promise;
- implementation convenience.

## 9. Escalation Rules

Escalate to the Founder when:

- reserved authority is unclear;
- an FD is required;
- scope expansion is proposed;
- instrument conflicts cannot be resolved administratively;
- a Critical defect affects authority or evidence;
- a risk requires acceptance;
- an exception affects Charter controls;
- an Open Question closure is proposed;
- constitutional treatment is disputed;
- review continuation would exceed authority.

Escalate to the Validator or Evidence Custodian, as applicable, for:

- integrity mismatch;
- provenance gap;
- invalid citation;
- missing mandatory field;
- pack version conflict;
- broken traceability.

## 10. Stop Rules

Affected execution shall stop for:

- absent Founder commencement;
- missing or conflicting review identifier;
- use of an unfrozen pack;
- Critical integrity failure;
- attempted historical reconstruction;
- inability to record exact Founder wording;
- unauthorised session scope;
- proposed constitutional or RGS amendment;
- unauthorised engineering work;
- unresolved confidentiality, legal, security, or privacy prohibition;
- invalid Founder authority claim.

A stop remains until the defect is corrected, bounded away, or dispositioned by the proper authority.

## 11. Decision Recording Rules

When the Founder issues a future decision:

1. capture exact wording;
2. confirm the selected option or directive;
3. record conditions and rationale, or absence of rationale;
4. cite the attributable source;
5. map evidence, RQs, and GFs;
6. record scope and non-effects;
7. validate without changing meaning;
8. obtain correction from the Founder if wording is ambiguous.

Acknowledgement, silence, discussion, or acceptance of a session record is not an FD unless explicitly stated.

## 12. Evidence Change Rules During Examination

- Frozen packs remain immutable.
- New material uses a successor or Supplemental Pack.
- A future session may pause for pack update.
- Post-session evidence triggers impact assessment and possible reopening.
- No participant may introduce uncited evidence as authoritative.

## 13. Open Question Rules

- all 23 baseline questions remain controlled;
- RQ mapping does not change OQ wording;
- GF issuance does not close an OQ;
- only required attributable Founder authority may close it;
- partial answers preserve unresolved remainder;
- deferral records owner and trigger;
- final validation reconciles every status.

## 14. Constitutional Candidate Rules

- candidates arise only after Charter tests;
- they require evidence, validated GF, and FD where authority is required;
- they remain candidates;
- they do not amend the Constitution;
- separate consolidation authority is mandatory;
- rejected and deferred candidates remain traceable.

## 15. Quality and Defect Handling

Use the Plan’s Critical, Major, Minor, and Observation classifications.

- Critical defects stop affected execution.
- Major defects block reliance.
- Minor defects are corrected before final assembly.
- Observations are recorded without inflating them into required governance.

Defect correction shall never rewrite historical records silently.

## 16. Review Change Control

Changes to scope, domain order, required artefacts, or gates require:

- change purpose;
- authority;
- impact assessment;
- Charter and Agenda conformance check;
- version update;
- validation;
- Founder decision where reserved;
- treatment of completed work.

Administrative corrections may follow the approved Plan’s bounded control but must remain traceable.

## 17. Execution Completion

Execution is complete only after:

- every Charter completion criterion is satisfied or explicitly conditioned;
- final validation is complete;
- the Founder dispositions the final review record.

Completion does not authorise constitutional consolidation, RGS amendment, or Engineering Discovery unless the Founder separately states that effect.

## 18. Rules Non-Effects

FEF-FGRER-001 does not:

- approve the Plan;
- commence the review;
- assign an identifier;
- open a gate;
- create a session or output;
- modify the Charter, Agenda, Constitution, RGS, Master Programme, or Open Questions.
