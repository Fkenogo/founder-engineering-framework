# Founder Engineering Framework Adoption Guide

**Document type:** Practical adoption guide  
**Status:** Proposed operational adoption guide — not yet a constitutional or governance standard  
**Framework basis:** FEF-PAR-001 and the completed D1–D6 operating record  
**Primary purpose:** Help individual Founder projects begin using the current Founder Engineering Framework without importing unnecessary governance overhead

---

## 1. Purpose

This guide explains how an individual Founder project should begin using the Founder Engineering Framework (FEF).

Its objective is not to make every project reproduce the full FEF repository or repeat the FEF-FGR-002 review programme.

Its objective is to help each project:

1. understand the current FEF baseline;
2. identify where it already aligns;
3. identify genuine gaps, deviations, or conflicts;
4. obtain Founder decisions only where necessary;
5. implement approved alignment actions proportionately; and
6. return operational lessons to FEF without automatically changing the Framework.

This guide applies the emerging FEF principles demonstrated through D1–D6:

- minimum-footprint administration;
- project ownership and stewardship;
- Single Source of Truth;
- evidence-bounded decision-making;
- explicit authority and lifecycle boundaries;
- proportional governance; and
- learning before legislating.

These principles remain operating guidance for adoption. Their permanent constitutional treatment remains subject to the authorised FEF programme and Framework Evolution process.

---

## 2. What FEF Adoption Means

FEF adoption does **not** mean:

- copying the full FEF repository into a project;
- creating hundreds of governance files;
- repeating every D1–D6 review activity;
- replacing project-specific programme management;
- forcing identical repository structures across all projects;
- transferring project authority to the FEF repository; or
- treating every FEF observation as mandatory policy.

FEF adoption means that the project uses the current FEF baseline as a minimum governance reference for:

- Founder authority;
- programme sequencing;
- evidence and validation;
- decision recording;
- repository integrity;
- controlled lifecycle transitions;
- traceability;
- escalation;
- exceptions and unresolved matters; and
- governance learning.

The project remains responsible for its own product, commercial, technical, operational, and delivery decisions.

---

## 3. Adoption Architecture

The relationship should remain:

```text
Founder Engineering Framework
        |
        | provides baseline governance
        v
Individual Founder Project
        |
        | retains project ownership and stewardship
        v
Project-specific delivery, decisions, evidence, and lessons
```

The FEF repository is the source of the Framework baseline.

Each project repository remains the source of truth for that project's own programme state, decisions, evidence, and delivery record.

The project should link to FEF. It should not duplicate the whole Framework.

---

## 4. Minimum Project Adoption Set

Every adopting project should begin with one required project-level file:

```text
docs/governance/FEF-ALIGNMENT.md
```

Where a repository already has a controlled governance or programme folder, place the file there instead of creating a competing structure.

Examples:

```text
docs/governance/FEF-ALIGNMENT.md
docs/programme/FEF-ALIGNMENT.md
knowledge-repository/00-enterprise/governance/FEF-ALIGNMENT.md
```

The project should use **one location only**.

The project should not create both a root-level and a nested alignment file.

### Optional supporting records

Create these only where the project genuinely needs them:

```text
docs/governance/FEF-ALIGNMENT-ACTIONS.md
docs/governance/FEF-DEVIATIONS.md
docs/governance/FEF-LESSONS.md
```

Do not create optional records merely to complete a template.

A small project may keep approved actions, deviations, and lessons inside `FEF-ALIGNMENT.md`.

---

## 5. Role of `FEF-ALIGNMENT.md`

`FEF-ALIGNMENT.md` is the project's controlled entry point to FEF.

It should answer:

- Which FEF baseline is the project using?
- What parts already align?
- What genuinely requires adjustment?
- What remains project-specific?
- Are there intentional deviations?
- Are any Founder decisions required?
- What alignment work has been approved?
- What lessons should later be considered by FEF?

It is not a duplicate Master Programme.

It is not a project constitution.

It is not authority to make changes.

It is an alignment and traceability record.

---

## 6. Who Creates the Alignment File

The coding agent working inside the individual project repository should create it.

The Founder should not manually copy and maintain alignment files across repositories.

The coding agent should:

1. inspect the project repository;
2. identify the existing authoritative programme and governance records;
3. select the correct folder;
4. create the project-specific `FEF-ALIGNMENT.md`;
5. assess alignment without implementing changes;
6. validate links and repository state;
7. stop for Founder review.

