# FEF-EPS-001 — Evidence Pack Specification

**Programme:** Founder Engineering Framework  
**Document identifier:** FEF-EPS-001  
**Version:** 0.1  
**Status:** Founder Review Draft — Not Approved  
**Work package:** FEF-WPK-001G  
**Parent Plan:** [FEF-FGRP-001](FEF-FGRP-001-FOUNDER-GOVERNANCE-REVIEW-PLAN.md)  
**Evidence packs assembled:** 0  
**Execution effect:** None

## 1. Purpose

Define how future Founder Governance Review evidence packs shall be structured, versioned, admitted, frozen, updated, integrity-verified, and traced.

This Specification creates no Evidence Record and assembles no evidence pack.

## 2. Evidence Pack Definition

An Evidence Pack is a controlled, versioned collection of admitted Evidence Records and supporting materials prepared for a bounded review purpose.

An Evidence Pack:

- is not the original authority of its sources;
- does not elevate source authority;
- does not create a GF or FD;
- must distinguish admitted evidence, rejected evidence, context-only material, and unresolved access dependencies;
- becomes usable only after validation and freeze.

## 3. Pack Types

| Pack Type | Purpose |
|---|---|
| Review Baseline Pack | Approved instruments, attributable authority, programme context, historical boundary, and initial Open Questions baseline |
| Domain Pack | Evidence common to one Charter domain |
| Session Pack | Bounded admitted evidence for future RQs in one future session |
| Supplemental Pack | Controlled evidence admitted after a prior freeze |
| Decision Extract | Exact validated evidence and GF references supporting a future Founder decision gate |
| Final Review Evidence Index | Consolidated index of every pack and Evidence Record used in the review |

Pack types are future classifications only.

## 4. Identifier Strategy

After review identifier assignment, a pack shall use:

> `<REVIEW-ID>-EP-NNN`

Pack versions shall append:

> `-vMAJOR.MINOR`

No pack identifier or version is assigned by this Specification.

## 5. Required Pack Structure

Each future pack shall contain:

1. **Pack Control Record**
   - pack identifier;
   - type;
   - title;
   - review identifier;
   - related domain, RQs, and future session where applicable;
   - owner, custodian, validator;
   - version and state;
   - creation, freeze, and validation dates.
2. **Manifest**
   - ordered pack items;
   - Evidence Record IDs;
   - source references;
   - item versions;
   - hashes or equivalent integrity values;
   - evidence class;
   - admissibility status;
   - access status.
3. **Scope Statement**
   - purpose;
   - included evidence subjects;
   - exclusions;
   - known gaps;
   - intended use.
4. **Evidence Records**
   - Charter-compliant provenance and admissibility metadata.
5. **Source Materials or Stable References**
   - preserved copies where permitted;
   - stable location and access route otherwise.
6. **Relevant Extracts**
   - precise excerpts or internal references;
   - sufficient context;
   - copyright, confidentiality, or access constraints.
7. **Conflict and Limitation Log**
   - contradictions;
   - supersession;
   - uncertainty;
   - unavailable material;
   - rejected or conditional evidence.
8. **Traceability Map**
   - pack item to RQ;
   - RQ to domain;
   - later session and output links when they exist.
9. **Validation Record**
   - checks;
   - defects;
   - disposition;
   - validator;
   - date.
10. **Change Log**
    - version;
    - change;
    - reason;
    - authority;
    - affected RQs;
    - revalidation effect.
11. **Integrity Manifest**
    - algorithm;
    - path or item;
    - digest;
    - generation date;
    - generator;
    - verification result.

## 6. Pack Lifecycle

| State | Meaning | Permitted Use |
|---|---|---|
| Candidate | Sources identified but not admitted | Inventory only |
| Assembly | Admitted evidence being collected and structured | Preparation only |
| Validation Pending | Assembly complete; checks not finished | No session use |
| Validated | Required checks pass | Eligible for freeze |
| Frozen | Version locked and integrity manifest recorded | Authorised session use after entry gate |
| Superseded | Later frozen version replaces it | Historical traceability only |
| Withdrawn | Pack removed from use with reason | Historical traceability only |
| Archived | Final preservation state | Audit and retention |

Only a `Frozen` pack may be used as the controlling pack in a future session.

## 7. Version Control

### 7.1 Draft Versions

- `0.MINOR` versions apply during assembly and pre-freeze validation.
- Every material change increments the minor version.
- Prior versions remain preserved.

### 7.2 Frozen Versions

- The first frozen version becomes `1.0`.
- A change after freeze requires a new version.
- Non-substantive metadata correction may increment the minor version only when no evidence meaning, content, admissibility, or RQ mapping changes.
- Any evidence addition, removal, replacement, altered extract, admissibility change, or changed integrity value increments the major version and requires re-freeze.

### 7.3 No In-Place Mutation

