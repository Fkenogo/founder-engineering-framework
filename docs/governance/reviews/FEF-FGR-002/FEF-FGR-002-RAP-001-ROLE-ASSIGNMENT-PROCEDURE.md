# FEF-FGR-002-RAP-001 — Role Assignment Procedure

| Control Field | Recorded Value |
|---|---|
| Review identifier | FEF-FGR-002 |
| Document identifier | FEF-FGR-002-RAP-001 |
| Version | 1.0 |
| Status | Controlled Operational Document — Mobilisation |
| Assignment register | FEF-FGR-002-RAR-001 |
| Current assignments | 0 |

## 1. Purpose

Define the controlled procedure for assigning, changing, suspending, ending, and preserving individual operational role assignments for FEF-FGR-002.

## 2. Assignment Authority

The Founder is the authority for:

- initial role assignments;
- assignment of the Review Administrator;
- assignment or approval of the Validator;
- any assignment that combines the Founder role with an operational role;
- high-risk multiple-role combinations;
- exceptions with residual procedural risk;
- removal of an assignment where reserved authority or review integrity is affected.

The assigned Review Administrator may:

- propose assignments and reassignments;
- administer the assignment record;
- recommend temporary cover;
- end an assignment at its recorded expiry;
- initiate vacancy and succession procedures.

The Review Administrator cannot make their own assignment effective or approve a high-risk combination. Founder approval is required.

## 3. Assignment Preconditions

Before an assignment becomes effective:

1. the role must exist in FEF-FGR-002-OGRS-001;
2. the candidate individual must be uniquely identifiable;
3. competence against the role requirements must be assessed;
4. availability and access requirements must be confirmed;
5. actual, potential, and perceived conflicts must be disclosed;
6. role combinations and independence limitations must be assessed;
7. required compensating controls must be defined;
8. assignment authority must approve;
9. the complete assignment must be entered in FEF-FGR-002-RAR-001;
10. the Validator must validate the record and boundary;
11. the effective date must be reached.

An assignment cannot operate retrospectively to legitimise an unauthorised action.

## 4. Mandatory Assignment Record

Every assignment must record:

- assignment identifier;
- role;
- assigned individual;
- individual identifier or attributable reference;
- assignment authority;
- authority source;
- assignment date;
- effective date;
- planned end date or explicit open-ended treatment;
- actual end date;
- status;
- competence assessment;
- access treatment;
- related role combinations;
- conflict disclosure;
- independence treatment;
- limitations;
- compensating controls;
- validation outcome and validator;
- superseded assignment, where applicable;
- change-history reference.

## 5. Assignment Lifecycle

| State | Meaning |
|---|---|
| Proposed | Candidate and role identified; no authority to act |
| Conflict Review | Competence, independence, and conflicts under assessment |
| Approved | Assignment authority approved; effective date not yet reached |
| Effective | Individual may act within the assigned role and limits |
| Temporarily Suspended | Authority to act paused; record retained |
| Expired | Planned end date reached |
| Withdrawn | Assignment authority or assignee ended the assignment |
| Superseded | Replacement assignment is effective |
| Archived | Historical assignment retained after review completion |

Only an `Effective` assignment authorises operational action.

## 6. Initial Assignment Procedure

1. Review Administrator candidate or Founder prepares an assignment proposal.
2. Candidate competence and access needs are assessed.
3. Conflicts and role combinations are disclosed.
4. Independence controls are assessed by a person not approving their own exception.
5. Founder approves, conditions, returns, defers, or declines the assignment.
6. Review Recorder or authorised register administrator records the exact disposition.
7. Validator validates identity, authority source, limits, conflicts, dates, and status.
8. Register state becomes `Effective` only when approval, validation, and effective date are all present.

## 7. Reassignment Procedure

Reassignment requires:

- reason for change;
- affected role and incumbent assignment;
- proposed successor;
- effective transition date;
- handover requirements;
- access changes;
- conflict and independence reassessment;
- assignment authority approval;
- validation;
- linkage between superseded and successor records.

The prior record is never overwritten or deleted.

## 8. Temporary Assignment

A temporary assignment must include:

- triggering vacancy or absence;
- defined start and end date;
- exact permitted scope;
- prohibited actions;
- role-combination assessment;
- compensating controls;
- approval and validation;
- handback or extension procedure.

Temporary status does not relax authority or competency boundaries.

## 9. Vacancy Handling

When a required role is vacant:

1. mark the role coverage state `Vacant`;
2. identify affected activities and gates;
3. suspend activities requiring that role;
4. notify the Founder, Review Administrator, and Validator;
5. initiate temporary or permanent assignment;
6. preserve incomplete work without advancing lifecycle state.

Founder vacancy is not cured through operational substitution. Reserved Founder gates remain blocked.

## 10. Succession and Handover

Handover must preserve:

- current registers and artefact states;
- open defects, conflicts, dependencies, and escalations;
- access custody;
- Evidence Pack and integrity information;
- upcoming gates;
- role-specific working records;
- acknowledgment by successor and outgoing assignee;
- validation of the transfer.

Succession does not transfer greater authority than the role contains.

## 11. Withdrawal

An assignee may request withdrawal. Assignment authority may also withdraw an assignment for:

- role completion;
- loss of competence or availability;
- unmanageable conflict;
- boundary breach;
- integrity failure;
- failure to perform required controls;
- review suspension or completion.

Withdrawal must record reason, effective time, affected work, access termination, handover, and successor treatment.

## 12. Access and Credential Treatment

Role assignment and system access are separate controls.

An effective assignment does not automatically grant:

- repository write access;
- confidential evidence access;
- approval permissions;
- external-system credentials.

Access must be proportionate, recorded, reviewed on reassignment, and removed when no longer required.

## 13. Audit Trail

The audit trail must preserve:

- every proposal and disposition;
- all versions;
- exact authority source;
- conflict disclosures;
- conditions and limitations;
- validation outcomes;
- effective and end dates;
- suspensions, withdrawals, and supersession;
- access changes;
- handovers;
- corrections and reasons.

Assignment identifiers remain reserved after withdrawal or error correction.

## 14. Assignment Identifier

Future assignment records use:

```text
FEF-FGR-002-RA-NNN
```

This is a schema only. No assignment identifier is instantiated by this procedure.

## 15. Current State

FEF-FGR-002-RAR-001 exists with zero assignments. No individual may act under an operational role until a valid assignment reaches `Effective`.

