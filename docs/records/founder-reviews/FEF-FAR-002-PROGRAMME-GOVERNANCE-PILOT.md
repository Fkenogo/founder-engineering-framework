# FEF-FAR-002 — Programme Governance Pilot Architectural Review

## 1. Review Identity

| Field | Recorded Value |
|---|---|
| Review identifier | FEF-FAR-002 |
| Title | Recognition of Programme Governance as a Distinct Governance Domain within FEF — Pilot Status |
| Work package | FEF-WPK-001B.6 |
| Review type | Founder Architectural Review |
| Authority | Founder |
| Recorded date | 2026-07-24 |
| Review status | Founder architectural decision recorded |
| Architectural treatment | Controlled pilot |
| Standard status | No standard created |
| Constitutional effect | None |
| Framework Governance effect | None |

## 2. Purpose

This record preserves the Founder-authorised architectural recognition of Programme Governance as a distinct governance domain within FEF for controlled pilot operation during the remainder of Phase 0.

The purpose is to evaluate an architectural distinction observed through practical programme execution. It is not to establish a permanent governance domain, create a Programme Governance Standard, or alter Framework Governance.

## 3. Authority Basis

FEF-WPK-001B.6 states that:

- Framework Governance governs the framework itself, including standards, constitutions, principles, authority, and engineering methods;
- Programme Governance governs execution of the framework, including programme control, sequencing, work packages, milestones, dashboards, health, validation, dependencies, and change control;
- the distinction has been validated through practical use during Phase 0;
- Programme Governance is to be established as a controlled pilot, not as a permanent governance domain.

This record preserves those supplied conclusions without expanding them.

## 4. Context Reviewed

The pilot recognition is based on the programme-management artefacts produced and validated through FEF-PGM-001:

- [FEF Master Programme](../../programme/FEF-MASTER-PROGRAMME.md);
- [Founder Dashboard](../../programme/FEF-FOUNDER-DASHBOARD.md);
- [Programme Dependency Review](../../programme/FEF-PROGRAMME-DEPENDENCY-REVIEW.md);
- [Programme Health Report](../../programme/FEF-PROGRAMME-HEALTH-REPORT.md);
- [FEF-PGM-001 Validation Report](../work-packages/FEF-PGM-001/FEF-PGM-001-VALIDATION-REPORT.md).

FEF-WPK-001B.6 also requires a dedicated Programme Decision Register as a pilot artefact.

## 5. Architectural Rationale

Programme control has a distinct operational concern from governance of framework content:

- **Framework Governance** addresses what governs the framework and its standards, principles, authority, constitutions, and engineering methods.
- **Programme Governance** addresses how authorised framework-development work is sequenced, monitored, validated, reported, and changed.

Recognising this boundary as a pilot permits controlled observation without prematurely creating a standard or permanent authority model.

## 6. Founder-Approved Architectural Decision

| Decision ID | Founder-Approved Architectural Decision | Recorded Effect | Scope Boundary |
|---|---|---|---|
| FAR-002-001 | Programme Governance is recognised as a distinct governance domain within FEF in Pilot Status. | Classifies the identified programme-management artefacts as Programme Governance Pilot Artefacts for controlled Phase 0 evaluation. | Does not create a permanent governance domain, governance standard, constitutional authority, or change to Framework Governance. |

This is an architectural decision only. Its approval is limited to pilot recognition and classification.

## 7. Architectural Boundary

### 7.1 Programme Governance Pilot Scope

The pilot may organise and evaluate:

- programme status and sequencing;
- work-package administration;
- milestones and dependencies;
- Founder dashboards;
- programme health reporting;
- programme-level validation;
- programme change control;
- programme-management decisions.

### 7.2 Excluded Scope

The pilot does not govern or decide:

- constitutional content or authority;
- Framework Governance principles;
- research, engineering, product, or adoption standards;
- approval or activation of FEF-RGS-000;
- product or project decisions;
- technical engineering methods;
- the creation of any additional governance domain.

