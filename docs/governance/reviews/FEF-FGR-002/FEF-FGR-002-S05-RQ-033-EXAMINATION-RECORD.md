# FEF-FGR-002-S05 — RQ-033 Examination Record

| Control Field | Recorded Value |
|---|---|
| Record identifier | FEF-FGR-002-S05-RQ-033-ER-001 |
| Review identifier | FEF-FGR-002 |
| Session identifier | FEF-FGR-002-S05 |
| Activity | **S05 Evidence Examination Loop 002 — RQ-033 Only** |
| Domain | D5 — Governance Lifecycle and Evolution |
| Examined RQ | FEF-FGR-002-RQ-033 — Applicability and Transitional Effect |
| Examination date | 2026-08-01 |
| Entry repository baseline | `a5749a9b56216fd7be1dcb98d0aceb00e5295dd9` |
| Evidence baseline | FEF-FGR-002-EP-005 v2.0 and MAN-002 — Frozen; no other evidence used |
| Analyst capacity | FEF-FGR-002-RA-003 — Review Analyst |
| Recorder capacity | FEF-FGR-002-RA-004 — Review Recorder |
| Independence | Non-independent operational combination disclosed (RA-002–RA-006) |
| Output | One candidate Governance Finding — FEF-FGR-002-GF-032 |
| Validation | FEF-FGR-002-S05-GF-032-VR-001 — Pass with Conditions |

This is S05's second evidence-examination loop. It is distinct from the
historical **D5 Evidence Mobilisation Loop 002**, which qualified evidence for
RQ-033 without examining or answering it. Loop 001 for RQ-032 and GF-031
remain unchanged.

## 1. RQ Load and Authority Boundary

### Exact Question

> When a FEF governance instrument is approved, amended, or withdrawn, does
> it apply retrospectively to work already underway, only to work commenced
> after its effective date, or under some other transitional rule, and who
> decides which rule applies?

The Founder accepted FEF-FGR-002-S05-RQ-032-ER-001 and
FEF-FGR-002-S05-GF-031-VR-001 without dispositioning GF-031, authorised a
bounded live-state correction, and authorised this loop for RQ-033 only after
the correction and ordinary entry checks passed. The authority permits one
RQ-033 examination record, no more than one candidate Governance Finding,
validation, and directly required control synchronisation. It does not permit
disposition of GF-031 or GF-032, a Founder Decision, examination of RQ-034
through RQ-037, session or domain closure, or D6/D7 commencement.

The mandatory pre-examination synchronisation was completed and checked before
analysis. It corrected stale current-state wording in the Master Programme,
D5 Review Question Set, Review Question Register, and the directly conflicting
Session Register summary. Review Identity, the Founder Dashboard, and Document
Manifest were synchronised. The Master Programme's stale header v0.75 was
reconciled to its already recorded v0.76 state before the correction advanced
it to v0.77. Historical version and event narratives remain unchanged.

The four Founder mobilisation conditions, seven PFSERR-002 conditions, S05
entry/opening conditions, and all Loop 001 validation conditions remain
binding. RA-002 retains session administration, RA-003 analysis, RA-004
recording, RA-005 evidence custody, and RA-006 validation in the disclosed
combined capacity. D1 Founder-reserved authority, the D3/D4 dependencies, the
neutral-before-disposition control, and the uncommenced D6/D7 interfaces are
preserved.

### Exact Mapped Evidence

Only the eight RQ-033 records frozen in EP-005 v2.0 were loaded:

- EV-009 — FEF-FAR-001 Founder Architectural Review;
- EV-010 — FEF-FAR-002 Programme Governance Pilot;
- EV-012 — FEF-WPK-001 Open Questions Register;
- EV-013 — FEF-RGS-000 Research Governance Standard;
- EV-070 — FD-015 Evidence Traceability and Controlled Reuse;
- EV-073 — D3 Governance Assurance Traceability Register;
- EV-078 — D3 Quarantine Manifest; and
- EV-079 — D3-C1 Corrected Admission-Readiness Checkpoint.

No live administrative version or unmapped evidence was substituted for a
governed acquisition object.

## 2. Evidence Qualifications Preserved

