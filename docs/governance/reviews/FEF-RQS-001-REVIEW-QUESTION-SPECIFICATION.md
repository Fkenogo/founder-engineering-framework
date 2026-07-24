# FEF-RQS-001 — Review Question Specification

**Programme:** Founder Engineering Framework  
**Document identifier:** FEF-RQS-001  
**Version:** 0.1  
**Status:** Founder Review Draft — Not Approved  
**Work package:** FEF-WPK-001G  
**Parent Plan:** [FEF-FGRP-001](FEF-FGRP-001-FOUNDER-GOVERNANCE-REVIEW-PLAN.md)  
**Review Questions instantiated:** 0  
**Execution effect:** None

## 1. Purpose

Define the canonical structure, lifecycle, validation, and traceability rules for future Founder Governance Review Questions.

This Specification creates no Review Question and assigns no review identifier.

## 2. Definition

A Review Question is a bounded, neutral, traceable statement of what the review must examine.

An RQ:

- connects the approved Agenda to operational evidence examination;
- states a decision or analysis purpose without predetermining an answer;
- may relate to one or more Charter domains;
- may originate from an existing Open Question, admitted evidence, a validated gap, or an authorised scope need;
- does not itself create a GF, FD, Constitutional Candidate, or Open Question disposition.

## 3. Identifier Schema

The canonical pattern is:

> `<REVIEW-ID>-RQ-NNN`

Where:

- `<REVIEW-ID>` is the later Founder-assigned review identifier;
- `RQ` denotes Review Question;
- `NNN` is a zero-padded sequential number.

Rules:

1. no RQ identifier may be issued before the review identifier is assigned;
2. identifiers are unique and immutable;
3. withdrawn identifiers remain reserved;
4. an amended RQ keeps its identifier and increments its version when its decision purpose is unchanged;
5. a materially different question receives a new identifier and links to the earlier RQ;
6. existing FEF-WPK-001 Open Question identifiers are never reused as RQ identifiers.

The pattern is not an instantiated identifier.

## 4. Mandatory Fields

| Field | Requirement |
|---|---|
| Canonical RQ ID | Assigned under Section 3 after review commencement |
| Version | Controlled RQ version |
| Title | Concise neutral label |
| Question Text | Exact bounded question |
| Decision Purpose | Why the review needs the answer |
| Review Domain | Primary D1–D8 domain |
| Secondary Domains | Other materially affected domains or `None` |
| Source / Trigger | Open Question, evidence gap, authorised scope item, prior GF, or other admitted source |
| Source Open Question | Exact existing OQ ID or `Not applicable` |
| Scope | Included subject matter |
| Exclusions | Explicit non-scope |
| Evidence Need | Evidence classes and subjects required |
| Evidence Records | Canonical admitted evidence references |
| Contrary Evidence | Known contradicting or limiting evidence |
| Dependencies | Prerequisite RQs, domains, evidence, authority, or decisions |
| Expected Output Class | Analysis, GF, decision question, deferral, mapping, or other Charter-permitted class |
| Founder Decision Need | `Required`, `Potential`, `Not currently required`, or `Undetermined` |
| Assigned Examination Unit | Future session reference after assignment, or `Unassigned` |
| Owner / Coordinator | Accountable preparation role |
| Validator | Assigned validation role |
| Lifecycle State | State from Section 5 |
| Disposition | Exact outcome or `Pending` |
| Related GFs | Canonical references or `None` |
| Related FDs | Canonical references or `None` |
| Constitutional Candidate Links | Canonical references or `None` |
| Deferred Matter Links | Canonical references or `None` |
| Created / Updated Dates | Attributable dates |
| Change Rationale | Reason for each controlled revision |

Mandatory fields may contain an explicit `Not applicable`, `None`, `Unassigned`, `Undetermined`, or `Pending` only when accurate. Blank mandatory fields fail validation.

## 5. RQ Lifecycle

| State | Meaning | Entry Authority | Exit Requirement |
|---|---|---|---|
| Candidate | Potential question identified but not admitted | Review Coordinator or authorised participant | Initial scope and source recorded |
| Draft | Mandatory fields being prepared | Review Coordinator | Neutral wording and dependencies complete |
| Evidence Mapped | Candidate Evidence Records and gaps mapped | Evidence Custodian | Evidence mapping and limitations recorded |
| Validated | Structure, neutrality, scope, evidence, and traceability pass | Validator | Validation record |
| Admitted | Approved for future examination within review scope | Review Coordinator under approved Plan | Future examination unit assignment permitted |
| Under Review | Being examined in an authorised session | Session entry gate | Session record captures treatment |
| Answered | Evidence and review outputs provide a recorded answer | Session/domain process | GF/FD links and disposition validated |
| Deferred | Intentionally postponed | Founder or authorised review disposition | Rationale, dependency, and trigger recorded |
| Out of Scope | Excluded by approved instruments | Review Coordinator or Founder as applicable | Destination or owner recorded |
| Superseded | Replaced by a new RQ | Approved change control | Replacement link recorded |
| Closed | All closure requirements satisfied | Authority appropriate to the source question | Final traceability and validation complete |
| Archived | Preserved after final review assembly | Evidence Custodian | Retention and integrity controls applied |

