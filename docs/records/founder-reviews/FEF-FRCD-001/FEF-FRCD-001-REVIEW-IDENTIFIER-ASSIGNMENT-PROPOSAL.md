# FEF-FRCD-001 — Review Identifier Assignment Proposal

**Status:** Proposal — Not Assigned  
**Parent decision:** [FEF-FRCD-001](../FEF-FRCD-001-FOUNDER-REVIEW-COMMENCEMENT-DECISION.md)  
**Allocation authority:** Founder commencement decision  
**Current review identifier:** None

## 1. Purpose

Prepare a collision-safe review identifier for assignment only after the Founder approves FEF-FRCD-001.

This proposal does not assign, reserve as authoritative, or activate an identifier.

## 2. Identifier Rules

FEF-FGRP-001 defines the review identifier schema as:

```text
FEF-FGR-NNN
```

The allocation procedure requires:

1. explicit Founder commencement authority;
2. repository-wide collision review;
3. protection of the historical FEF-FGR-001 record;
4. selection of the next unused numeric value;
5. attributable assignment recording;
6. consistent propagation only after assignment.

## 3. Existing Review-Identifier Inventory

The inventory distinguishes namespaces because architectural reviews and governance reviews are different record classes.

| Identifier | Class | Current Treatment | Collision Relevance |
|---|---|---|---|
| FEF-FAR-001 | Founder Architectural Review | Existing architectural review record | Occupies FAR namespace only |
| FEF-FAR-002 | Founder Architectural Review | Existing pilot architectural review record | Occupies FAR namespace only |
| FEF-FGR-001 | Founder Governance Review | Permanent historical evidence-gap record | Occupies FGR sequence 001 permanently |

No other exact `FEF-FGR-NNN` identifier was found in the repository inventory performed for this package.

## 4. Protected Historical Identifier

FEF-FGR-001 shall remain:

- the permanent historical evidence-gap record;
- independently identifiable;
- unrenumbered;
- unreconstructed;
- unavailable for reuse.

The new review must not inherit, overwrite, complete, or alias FEF-FGR-001.

## 5. Proposed Next Identifier

The next available identifier is proposed as:

> **FEF-FGR-002 — Proposed; Not Assigned**

This value is collision-safe at preparation time because:

- FEF-FGR-001 is the only occupied FGR sequence value;
- no exact FEF-FGR-002 identity exists in the repository;
- FAR identifiers are a separate review class and namespace;
- the proposal preserves monotonic numbering;
- the value will be checked again immediately before assignment.

Mention of FEF-FGR-002 in this proposal is not assignment.

## 6. Assignment Procedure After Founder Approval

If FEF-FRCD-001 is approved:

1. record the attributable Founder approval;
2. repeat the repository-wide exact-identifier collision search;
3. confirm FEF-FGR-001 remains protected and unchanged;
4. confirm FEF-FGR-002 remains unused;
5. assign FEF-FGR-002 in a controlled review identity record;
6. record assignment date, authority, and source decision;
7. instantiate registers using the assigned identifier;
8. validate all propagated references before review activity begins.

If FEF-FGR-002 is no longer available, stop and return to the Founder with a revised proposal. Do not silently select another number.

## 7. Assignment Record Requirements

The future assignment record must contain:

- assigned review identifier;
- review title;
- Founder authority reference;
- assignment date;
- collision-search scope and result;
- historical FEF-FGR-001 protection statement;
- governing instrument versions;
- review state;
- integrity or validation record;
- propagation log.

## 8. Non-Effects

This proposal does not:

- assign FEF-FGR-002;
- commence the review;
- create a review record;
- create a register instance;
- create a session;
- create any Review Question, evidence record, Evidence Pack, Governance Finding, Founder Decision, or Constitutional Candidate;
- change FEF-FGR-001.