Where a matter crosses this boundary, the pilot may record the dependency but may not decide the framework-governance substance.

## 8. Expected Benefits

The pilot will evaluate whether the distinction:

- improves programme visibility and sequencing;
- keeps programme-control decisions separate from framework-content decisions;
- improves dependency, milestone, and blocker traceability;
- reduces ambiguity about the current active and next authorised work;
- provides useful evidence for a later Founder architectural decision;
- avoids premature standardisation.

These are evaluation expectations, not guaranteed outcomes or adopted governance principles.

## 9. Pilot Status and Lifecycle

The architectural treatment is **Pilot**.

The pilot lifecycle is:

1. **Established** — FAR-002 and the pilot artefact set are recorded.
2. **Operating** — the artefacts support the remainder of Phase 0.
3. **Observed** — usability, consistency, proportionality, and boundary performance are recorded.
4. **Evaluated** — evidence is reviewed against Section 10.
5. **Founder Disposition** — the Founder may continue, revise, end, defer, or separately authorise a proposal for governed standardisation.

No lifecycle stage automatically creates permanence, standard status, constitutional effect, or authority beyond programme administration.

## 10. Validation and Evaluation Criteria

The pilot will be suitable for later evaluation when evidence shows whether:

1. the Master Programme remains the controlling programme record;
2. every work package is represented once with a clear status;
3. exactly one immediate next work package is identifiable;
4. sequencing and dependency changes remain traceable;
5. dashboards allow rapid Founder understanding;
6. programme decisions remain separate from constitutional, framework, engineering, and product decisions;
7. programme-control overhead remains proportionate to programme value;
8. pilot artefacts remain internally consistent;
9. no pilot artefact is treated as a governance standard;
10. the critical path is changed only through express authority.

## 11. Future Review Trigger

Founder architectural review is required at the end of Phase 0 or before any proposal to make Programme Governance permanent or governed by a standard, whichever occurs first.

An earlier review may be requested if the pilot creates material overlap with Framework Governance, becomes disproportionate, or cannot maintain a consistent programme record.

This trigger authorises evaluation only. It does not predetermine the Founder’s disposition.

## 12. Explicit Non-Effects

FAR-002:

- does not create a Programme Governance Standard;
- does not make Programme Governance a permanent governance domain;
- does not amend FEF-RGS-000;
- does not amend constitutional content;
- does not change an authority level;
- does not alter FAR-001 or another Founder decision;
- does not change the authorised execution sequence;
- does not authorise FEF-WPK-001C, FEF-WPK-001D, FEF-RDS-001, or FEF-P0-002 to commence;
- does not close any Open Question;
- does not approve the recommendation that every governance domain must first operate as a pilot;
- does not create another governance domain.

## 13. Recommendation Preserved for Pilot Evaluation

FEF-WPK-001B.6 supplies the following recommendation:

> Every new governance domain must first operate successfully as a pilot before it can become a governed standard.

This statement is preserved as a recommendation for evaluation. It is not an adopted programme rule, governance principle, constitutional provision, or mandatory standard-development requirement.

## 14. Approval and Treatment Record

| Field | Recorded Value |
|---|---|
| Architectural decision | FAR-002-001 |
| Approval status | Founder Approved — Pilot Architecture Only |
| Approval evidence | Express Founder authorisation and architectural conclusions in FEF-WPK-001B.6 |
| Separate review date | Not supplied |
| Pilot commencement | On completion and validation of FEF-WPK-001B.6 |
| Pilot duration | Remainder of Phase 0, subject to earlier review trigger |
| Permanent-domain status | Not approved |
| Standard status | No Programme Governance Standard exists |
| Constitutional treatment | None |
| Execution-sequence effect | None |
| Immediate next work package | Unchanged — FEF-WPK-001B.5 |