| Evidence | Treatment during examination |
|---|---|
| EV-009 | E2 Admitted; one scoped Founder architectural decision record only; its absent approval/effective date and current-constraint treatment do not establish a general rule |
| EV-010 | E2 Admitted; one bounded Founder-approved pilot example only; its event-based commencement trigger does not govern other instruments or underway work |
| EV-012 | E2 Admitted; used only for OQ-017's exact wording and open Founder-owned transition-decision state, not as an answer |
| EV-013 | E2 Conditionally Admitted; used only for its `Draft v0.2`, `Not Approved`, and `Effective date: None` state; proposed content is not authority |
| EV-070 | E1 Admitted; used only for mandatory version/source/authority traceability and controlled reuse; it states no transitional-applicability rule |
| EV-073 | E4 Admitted; one D3 version-stamped traceability example only; not a universal or current-state model |
| EV-078 | E1 Admitted; correction/recovery example only, never an ordinary amendment precedent; prior unauthorised work and restored control state remain distinguishable |
| EV-079 | E1 Admitted; one explicit correction/supersession-for-active-reliance example only; it corrects an inaccurate claim rather than amending a valid instrument |

Pack inclusion was not treated as truth, sufficiency, adequacy,
recommendation, or an answer. OQ-017 remains open and unchanged. No
transition rule is adopted or applied to FEF-RGS-000.

### 2.1 Integrity and Source Currency

At the actual Loop 002 gate:

- EP-005 v2.0 reproduced
  `d4504f3b1983d5076054b479b565d6dc758edadb239603b86347c608d09b8ada`;
- MAN-002 reproduced
  `ce6e5b40cbe1c52cf263ccaddd97d0c8461a77d3a71402fbdc7aad60f337ac52`;
- the canonical 25-line ledger reproduced membership fingerprint
  `c3a88eb9cbb2c8e4b38ee18cdc9c5f92a11087dcfd2ea66a32ea668766571a0f`;
- all 27 governed historical acquisition objects reproduced their recorded
  SHA-256 digests; and
- all eight RQ-033 live sources remained byte-identical to their governed
  acquisition objects.

No source was unavailable, superseded for its permitted use, or affected by a
currency change. No refresh, requalification, remapping, successor, or
Supplemental Pack was required. The corpus remained 25 Evidence Records, 41
source-to-RQ mappings, 42 source-to-requirement links, and 24 evidence
requirements. Frozen v1.0/MAN-001 remained historical, reliance-blocked, and
byte-identical to freeze commit `663297a1f9d194bf85fcad9cb98d5dfccd95b86f`.

## 3. Examination Results by Analytical Classification

### 3.1 Directly Established by Evidence

1. EV-009 records a scoped Founder architectural decision whose approval date
   was not supplied and to which no effective status or effective date was
   assigned. It treats the recorded decisions as current architectural
   constraints and direction, within their express boundaries.
2. EV-010 records a different bounded treatment: the Programme Governance
   pilot is Founder Approved for pilot architecture only, and its commencement
   is tied to completion and validation of FEF-WPK-001B.6 rather than a stated
   retrospective/prospective rule or distinct calendar effective date.
3. EV-012 records OQ-017 as open: whether an approved FEF-RGS-000 would apply
   to research already underway or only after its effective date requires a
   Founder transition decision and remains unresolved.
4. EV-013 records that FEF-RGS-000 is `Draft v0.2`, `Not Approved`, has no
   effective date, and creates no present authority. No transitional rule can
   validly be applied to it from the mapped evidence.
5. EV-070 requires controlled reuse to preserve source identity, version,
   authority, admissibility, limitations, and exact purpose through later
   outputs and decisions. It supports version-at-decision traceability, not a
   rule selecting retrospective or prospective effect.
6. EV-073 demonstrates one operated D3 chain with record and pack versions
   traced through RQ, evidence, session, finding, disposition, and Founder
   Decision. It does not record a transitional determination.
7. EV-078 records a Founder-authorised recovery in which work beyond the last
   authorised boundary was quarantined, active registers were restored, and
   the affected material was preserved for audit and potential later reuse.
   At that restoration point the unauthorised identifiers were treated as not
   currently allocated.
8. EV-079 records a correction in which a prior false D3-closure and authority
   claim was corrected in v1.1, the original remained preserved in history,
   and the correction superseded it for active reliance. The record expressly
   states that the claimed closure had never validly occurred.

### 3.2 Reasonably Supported

1. The mapped evidence reasonably supports decision-specific treatment rather
   than one demonstrated common rule: an undated current-constraint treatment
   in EV-009, an event-triggered pilot commencement in EV-010, and two
   retrospective corrective treatments for invalid or inaccurate prior states
   in EV-078 and EV-079.
2. The evidence reasonably supports preservation of the version and authority
   context under which work occurred. EV-070 supplies the attributable
   traceability requirement and EV-073 demonstrates it in one closed domain.
3. The Founder is the evidenced authority for the scoped architectural and
   recovery examples and is the recorded owner of OQ-017's unresolved
   transition decision. No mapped source records a delegated non-Founder
   selection of a transitional rule.

