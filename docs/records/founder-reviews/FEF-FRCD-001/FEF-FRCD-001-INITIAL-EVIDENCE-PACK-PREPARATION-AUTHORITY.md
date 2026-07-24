# FEF-FRCD-001 — Initial Evidence Pack Preparation Authority

**Status:** Prepared Conditional Authority — Not Effective  
**Authority trigger:** Founder approval of FEF-FRCD-001  
**Evidence Records created:** 0  
**Evidence Packs assembled:** 0

## 1. Purpose

Define the limited authority and controls for preparing the first D1 Evidence Pack after review commencement.

This document does not currently grant effective preparation authority, register evidence, assemble a pack, freeze a pack, or admit a source.

## 2. Conditional Authority

After all conditions in Section 3 are satisfied, authorised evidence administration may:

- identify prospective sources relevant to admitted D1 Review Questions;
- register source metadata and provenance;
- perform admissibility checks;
- preserve admissible material or record controlled external references;
- assemble a draft Evidence Pack;
- submit the pack to freeze and integrity validation.

This authority does not allow evidence to be fabricated, inferred, silently transformed, or treated as dispositive without review.

## 3. Conditions Precedent

Evidence Pack preparation may begin only after:

1. the Founder approves FEF-FRCD-001;
2. the approval is recorded;
3. the review identifier is assigned;
4. the Evidence Register and Evidence Pack Register are instantiated and validated;
5. at least one D1 RQ is validly admitted;
6. FEF-EPS-001 is confirmed as the applicable specification;
7. evidence preparation and validation roles are recorded;
8. access, confidentiality, and preservation requirements are defined for the candidate material;
9. no applicable stop condition exists.

## 4. Preparation Rules

The first pack must:

- be scoped to admitted D1 RQs;
- contain a controlled manifest;
- distinguish included, excluded, unavailable, and superseded material;
- preserve source provenance;
- record acquisition method and date;
- record authenticity and integrity treatment;
- record admissibility results and limitations;
- preserve contradictory evidence and material uncertainty;
- separate source content from analysis;
- use version control;
- remain Draft until the freeze procedure passes.

## 5. Freeze Requirements

Before use in a review session, the pack must:

1. have a unique pack identifier derived from the assigned review identifier;
2. identify its exact RQ and domain scope;
3. contain a complete evidence manifest;
4. complete admissibility review for every included item;
5. document every exclusion and known gap;
6. record access and confidentiality treatment;
7. compute and record integrity fingerprints for preserved digital material;
8. record stable external references where preservation is not lawful or feasible;
9. record pack version and freeze timestamp;
10. receive independent freeze validation;
11. enter the Frozen lifecycle state;
12. prohibit in-place mutation.

## 6. Update Requirements

Before freeze, changes increment the draft version and preserve change history.

After freeze:

- the frozen version remains immutable;
- new material requires a supplemental pack or controlled replacement version;
- the reason, authority, affected RQs, and integrity values must be recorded;
- any session relying on the earlier pack must retain that exact reference;
- material changes may trigger RQ or session reopening.

## 7. Validation Requirements

The first pack must pass:

- identifier and version validation;
- manifest reconciliation;
- provenance completeness;
- admissibility validation;
- scope-to-RQ validation;
- duplicate and supersession checks;
- access and confidentiality validation;
- integrity verification;
- exclusion and evidence-gap validation;
- internal-link and location validation;
- independent freeze validation.

No failed control may be treated as passed through assumption.

## 8. Integrity Requirements

For preserved digital material:

- use SHA-256 or the controlled repository-equivalent fingerprint;
- record the fingerprint beside the exact evidence version;
- re-verify at freeze, pre-session use, and post-update use;
- stop use if verification fails until the discrepancy is resolved or explicitly dispositioned.

For external or non-preserved material:

- record the stable locator;
- record retrieval date and retrieval method;
- record publisher, custodian, or source authority;
- record version or observed state;
- preserve an extract only when permitted;
- document limitations and future availability risk.

## 9. Traceability Requirements

Every included evidence item must trace to:

- an Evidence Record;
- one or more admitted D1 RQs;
- the pack manifest;
- its provenance record;
- its admissibility result;
- its integrity or stable-reference record;
- every session in which it is used;
- every GF that later relies on it.

The absence of evidence must be recorded as a gap, not filled by inference.

## 10. Stop and Escalation Conditions

Preparation must stop or escalate when:

- commencement approval is absent or ambiguous;
- the review identifier or required registers are missing;
- no relevant RQ has been admitted;
- provenance is unavailable;
- authenticity or integrity is materially disputed;
- access or confidentiality requirements are unresolved;
- evidence appears altered without a controlled version history;
- a material conflict is omitted;
- freeze validation fails;
- use would breach an external obligation.

## 11. Current Non-Effects

This prepared authority:

- is not yet effective;
- registers no evidence;
- assembles no Evidence Pack;
- freezes no pack;
- admits no source;
- creates no review output.

