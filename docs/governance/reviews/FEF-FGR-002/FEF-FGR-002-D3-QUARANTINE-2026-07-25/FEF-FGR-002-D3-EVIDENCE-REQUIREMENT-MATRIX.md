# FEF-FGR-002 — D3 Evidence Requirement Matrix

| Control Field | Recorded Value |
|---|---|
| Matrix identifier | FEF-FGR-002-D3-ERM-001 |
| Review identifier | FEF-FGR-002 |
| Domain | D3 — Governance Assurance |
| Version | 1.0 |
| Preparation date | 2026-07-25 |
| Source RQs | FEF-FGR-002-RQ-016 through FEF-FGR-002-RQ-024 |
| Preparation capacity | FEF-FGR-002-RA-003 — Review Analyst |
| Recording capacity | FEF-FGR-002-RA-004 — Review Recorder |
| Validator | FEF-FGR-002-RA-006 — non-independent combination disclosed |
| Requirement references | D3-ERQ-01 through D3-ERQ-22 — temporary controls only |
| Evidence conclusion effect | None |

## 1. Derivation Method

Requirements were derived from the exact admitted RQ wording and mandatory
evidence-need fields. Shared requirements are consolidated so that one
qualified source may support several RQs without duplicate registration.
Different permitted uses remain explicit in the RQ mapping.

`D3-ERQ-NN` references are local matrix controls. They do not create permanent
identifier architecture, Evidence Records, admissibility, weight, or a
substantive answer.

## 2. Consolidated Requirements

