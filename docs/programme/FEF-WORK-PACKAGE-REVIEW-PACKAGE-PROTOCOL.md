# FEF Work Package Review Package Protocol

**Protocol identifier:** FEF-WRP-001
**Work package:** FEF-WPK-001B.7
**Version:** Pilot v0.1
**Status:** Founder Approved for Pilot Use — Preferred Operating Practice
**Document type:** Operational review-package specification
**Standard status:** Not a governance standard
**Application:** Prospective; no historical rewrite required
**Authority effect:** None beyond cited work-package and programme authority

## 1. Purpose

The Work Package Review Package (WRP) provides a consistent, concise handover from work-package implementation to Founder review. It presents implementation outcomes, validation evidence, governance impact, programme impact, repository state, risks, and decision points in a predictable structure.

The protocol is intended to reduce review effort and improve traceability. During the Programme Governance pilot it is a preferred operating practice, not a mandatory control or governance standard.

## 2. Scope

The protocol applies prospectively to FEF work packages prepared after FEF-WPK-001B.7.

It covers:

- review-package preparation after implementation and validation;
- consistent presentation of work-package outcomes;
- separation of coding-agent reporting from Founder disposition;
- traceability to deliverables and evidence;
- recommendation of, but not authorisation of, subsequent work.

It does not:

- require historical work packages to be rewritten;
- replace a work-package specification or validation report;
- replace a Founder review or decision record;
- approve deliverables, standards, governance, or constitutional content;
- change programme status or sequencing by itself.

## 3. Authority Boundaries

### 3.1 Coding-Agent Responsibility

The coding agent may:

- prepare Sections 1 through 12;
- link deliverables and validation evidence;
- report implementation, architecture, governance, programme, and repository impacts;
- identify risks and Founder decisions required;
- recommend one next work package where the programme record supports it;
- mark the package review-ready after the completion criteria in Section 8 are met.

The coding agent must not:

- complete or pre-populate a Founder decision in Section 13;
- approve, accept, reject, condition, or activate a deliverable;
- represent a recommendation as authorisation;
- change programme sequencing through the Review Package;
- infer Founder disposition from silence or prior context.

### 3.2 Founder Responsibility

Only the Founder may complete Section 13. Founder completion may record disposition, conditions, amendments, approval status, and next-work-package authorisation.

Section 13 must remain visibly reserved even when no immediate Founder decision is requested.

### 3.3 Relationship to Other Records

The Review Package summarises and links evidence; it does not replace source artefacts. Where records differ:

- the Master Programme controls programme status and sequence;
- the applicable validation report controls recorded validation results;
- the relevant decision or review record controls its authorised decision;
- the Review Package controls none of those underlying authorities.

## 4. Review Package Lifecycle

| Stage | Responsible Party | Required Outcome |
|---|---|---|
| 1. Initiate | Work-package owner or coding agent | Identify that a prospective WRP will be prepared using the current template. |
| 2. Implement | Coding agent or authorised implementer | Produce scoped deliverables while preserving evidence and authority boundaries. |
| 3. Validate | Coding agent or authorised validator | Execute proportionate checks and issue a validation report. |
| 4. Assemble | Coding agent | Complete WRP Sections 1–12 and link source evidence. |
| 5. Handover | Coding agent | Mark the WRP review-ready while leaving Section 13 uncompleted. |
| 6. Founder Review | Founder | Review evidence and complete Section 13 if a disposition is made. |
| 7. Record | Authorised recorder | Preserve the Founder disposition and update affected programme records. |

Implementation completion, review-package readiness, and Founder disposition are distinct events. None implies another.

## 5. Required Review Package Structure

Every WRP prepared under this protocol should contain the following sections in order:

1. Executive Summary
2. Work Package Scope
3. Deliverables Produced
4. Architectural Impact
5. Governance Impact
6. Programme Impact
7. Repository Impact
8. Validation Summary
9. Outstanding Risks
10. Founder Decisions Required
11. Recommended Next Work Package
12. Review Checklist
13. Founder Disposition (Founder only)

### 5.1 Minimum Content

| Section | Minimum Content |
|---|---|
| Executive Summary | Outcome, review status, and material limitation |
| Work Package Scope | Objective, included work, exclusions, and authority boundary |
| Deliverables Produced | Identifiers, paths or links, status, and purpose |
| Architectural Impact | Architecture created, changed, confirmed, or explicitly unchanged |
| Governance Impact | Governance decisions, non-effects, open questions, and approval boundaries |
| Programme Impact | Work-package status, sequence, dependencies, dashboard, and next-work effects |
| Repository Impact | Files created or updated, protected files, worktree, branch, HEAD, commit, and remote state where relevant |
| Validation Summary | Validation report, checks, results, limitations, and unresolved failures |
| Outstanding Risks | Genuine remaining risks, owners where known, and consequences |
| Founder Decisions Required | Exact decisions requested, or an explicit statement that none are currently required |
| Recommended Next Work Package | Exactly one supported recommendation, or an explicit statement that none is recommended |
| Review Checklist | Concise checks enabling rapid Founder review |
| Founder Disposition | Founder-only fields defined in Section 7 |

## 6. Optional Content

Optional content may be added only where it improves review clarity. It should be placed as a subsection within Sections 1–12 so that Founder Disposition remains the final section.

Permitted optional content includes:

- evidence index;
- traceability matrix;
- change inventory;
- dependency diagram;
- validation limitations;
- deviations from the work-package scope;
- alternatives considered;
- implementation metrics;
- follow-up conditions proposed for Founder consideration.

Optional content must not obscure the required sections or create new authority.

## 7. Founder-Only Section

Section 13 must use the following fields:

- Founder disposition;
- conditions;
- amendments;
- approval status;
- next-work-package authorisation;
- Founder record reference;
- disposition date.

When assembled by a coding agent, each field must remain marked **Founder completion required**. The coding agent may not choose a disposition, enter “approved,” state conditions on the Founder’s behalf, or authorise subsequent work.

The template contains an explicit protected instruction comment. Removal or completion of that section by a coding agent is a protocol validation failure.

## 8. Completion Criteria

A WRP is **Review-Ready** when:

1. Sections 1–12 are present and materially complete;
2. deliverables and evidence are linked;
3. scope and authority boundaries are explicit;
4. impacts are distinguished from approvals;
5. validation results and limitations are accurately summarised;
6. risks and Founder decision points are explicit;
7. the next-work-package statement is a recommendation only;
8. Section 13 is present and uncompleted;
9. local references resolve;
10. the Review Package is consistent with the Master Programme.

Review-Ready does not mean Founder Approved.

A work package may be recorded as implementation-complete when its own authorised acceptance and validation criteria are met. If its work-package authority requires Founder approval as an acceptance condition, it must not be represented as finally approved before Section 13 or another authoritative Founder record supplies that approval.

## 9. Operating Practice

Prospective FEF work packages should use the current WRP template unless the work-package instruction expressly selects another review mechanism or the package is too small to justify a separate review artefact.

Because this is a preferred pilot practice:

- non-use does not require a governance exception;
- non-use should be explained in the work-package completion record;
- pilot evidence should record whether use improved review speed, clarity, and traceability;
- recurring problems should be recorded for pilot evaluation rather than silently converted into mandatory rules.

## 10. Change and Version Treatment

Protocol and template changes must:

- preserve the Founder-only boundary;
- remain within the Programme Governance pilot;
- be traceable to an authorised work package or recorded programme decision;
- avoid retrospective rewrite requirements;
- preserve prior versions in repository history when committed.

No pilot revision may represent this protocol as a governance standard without separate Founder authority.
