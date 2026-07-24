# FEF-FRCD-001 — Execution Register Instantiation Plan

**Status:** Prepared Plan — No Register Instances Created  
**Activation dependency:** Attributable Founder approval of FEF-FRCD-001  
**Review identifier dependency:** Assigned review identifier

## 1. Purpose

Define the controlled sequence for creating the empty register instances required to operate the Founder Governance Review after commencement is authorised.

This plan does not instantiate a register, assign a register identifier, or create a substantive register entry.

## 2. Instantiation Preconditions

No register may be instantiated until:

1. FEF-FRCD-001 is approved;
2. the approval is recorded;
3. the review identifier is assigned through the approved collision-safe procedure;
4. the governing instrument versions are confirmed;
5. the register owner and validator roles are recorded without inventing authority;
6. the applicable template or schema is validated;
7. the register location and access treatment are approved operationally.

## 3. Required Register Set

| Register Class | Purpose | Initial State | Substantive Rows at Instantiation |
|---|---|---|---:|
| Review Question Register | Control RQ identity, lifecycle, domain, evidence, and disposition | Empty controlled instance | 0 |
| Evidence Register | Control evidence identity, source, provenance, admissibility, access, and integrity | Empty controlled instance | 0 |
| Evidence Pack Register | Control pack identity, version, freeze, scope, integrity, and use | Empty controlled instance | 0 |
| Session Register | Control session identity, purpose, domain, readiness, state, and record location | Empty controlled instance | 0 |
| Governance Finding Register | Control GF identity, evidence basis, validation, lifecycle, and disposition | Empty controlled instance | 0 |
| Founder Decision Register | Control review-scoped FD identity, source GF, disposition, authority, and effect | Empty controlled instance | 0 |
| Constitutional Candidate Register | Control candidate identity, source decision, extraction status, and disposition | Empty controlled instance | 0 |
| Deferred Matter Register | Control intentionally deferred matters, rationale, dependencies, trigger, and state | Empty controlled instance | 0 |

## 4. Common Register Control Fields

Every future register instance must include:

- register title and class;
- unique register identifier derived from the assigned review identifier;
- assigned review identifier;
- register version;
- controlling Charter, Agenda, and Plan versions;
- applicable specification or schema;
- creation date;
- record owner;
- validator;
- lifecycle state;
- access and confidentiality treatment;
- integrity fingerprint or equivalent;
- change history;
- entry count;
- last validation date;
- non-effects statement.

## 5. Planned Identifier Forms

The following forms are schematic placeholders only:

| Register | Planned Form |
|---|---|
| Review Question Register | `<REVIEW-ID>-RQR-001` |
| Evidence Register | `<REVIEW-ID>-ER-001` |
| Evidence Pack Register | `<REVIEW-ID>-EPR-001` |
| Session Register | `<REVIEW-ID>-SR-001` |
| Governance Finding Register | `<REVIEW-ID>-GFR-001` |
| Founder Decision Register | `<REVIEW-ID>-FDR-001` |
| Constitutional Candidate Register | `<REVIEW-ID>-CCR-001` |
| Deferred Matter Register | `<REVIEW-ID>-DMR-001` |

These forms are not assigned identifiers and must be collision-checked when instantiated.

## 6. Instantiation Sequence

### Stage RI-0 — Authority Verification

- verify FEF-FRCD-001 approval;
- verify review identifier assignment;
- verify governing instrument versions;
- verify no stop condition.

### Stage RI-1 — Foundation Registers

Instantiate and validate, empty:

1. Review Question Register;
2. Evidence Register;
3. Deferred Matter Register.

### Stage RI-2 — Execution Registers

Instantiate and validate, empty:

1. Evidence Pack Register;
2. Session Register.

### Stage RI-3 — Output Registers

Instantiate and validate, empty:

1. Governance Finding Register;
2. Founder Decision Register;
3. Constitutional Candidate Register.

### Stage RI-4 — Cross-Register Validation

- confirm unique identifiers;
- confirm zero initial substantive rows;
- confirm reciprocal reference fields;
- confirm access and integrity controls;
- confirm navigation and traceability;
- record validation result.

## 7. Admission Boundary

Instantiation creates only an empty governed container.

It does not:

- admit an RQ;
- admit evidence;
- assemble or freeze a pack;
- schedule or create a session record;
- create a GF;
- create a review-scoped FD;
- create a Constitutional Candidate;
- defer a matter.

Each substantive entry requires its own authority, lifecycle, and validation.

## 8. Register-Specific Minimum Validation

| Register | Minimum Validation Before Use |
|---|---|
| Review Question Register | Conforms to [FEF-RQS-001](../../../governance/reviews/FEF-RQS-001-REVIEW-QUESTION-SPECIFICATION.md); lifecycle totals reconcile |
| Evidence Register | Provenance, admissibility, access, and integrity fields exist |
| Evidence Pack Register | Conforms to [FEF-EPS-001](../../../governance/reviews/FEF-EPS-001-EVIDENCE-PACK-SPECIFICATION.md); freeze and supplement states exist |
| Session Register | Links to the controlled session template and entry-gate state |
| Governance Finding Register | Supports evidence links, validation state, affected RQs, and Founder disposition |
| Founder Decision Register | Separates proposed, Founder-dispositioned, effective-treatment, and superseded states |
| Constitutional Candidate Register | Separates candidacy from constitutional approval or adoption |
| Deferred Matter Register | Records rationale, dependency, review trigger, owner, and non-closure state |

## 9. Existing Templates

The repository currently contains:

- [Review Question Register Template](../../../templates/FEF-REVIEW-QUESTION-REGISTER-TEMPLATE.md);
- [Founder Governance Review Session Record Template](../../../templates/FEF-FOUNDER-GOVERNANCE-REVIEW-SESSION-RECORD-TEMPLATE.md).

They remain templates. This plan does not copy, populate, rename, or instantiate them.

## 10. Completion Criteria

Register instantiation is complete only when:

- all eight empty instances exist under the assigned review identity;
- all identifiers are unique;
- all control fields are complete;
- all entry counts are zero at initial validation;
- all links resolve;
- cross-register fields are compatible;
- validation passes;
- no substantive review work has been performed merely through instantiation.

## 11. Current State

All eight register classes remain uninstantiated.