| Ref | Canonical RQ | Evidential Issue | Required Source Characteristic / Likely Class | Authority, Provenance, Date, and Version | Need | Contrary / Failure Need | Permitted Use and Known Limitation | Absence Consequence / Escalation | Reuse |
|---|---|---|---|---|---|---|---|---|---|
| D3-ERQ-01 | RQ-016; RQ-019; RQ-024 | Assurance objects, transitions, gates, and reliance points | Controlling review instruments; E2 | Founder-approved or approved-plan preparation control; attributable repository path; current applicable state or exact operated baseline | Mandatory primary | Contrary lifecycle state if one exists | Identify governed objects and gates only; does not set D5 lifecycle architecture | Blocking if no authoritative lifecycle and gate basis exists | Shared |
| D3-ERQ-02 | RQ-016; RQ-019; RQ-024 | Operated validation, conditions, correction, closure, and later reliance | Validation and closure records; E4/E2 | Exact controlled record, validator, date, verdict, conditions, stable path, reproducible digest | Mandatory primary plus cross-domain corroboration | Pass-with-conditions, correction, blocked, returned, or fail examples where available | Establish operated states and recorded consequences only; no inference that the model is complete | Manageable if some verdict paths are unoperated; blocking if no operated gate exists | Shared |
| D3-ERQ-03 | RQ-016; RQ-020 | Proportionality, conditions, and residual-risk information | Attributable conditions and risk-boundary records; E1/E2 | Exact Founder decision or controlled limitation record; decision date and version | Mandatory primary | Condition that constrained reliance | Identify factors and reserved authority; validation is not risk acceptance | Blocking if Founder-risk boundary cannot be attributed | Shared |
| D3-ERQ-04 | RQ-017 | Formal role, authority, conflict, and separation requirements | Role, boundary, RACI, and independence controls; E2 | Current controlled versions and issuing review authority | Mandatory primary | Prohibited or conflicting combination rule | Compare functional boundaries; descriptive role text is not proof of independence | Blocking if current authority boundaries cannot be established | RQ-specific |
| D3-ERQ-05 | RQ-017 | Actual combined-capacity operation and compensating controls | Effective assignments and operated validation records; E2/E4 | Current assignment state and exact validation records with capacity disclosure | Mandatory primary and corroborative | Record showing omitted disclosure or failed control, if available | Establish disclosed operation only; capacity labels do not prove independence | Manageable limitation if operation exists but no independent comparator exists | RQ-specific |
| D3-ERQ-06 | RQ-017; RQ-022 | Independent validation and later independent revalidation | Independently performed validation or revalidation; E4 | Attributable independent validator, method, inputs, date, and result | Desirable corroboration; potentially material | Contrary independent conclusion | Cannot be substituted by deterministic checks or a second capacity label held by the same actor | Material manageable gap for pack preparation; escalate before any claim of independent assurance | Shared |
| D3-ERQ-07 | RQ-018 | Challenge, rebuttal, dissent, disagreement, and escalation controls | Normative challenge and escalation provisions; E2 | Controlling instrument or exact accepted decision boundary | Mandatory primary | Competing or contrary treatment | Identify permitted paths and authority boundaries only | Blocking if no challenge or escalation authority can be located | RQ-specific |
| D3-ERQ-08 | RQ-018 | Operated challenge, rebuttal, dissent, or unresolved disagreement | Attributable operated example; E1/E4 | Exact source, actors/capacities, evidence baseline, outcome, and unresolved state | Desirable corroboration; material | Contrary view or rejected challenge is intrinsic | Absence is not evidence that challenge control is unnecessary | Material manageable gap; escalate if a conclusion depends on operated effectiveness | RQ-specific |
| D3-ERQ-09 | RQ-019 | Distinct validation verdicts and reliance consequences | Operated Pass and Pass-with-Conditions records; E4 | Exact verdict, conditions, affected output, date, method, and validator | Mandatory primary | Different verdict and consequence paths | Compare recorded outcomes without making them permanent D5 states | Blocking if no distinct operated outcome is available | RQ-specific |
| D3-ERQ-10 | RQ-019 | Returned, blocked, failed, invalidated, or corrected paths | Operated negative/corrective example; E4 | Exact trigger, authority, affected artefact, correction, and reliance treatment | Desirable corroboration; material | Failed or blocked condition is intrinsic | No retrospective record may be manufactured | Material manageable gap; escalate before claiming complete consequence coverage | RQ-specific |
| D3-ERQ-11 | RQ-020 | Reserved risk authority and conditional Founder consideration | Exact Founder decisions and non-effects; E1 | Attributable directive, canonical decision record, date, conditions, and protected boundaries | Mandatory primary | Conditions showing validation did not accept risk | Establish decision authority and recorded conditions only; not substantive risk acceptance for D3 | Blocking if reserved authority or exact conditions are unavailable | RQ-specific |
| D3-ERQ-12 | RQ-020 | Operated residual-risk acceptance, expiry, or reassessment | Attributable risk decision and later reassessment; E1/E4 | Exact risk, accepter, conditions, expiry/trigger, and reassessment record | Desirable corroboration; material | Reassessment or rejection | A validation condition is not proof of risk acceptance | Material manageable gap; Founder escalation if current acceptance is requested | RQ-specific |
| D3-ERQ-13 | RQ-021 | Pre-Founder input assurance and neutrality | Founder review package and its validation; E2/E4 | Exact package baseline, source findings, neutrality checks, date, and digest | Mandatory primary | Returned or insufficient input example if available | Establish input preparation and validation, not quality of Founder judgement | Blocking if no attributable input-to-decision preparation chain exists | RQ-specific |
| D3-ERQ-14 | RQ-021 | Exact directive capture, decision recording, post-decision validation, and synchronisation | Attributable directives, canonical decisions, validation, and traceability; E1/E4 | Exact source wording, canonical ID, date, conditions, non-effects, validation, and register links | Mandatory primary plus complete D2 corroboration | Recording correction or mismatch, if available | Compare source-to-record fidelity; never evaluate or automate judgement | Blocking if directive-to-record reconciliation is not reproducible | RQ-specific |
| D3-ERQ-15 | RQ-022; RQ-023; RQ-024 | Reproducibility, integrity, and deterministic verification | Frozen packs, SHA-256 manifests, recorded commands/results, traceability; E4 | Exact baseline, algorithm, digest, date, method, and affected records | Mandatory primary | Integrity mismatch or tool failure where available | A successful command establishes only the condition tested | Blocking if material baselines cannot be reproduced | Shared |
| D3-ERQ-16 | RQ-022 | Handover, reassignment, Validator unavailability, defect discovery, and revalidation | Operated continuity or revalidation records; E2/E4 | Exact trigger, former/new capacity, transferred inputs, validation, date, and result | Desirable corroboration; material | Defect or failed continuity example | Ordinary file availability is not evidence of governed continuity | Material manageable gap; escalate before endorsing operated continuity effectiveness | RQ-specific |
| D3-ERQ-17 | RQ-023 | Tool and AI authority boundaries | Founder and operational authority controls; E1/E2 | Exact controlling decision or rule, applicable date, scope, and non-effects | Mandatory primary | Prohibited automation or escalation boundary | Establish permitted and prohibited roles; no general AI policy | Blocking if automated approval/Founder boundary is not attributable | RQ-specific |
| D3-ERQ-18 | RQ-023 | Operated deterministic, tool-assisted, and human-review steps | Validation reports with commands, results, manual checks, ambiguity treatment; E4 | Reproducible method, inputs, result, date, and responsible capacity | Mandatory primary and corroborative | False pass, error, or escalation example where available | Does not establish semantic truth or independent assurance | Manageable if error examples are absent; blocking if methods are irreproducible | RQ-specific |
| D3-ERQ-19 | RQ-024 | End-to-end RQ–evidence–pack–session–GF–FD assurance chain | Validated traceability registers; E4 | Exact record IDs, versions, conditions, and closed-domain state | Mandatory primary with D1/D2 corroboration | Missing or broken chain if found | Establish recorded linkage without source-authority elevation | Blocking if at least one complete chain cannot be reproduced | RQ-specific |
| D3-ERQ-20 | RQ-024 | Candidate/deferral assessment, closure, and downstream reliance | Candidate/deferral, closure, programme, and later-reference records; E2/E4 | Exact output state, validation, date, and protected boundary | Mandatory primary | Non-zero or returned treatment if available | Assurance objects only; no D7 candidate criteria, D8 disposition, or D6 architecture | Manageable if only zero-output examples exist; blocking if closure state is untraceable | RQ-specific |
| D3-ERQ-21 | RQ-016–RQ-024 | Qualification, permitted use, limitation, sufficiency, freeze, traceability, and custody baseline | Accepted D2 decisions and operated D2 controls; E1/E4 | Exact FD-011 through FD-016 wording, D2 validation, traceability, closure, and frozen EP-002 | Mandatory controlling dependency | Conditions and reserved subjects within each decision | Controls how D3 may rely; does not answer D3 | Blocking if a controlling D2 boundary is missing or broadened | Shared |
| D3-ERQ-22 | RQ-023; corroborative to RQ-016–RQ-022 and RQ-024 | External professional assurance and project-specific operated assurance | Authorised E3 or project-specific E4 | Primary authority, applicability, version, acquisition, access, and integrity | Desirable corroboration; not currently authorised | Contrary professional or project evidence | No external source may be introduced without later authority and qualification | Non-blocking for pack preparation if disclosed; escalate before any external-practice claim | Shared gap |