The coding agent must not create the file in the central FEF repository on behalf of a project.

Each project owns its own alignment record.

---

## 7. Adoption Stages

### Stage 1 — Read-only project assessment

The coding agent reviews:

- repository structure;
- Master Programme or equivalent;
- project constitution or authority records;
- decision registers;
- evidence and validation records;
- lifecycle controls;
- current delivery state;
- unresolved matters; and
- existing governance documentation.

No project changes are implemented.

### Stage 2 — Prepare `FEF-ALIGNMENT.md`

The coding agent records:

- current FEF baseline;
- current project baseline;
- areas already aligned;
- gaps or missing controls;
- intentional project-specific differences;
- possible conflicts;
- recommended alignment actions;
- actions requiring Founder authority;
- actions that need no change; and
- candidate lessons for FEF.

### Stage 3 — Founder review

The Founder decides only:

- which alignment actions are approved;
- which deviations are accepted;
- which matters require clarification;
- which matters remain project-specific; and
- which lessons should be retained for later Framework consideration.

### Stage 4 — Controlled implementation

The coding agent implements only approved alignment actions.

The project should preserve its own architecture unless a change is explicitly approved.

### Stage 5 — Alignment closure

The coding agent updates `FEF-ALIGNMENT.md` with:

- completed actions;
- approved deviations;
- remaining gaps;
- current alignment status; and
- next review trigger.

### Stage 6 — Operational learning

The project records only material lessons.

A lesson does not automatically change FEF.

Lessons should enter the existing Framework Evolution intake only after Founder authorisation and evidence of wider relevance.

---

## 8. Alignment Categories

Use the following categories.

| Category | Meaning |
|---|---|
| Aligned | The project already satisfies the relevant FEF baseline |
| Partially Aligned | The project satisfies part of the baseline but has a genuine gap |
| Project-Specific | The matter belongs to the project and does not require Framework standardisation |
| Intentional Deviation | The project knowingly differs and requires an explicit rationale or Founder acceptance |
| Conflict | The project and FEF appear to require incompatible treatment; do not resolve automatically |
| Not Applicable | The FEF control does not apply to the project's present scope or lifecycle |
| Evidence Needed | Alignment cannot be determined from available repository evidence |
| Pending Founder Decision | A material authority, exception, risk, or sequencing decision is required |

Avoid percentage scores unless a later authorised methodology requires them.

---

## 9. Minimum Alignment Areas

The first alignment assessment should cover only these areas:

1. **Founder authority**
   - Are reserved Founder decisions identifiable?
   - Are delegated operational roles clearly bounded?

2. **Programme authority**
   - Is there one authoritative source of current project state?
   - Are next actions and dependencies controlled?

3. **Decision lifecycle**
   - Are material decisions attributable and recorded?
   - Are decision and implementation authority separated?

4. **Evidence and validation**
   - Can important claims and approvals be traced to evidence?
   - Are validation limitations disclosed?

5. **Lifecycle and gates**
   - Are major transitions explicitly authorised?
   - Can work proceed without silently skipping prerequisites?

6. **Repository integrity**
   - Are authoritative records identifiable?
   - Are historical records preserved?
   - Are links, versions, and statuses internally coherent?

7. **Exceptions and unresolved matters**
   - Are blockers, risks, open questions, and deviations visible?
   - Are they prevented from silently becoming resolved?

8. **Governance proportionality**
   - Is administration limited to what materially protects trust, integrity, and sequencing?

Do not assess every FEF document individually unless the project has a specific need.

---

## 10. Standard Prompt — Initial Project Alignment

Use this prompt inside each project repository:

> Review this project against the current Founder Engineering Framework operational baseline.
>
> Treat the project repository as the authoritative source for the project's own state and FEF as the baseline governance reference.
>
> Do not redesign the project. Do not copy the full FEF repository. Do not introduce governance merely to resemble FEF.
>
> First inspect the repository and identify:
>
> 1. the project's authoritative programme-state record;
> 2. existing Founder authority and decision records;
> 3. evidence, validation, lifecycle, repository, and exception controls;
> 4. existing governance folders and naming conventions; and
> 5. the correct location for one project-level `FEF-ALIGNMENT.md`.
>
> Prepare a read-only alignment assessment covering:
>
> - areas already aligned;
> - genuine gaps;
> - project-specific matters;
> - intentional deviations;
> - conflicts that require Founder judgement;
> - evidence gaps;
> - proportionate recommended actions; and
> - operational lessons that may later inform FEF.
>
> Create `FEF-ALIGNMENT.md` in the project's existing governance or programme folder. If no suitable folder exists, use `docs/governance/FEF-ALIGNMENT.md`.
>
> Do not implement any alignment action.
>
> Do not create extra registers or governance files unless the assessment demonstrates they are necessary.
>
> Treat FEF as minimum governance, not a complete project operating model.
>
> Stop for Founder review and report the repository state, file location, alignment findings, proposed actions, deviations, conflicts, and next decision required.