An RQ sourced from a governance Open Question cannot close that Open Question without the attributable Founder Decision required by the Charter.

## 6. Relationship to Domains

Each RQ shall:

- identify one primary D1–D8 domain;
- identify material secondary domains;
- respect the approved Agenda sequence;
- record why cross-domain treatment is needed;
- avoid merging distinct decision purposes merely to reduce question count;
- be revalidated if its primary domain changes.

D8 mapping does not require every RQ to use D8 as a secondary domain. The Open Question relationship field provides direct traceability.

## 7. Relationship to Evidence

Before admission, each RQ shall define:

- evidence needed;
- evidence already admitted;
- evidence gaps;
- conflicting or limiting sources;
- applicable evidence classes;
- whether the question can proceed conditionally.

An RQ may proceed with an evidence gap only when the gap is explicit and the future session entry validation permits it. Missing evidence shall not be converted into an answer.

## 8. Relationship to Governance Findings

- An RQ may produce zero, one, or multiple GFs.
- A GF may address multiple RQs only when each relationship is explicit.
- The RQ shall not contain the GF conclusion in advance.
- A GF link is added only after the GF receives its canonical identifier.
- An answered RQ relying on a GF must cite the GF’s lifecycle state.
- A rejected or superseded GF does not disappear from RQ history.

## 9. Relationship to Founder Decisions

- An RQ may identify a potential or required Founder decision.
- Decision options are prepared separately at the Founder Decision gate.
- An RQ must not imply that silence, acknowledgement, or session completion is an FD.
- When an FD is issued, the exact FD reference and effect on the RQ are recorded.
- If no FD is issued, the RQ shall record the resulting open, deferred, or non-decision state.

## 10. Relationship to Open Questions

For an RQ derived from one of the 23 existing Open Questions:

- preserve the exact OQ identifier;
- do not rewrite the OQ inside the canonical register;
- record whether the RQ covers all or part of the OQ;
- map all related GFs and FDs;
- distinguish `Answered` from `Closed`;
- require FD-cited authority for OQ closure;
- preserve any unresolved remainder.

## 11. Validation Requirements

### 11.1 Pre-Admission Validation

The Validator shall confirm:

- canonical identifier integrity;
- neutral and non-leading wording;
- one intelligible decision or analysis purpose;
- scope and exclusions;
- correct primary domain;
- evidence need and mapping;
- known conflicts and uncertainty;
- dependencies;
- expected output class;
- Founder decision-need classification;
- Open Question mapping;
- absence of a predetermined GF, FD, or candidate.

### 11.2 Pre-Session Validation

Confirm:

- RQ is `Admitted`;
- evidence pack contains the mapped admitted evidence;
- dependencies are satisfied or disclosed;
- session scope covers the RQ;
- no post-freeze material is used without supplement control.

### 11.3 Post-Session Validation

Confirm:

- session treatment is traceable;
- disposition is accurate;
- GF and FD references exist before citation;
- deferrals and gaps are explicit;
- Open Question status is not changed without authority;
- lifecycle transition is valid.

## 12. Traceability Rules

Every RQ shall support:

```text
Agenda Objective / Domain
        ↓
Source or Existing Open Question
        ↓
Review Question
        ↓
Evidence Records and Evidence Pack
        ↓
Future Session Record
        ↓
GF or Recorded Non-Finding
        ↓
FD or Recorded Non-Decision
        ↓
Open Question / Candidate / Deferral Treatment
```

Every missing link shall have an explicit reason.

## 13. Change Control

RQ changes shall:

- increment version;
- preserve prior wording;
- record author, date, and rationale;
- identify affected evidence, sessions, GFs, FDs, and OQs;
- trigger revalidation;
- avoid retroactive alteration of a session or Founder Decision.

A material purpose change requires a new RQ identifier.

## 14. Quality Rules

An RQ should be:

- neutral;
- singular enough to answer coherently;
- bounded;
- evidence-addressable;
- relevant to an approved domain;
- explicit about authority;
- proportionate;
- traceable;
- free from hidden implementation assumptions.

Questions should not be split or merged solely to produce a target count.

## 15. Specification Non-Effects

FEF-RQS-001 does not:

- assign a review identifier;
- instantiate an RQ;
- create an RQ Register;
- admit evidence;
- create a session;
- create a GF, FD, or Constitutional Candidate;
- change or close an Open Question;
- commence the review.