## 3. Per-RQ Requirement Reconciliation

| RQ | Requirement Refs | Mandatory | Corroborative / Contrary | Current Requirement Verdict |
|---|---|---:|---:|---|
| RQ-016 | 01, 02, 03, 21 | 4 | operated conditions and cross-domain gate examples within 02–03 | Complete |
| RQ-017 | 04, 05, 06, 21 | 3 | 1 — independent assurance under 06 | Complete with known evidence gap |
| RQ-018 | 07, 08, 21 | 2 | 1 — operated dissent/challenge under 08 | Complete with known evidence gap |
| RQ-019 | 01, 02, 09, 10, 21 | 4 | 1 — negative/corrective path under 10 | Complete with known evidence gap |
| RQ-020 | 03, 11, 12, 21 | 3 | 1 — operated risk reassessment under 12 | Complete with known evidence gap |
| RQ-021 | 13, 14, 21 | 3 | returned/mismatched input under 13–14 if available | Complete |
| RQ-022 | 06, 15, 16, 21 | 2 | 2 — independent revalidation and continuity under 06/16 | Complete with known evidence gaps |
| RQ-023 | 15, 17, 18, 22 | 3 | 1 — authorised E3/project source under 22 | Complete with known evidence gap |
| RQ-024 | 01, 02, 15, 19, 20, 21 | 6 | non-zero candidate/deferral or broken chain under 20 if available | Complete with limitation |

## 4. Requirement Validation

All nine admitted RQs are represented. Requirements are evidence-neutral,
cross-RQ reuse is explicit, and no evidence class is treated as automatic
weight. Missing independent, dissent, failure, continuity, residual-risk
reassessment, and external-source examples are requirements and gaps, not
assumed facts.

**Requirement-completeness verdict: Pass with Conditions.**

Conditions:

1. unavailable or unauthorised corroboration must remain visible;
2. a later pack must preserve each source's RQ-specific permitted use;
3. no gap may be filled by inference, reconstruction, or narrative repetition;
4. D4–D8 interfaces remain outside D3 decision scope.

## 5. Non-Effects

This matrix does not register evidence, determine source weight, answer an RQ,
assemble an Evidence Pack, create a session, produce a GF or FD, modify an Open
Question, or create constitutional or engineering authority.