---

## 11. Standard Prompt — Approved Alignment Implementation

After Founder review, use:

> Implement only the Founder-approved FEF alignment actions recorded for this project.
>
> Preserve the project's own architecture, business decisions, technical decisions, and repository ownership.
>
> Do not implement unapproved recommendations.
>
> Do not create new governance artefacts where an existing authoritative project record can carry the required control.
>
> Where project practice and FEF appear to conflict, stop and report the conflict rather than resolving it by assumption.
>
> Update `FEF-ALIGNMENT.md` to record:
>
> - approved actions;
> - completed actions;
> - accepted deviations;
> - unresolved conflicts;
> - remaining evidence gaps;
> - current alignment status; and
> - the next review trigger.
>
> Validate links, repository integrity, and the absence of unrelated changes.
>
> Commit and push according to the project's normal engineering controls, then stop.

---

## 12. Framework Lessons

A project lesson should be recorded only when it is material.

Examples:

- a governance control consistently prevented a defect;
- a required control created disproportionate effort;
- a lifecycle gate was unclear;
- a project needed a control not currently available in FEF;
- a project-specific practice may be transferable elsewhere; or
- a repeated synchronisation or traceability failure occurred.

The project should record:

| Field | Required content |
|---|---|
| Lesson | What happened |
| Evidence | Where it can be verified |
| Project context | Why it arose here |
| Local action | What the project did |
| Possible wider relevance | Why it may matter beyond this project |
| Status | Observed / Submitted / Under Review / Adopted / Rejected / Deferred |

A project lesson is not a Framework rule.

Cross-project adoption requires the authorised Framework Evolution process.

---

## 13. Recommended Rollout Order

Do not align every project at once.

Use a pilot sequence:

1. Select one active, well-documented project.
2. Create its `FEF-ALIGNMENT.md`.
3. Review the administrative effort.
4. Implement only high-value alignment actions.
5. Record lessons.
6. Refine the adoption process if necessary.
7. Apply the improved process to the next project.

Recommended first pilots:

- one product with active engineering delivery; and
- one knowledge-heavy or non-software project.

This provides contrasting evidence without attempting a full portfolio rollout immediately.

---

## 14. Alignment Review Triggers

Review the project alignment when:

- the project begins a new major phase;
- a new repository or programme architecture is introduced;
- a material Founder decision changes authority or scope;
- a major release or implementation baseline is approved;
- the project discovers a recurring governance failure;
- FEF issues a new approved operational baseline; or
- the Founder explicitly requests reassessment.

Do not create fixed recurring reviews unless operational evidence shows they are needed.

---

## 15. Adoption Boundaries

The project must not:

- claim full FEF compliance without an evidence-based assessment;
- treat emergent FEF patterns as constitutional rules;
- replace its own Master Programme with the central FEF Master Programme;
- create duplicate sources of project state;
- silently resolve conflicts between FEF and project decisions;
- make Framework Evolution decisions inside the project repository;
- submit every local improvement as a Framework lesson; or
- allow alignment activity to displace core project delivery.

---

## 16. Success Test

The adoption process is working when:

- the project has one clear alignment record;
- important authority and lifecycle gaps are visible;
- approved changes are proportionate;
- project delivery becomes clearer rather than slower;
- no competing programme controls are created;
- project ownership remains intact;
- lessons are captured without automatically becoming policy; and
- FEF supports the project without becoming the project's main workload.

---

## 17. Immediate Adoption Decision

For the current FEF programme, this guide should be treated as a proposed operational adoption aid.

Before it becomes a permanent Framework standard, it should be tested in individual Founder projects.

The first operational objective is not universal compliance.

It is to determine whether the present FEF baseline can improve governance in real projects with minimum additional administration.
