# FEF-PGC-001 — Cross-Domain Lessons Learned

| Control Field      | Recorded Value                                                                                                          |
| ------------------ | ----------------------------------------------------------------------------------------------------------------------- |
| Lessons identifier | FEF-PGC-001-LLD-001                                                                                                     |
| Phase              | Post-D4 / Pre-D5                                                                                                        |
| Date               | 2026-07-29                                                                                                              |
| Review identifier  | FEF-FGR-002                                                                                                             |
| Domains assessed   | D1 — Governance Authority; D2 — Evidence Governance; D3 — Governance Assurance; D4 — Records and Information Governance |
| Authority boundary | Observation and recommendation only; no constitutional effect; no Founder Review required                               |
| Validator          | FEF-FGR-002-RA-006 — Validator; non-independent combination disclosed                                                   |

## 1. What Worked Well

### 1.1 One-to-One Traceability

The requirement that every Review Question map to exactly one Governance Finding and one Founder Decision produced:

- unambiguous accountability;
- simplified validation;
- clear closure criteria;
- no orphaned artefacts.

**Lesson:** Preserve the one-to-one chain for future domains. Do not introduce many-to-one or one-to-many mappings without explicit Founder authorisation.

### 1.2 Frozen Evidence Baselines

Freezing Evidence Packs (EP-002, EP-003, EP-004) before session examination provided:

- a stable examination baseline;
- protection against post-hoc evidence amendment;
- clear validation of evidence integrity;
- reproducible traceability.

**Lesson:** Continue the DG-3 freeze gate for all future domains. Do not allow session examination to proceed against a mutable evidence baseline.

### 1.3 Non-Independent Validation Disclosure

The explicit disclosure that the same capacity prepared and validated artefacts:

- preserved transparency;
- avoided false claims of independence;
- allowed Founder acceptance with conditions;
- maintained review validity without requiring external validation resources.

**Lesson:** Retain the non-independent validation disclosure as a standard control. Do not remove it until independent validation is separately authorised and resourced.

### 1.4 Verbatim Founder Wording

Recording Founder dispositions, conditions, rationale, and follow-up actions verbatim:

- eliminated interpretation risk;
- preserved constitutional discipline;
- enabled exact-fidelity validation;
- prevented agent inference of Founder intent.

**Lesson:** Continue verbatim recording for all future Founder Reviews. Do not paraphrase, summarise, or synthesise Founder wording.

### 1.5 Bounded Non-Effects

Every artefact recorded explicit non-effects:

- what it does not do;
- what it does not amend;
- what it does not commence;
- what it does not create.

This prevented scope creep and protected completed work.

**Lesson:** Maintain non-effects sections in all governance artefacts. They are as important as the effects.

## 2. What Became Unnecessarily Complex

### 2.1 Identifier Proliferation

The requirement to allocate unique identifiers for every artefact (e.g., FEF-FGR-002-D4-G2-FDVR-001) created administrative overhead. While necessary for traceability, the volume of identifiers requires careful register management.

**Observation:** This complexity is acceptable for a governance framework but may be heavy for simple projects. No simplification is recommended for FEF itself.

### 2.2 Register Synchronisation

Updating multiple registers (Governance Finding, Founder Decision, Review Question, Session, Review Identity, Master Programme, Founder Dashboard, Document Manifest) for each lifecycle transition is repetitive and error-prone.

**Observation:** This synchronisation is necessary for consistency but could benefit from a checklist or automation script in future projects. No change is recommended for FEF at this time.

### 2.3 Quarantine Recovery

The D3 quarantine incident (six artefacts with voided identifiers) demonstrated that:

- identifier collisions can occur;
- recovery requires preserved evidence and explicit voiding;
- the framework handles such incidents without data loss.

**Lesson:** Continue the quarantine approach for identifier or authority conflicts. Do not delete quarantined artefacts.

## 3. Where Templates Can Be Reused

| Template                             | Reuse Potential                          | Recommendation                      |
| ------------------------------------ | ---------------------------------------- | ----------------------------------- |
| Session Record Template              | High — used for S02, S03, S04            | Reuse for all future sessions       |
| Review Question Register Template    | High — used for D2, D3, D4 RQ registers  | Reuse for all future domains        |
| Work Package Review Package Template | High — used for WPK-001B.7, WPK-001E/F/G | Reuse for future work packages      |
| Evidence Pack Specification          | High — used for EP-002, EP-003, EP-004   | Reuse for all future evidence packs |
| Founder Decision Record Template     | High — used for FD-011 through FD-032    | Reuse for all future DG-5 issuances |
| Closure Report Template              | High — used for D2, D3, D4 closures      | Reuse for all future DG-6 exits     |
| Validation Report Template           | High — used across all domains           | Reuse for all future validations    |

**Lesson:** The template library is sufficient for D5 and future domains. No new templates are required.

## 4. Where Guidance Can Be Simplified

### 4.1 Onboarding Sequence

New adopters should read the five core instruments in this order:

1. FEF-FGRC-001 — Charter (authority and roles);
2. FEF-FGRP-001 — Plan (lifecycle and gates);
3. FEF-FGRER-001 — Execution Rules (session conduct);
4. FEF-RQS-001 — RQ Specification (question standards);
5. FEF-EPS-001 — Evidence Pack Specification (evidence standards).

**Recommendation:** Publish this sequence as the standard onboarding path.

### 4.2 Register Update Checklist

For each lifecycle transition, the following registers should be checked:

- Governance Finding Register;
- Founder Decision Register;
- Review Question Register;
- Session Register;
- Review Identity;
- Master Programme;
- Founder Dashboard;
- Document Manifest.

**Recommendation:** Use this checklist to avoid missed synchronisation.

### 4.3 Domain Closure Criteria

A domain may close only when:

- all RQs are answered and linked to GFs and FDs;
- all validations pass;
- traceability chains are complete;
- protected artefacts are unchanged;
- registers reconcile.

**Recommendation:** Apply these criteria consistently to D5 and future domains.

## 5. Strategic Observations

### 5.1 Governance as Enabler

The FEF demonstrates that governance can enable engineering rather than slow it, provided that:

- governance is bounded to risk reduction;
- evidence is preserved rather than re-examined;
- decisions are recorded verbatim;
- lifecycle closure is administrative rather than substantive.

### 5.2 Common vs Project Boundary

The most important architectural decision is the clear separation between:

- common FEF governance (reusable across projects);
- project engineering governance (project-specific);
- product architecture (project-specific);
- delivery governance (project-specific).

This separation prevents the framework from becoming a bottleneck.

### 5.3 Future Evolution

Framework enhancements (e.g., FEF-CCF-001 Context Continuity Framework) are correctly registered as future candidates rather than immediate requirements. This preserves D4–D5 focus and prevents governance expansion.

**Lesson:** Continue to defer framework evolution to authorised Framework Evolution processes.

## 6. Non-Effects

This lessons-learned document:

- does not amend D1–D4 artefacts;
- does not create new registers, governance domains, or lifecycle stages;
- does not perform Framework Evolution;
- does not amend constitutional instruments;
- does not commence D5 or D6;
- does not issue Founder Decisions;
- does not restructure the repository.