A frozen pack shall never be overwritten. Corrections shall produce a successor version linked to the predecessor.

## 8. Admissibility Checks

Each pack item shall pass or receive an explicit disposition against:

1. source identity;
2. provenance;
3. integrity;
4. authority;
5. relevance to a future RQ;
6. temporal applicability;
7. accessibility;
8. confidentiality, legal, privacy, and security treatment;
9. contradiction and supersession;
10. uncertainty;
11. intended use;
12. retention route.

Permitted dispositions:

- Admitted;
- Conditionally Admitted;
- Context Only;
- Rejected;
- Access Pending;
- Superseded.

Conditional admission shall state the condition and permitted reliance.

## 9. Evidence Pack Assembly Procedure

During future authorised execution:

1. identify pack purpose and scope;
2. identify relevant admitted RQs;
3. inventory candidate sources;
4. create or validate Evidence Records;
5. perform admissibility checks;
6. collect permitted source copies or stable references;
7. prepare extracts with context;
8. record conflicts and gaps;
9. build the manifest and traceability map;
10. generate draft integrity values;
11. complete pack validation;
12. resolve or disclose defects;
13. initiate freeze.

This procedure is not executed by FEF-WPK-001G.

## 10. Freeze Procedure

A future pack freeze shall:

1. confirm pack scope and RQs;
2. confirm every item’s admissibility state;
3. close the assembly version;
4. generate the final ordered manifest;
5. generate SHA-256 digests for preserved digital items where technically possible;
6. record stable reference metadata for non-preserved sources;
7. fingerprint the manifest itself;
8. record freeze authority, custodian, validator, date, and version;
9. mark the pack `Frozen`;
10. prohibit in-place edits;
11. record the frozen pack in the future Evidence Pack Register;
12. cite the frozen version in the future session entry record.

A freeze confirms pack integrity and readiness, not the truth of every source or the outcome of review analysis.

## 11. Update Procedure

### 11.1 Pre-Freeze Update

Update the draft version, change log, affected RQ mappings, and validation state.

### 11.2 Post-Freeze Update

When new evidence or a correction is required:

1. preserve the frozen pack;
2. open a successor version;
3. state the update trigger;
4. identify changed items;
5. reassess admissibility;
6. update conflicts, limitations, and traceability;
7. assess session and output impact;
8. revalidate;
9. re-freeze;
10. notify affected review roles.

### 11.3 Supplemental Pack

When time or access constraints make full pack replacement disproportionate, a Supplemental Pack may be prepared. It must:

- identify the parent frozen pack;
- contain only newly admitted or corrected material;
- meet all validation and freeze controls;
- state whether reliance on the parent changes;
- be cited explicitly in the session record.

No material may be introduced informally during a session.

## 12. Integrity Verification

### 12.1 Digital Material

Use SHA-256 where technically possible. Record:

- exact file or object;
- digest;
- algorithm;
- date;
- tool or method;
- verification result.

### 12.2 External or Non-Preserved Material

Record:

- stable URL or source location;
- title;
- issuer or custodian;
- version and date;
- access date;
- access limitation;
- available revision or checksum;
- preserved excerpt reference;
- reason the source is not stored.

### 12.3 Verification Points

Integrity shall be checked:

- at acquisition;
- at freeze;
- at session entry;
- after transfer or repository movement;
- during final review assembly.

A mismatch is a Critical quality defect until resolved or bounded by attributable authority.

## 13. Traceability Requirements

Each manifest item shall map to:

- Evidence Record;
- pack;
- RQ;
- domain;
- future session when assigned;
- GF or non-finding after creation;
- FD decision extract when used;
- Open Question or Constitutional Candidate when applicable.

No future GF shall cite a pack alone without identifying the supporting Evidence Records or precise sources.

## 14. Access and Confidentiality

Packs shall:

- record access classification;
- separate restricted source copies from unrestricted metadata where needed;
- avoid reproducing sensitive content unnecessarily;
- preserve lawful access constraints;
- record who accessed or validated restricted material where required;
- identify redaction and its effect on reliance.

Access restriction does not make evidence inadmissible automatically, but it must be visible and may limit validation.

## 15. Quality Checks

Before freeze, confirm:

- manifest completeness;
- no orphan source;
- no unresolved duplicate identity;
- all hashes and versions recorded;
- all RQ mappings valid;
- all conditional and rejected items visible;
- known contrary evidence present;
- extracts have sufficient context;
- pack scope does not exceed session purpose;
- access and retention controls are stated;
- change log is complete.

## 16. Specification Non-Effects

FEF-EPS-001 does not:

- create an Evidence Record;
- assemble, validate, or freeze an Evidence Pack;
- admit or reject a source;
- assign a review, pack, session, or RQ identifier;
- commence review execution;
- create a GF, FD, or Constitutional Candidate.