### 3.3 Unsupported

The mapped evidence does not support:

- a universal prospective-only, retrospective, or hybrid applicability rule;
- a default rule for valid work already underway when an approved instrument
  is later amended or withdrawn;
- treating absence of a retrospective statement as proof of prospective-only
  effect;
- extending EV-078 or EV-079 from defect correction to an ordinary amendment
  of a valid, effective instrument;
- an approved distinction between approval date, record date, decision date,
  and effective date across FEF instruments;
- a general delegated-authority model for choosing transitional treatment; or
- application of any rule to FEF-RGS-000.

### 3.4 Contradictory or Qualifying Matters

No mapped source directly contradicts the bounded facts above. Material
qualifications prevent a general rule:

- EV-009 calls its decisions current constraints while assigning no effective
  date; that combination does not say how earlier or underway work is treated.
- EV-010 has an event-based commencement trigger, but it is one pilot-specific
  condition and says nothing about retrospective effect or grandfathering.
- EV-078 and EV-079 show retrospective corrective effects for invalid or
  inaccurate states, but neither is an ordinary amendment or withdrawal of a
  valid, effective instrument.
- EV-013 is not approved and cannot supply current governance content.

### 3.5 Uncertain

It remains uncertain what default, exception, or decision procedure should
apply to valid work underway when a governance instrument is approved,
amended, or withdrawn; whether approval and effective dates should differ; and
whether any non-Founder capacity may select a rule. OQ-017 records the most
direct unresolved instance. Absence of a delegated example is not evidence
that delegation is impossible or prohibited.

### 3.6 Outside Scope

This loop does not adopt or recommend a retrospective, prospective, hybrid,
grandfathering, correction, or withdrawal rule; amend or apply a rule to
FEF-RGS-000; decide RQ-034 through RQ-037; design D6 effective-date tracking;
define a D7 constitutional transition; disposition GF-031; or commence
Framework Evolution.

## 4. Gap and Open-Question Assessment

| Gap or open matter | Treatment |
|---|---|
| No approved general transitional-applicability rule | Preserved as the principal evidence gap; no rule inferred or adopted |
| No ordinary-amendment/withdrawal example for a valid effective instrument | Preserved as untested; correction precedents not substituted |
| No common approval-date/effective-date distinction | Preserved; single-date and event-trigger examples not generalised |
| No delegated transitional-rule selection example | Preserved as an evidence gap; absence not treated as prohibition |
| OQ-017 | Remains open and unchanged; linked directly to the finding without resolution or disposition |
| Non-independent examination and validation | Disclosed; exact mapping, historical-object replay, source-currency checks, and analytical classification used as compensating controls |

## 5. Examination Conclusion

The evidence answers RQ-033 only at a bounded finding level. It establishes
that FEF records have used different, expressly scoped treatments: current
architectural constraints without an assigned effective date, an event-based
pilot commencement trigger, and retrospective correction of invalid or
inaccurate prior states while preserving history. Those examples do not
establish a general rule for approval, ordinary amendment, withdrawal, or
valid work already underway. Founder authority is evidenced for the bounded
examples and OQ-017 assigns the unresolved transition decision to the Founder;
no delegated rule-selection model is evidenced.

One candidate Governance Finding, FEF-FGR-002-GF-032, records this bounded
examples-and-gap conclusion. It embeds no transition rule, recommendation,
Founder disposition, or decision.

## 6. Validation and Compensating Controls

The same combined acting capacity performed analysis, recording, and
validation. Validation is not independent. Compensating controls were:

- mandatory live-state correction and intermediate entry validation before
  analysis;
- exact frozen pack, manifest, and membership-fingerprint reproduction;
- all-27 acquisition replay and exact eight-record RQ-033 mapping enforcement;
- live source-currency comparison against each governed RQ-033 acquisition;
- separate treatment of established, supported, unsupported,
  contradictory/qualifying, uncertain, and outside-scope matters;
- explicit preservation of EV-013, EV-078, OQ-017, D1, D6, and D7 boundaries;
  and
- post-edit protected-state, identifier, register, and contradiction checks.

## 7. Non-Effects

This record does not alter the historical D5 Evidence Mobilisation Loop 002;
modify either EP-005 version or manifest; change evidence identity,
membership, qualification, mapping, permitted use, or acquisition treatment;
change RQ wording or an Open Question; adopt or apply a transitional rule;
amend FEF-RGS-000; disposition GF-031 or GF-032; issue a Founder Decision;
examine RQ-034 through RQ-037; close S05 or D5; or commence D6 or D7.
