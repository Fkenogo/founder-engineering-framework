# FEF-FGR-002 — D3 Quarantine Manifest (2026-07-25)

| Control Field | Recorded Value |
|---|---|
| Manifest identifier | FEF-FGR-002-D3-QM-001 |
| Review identifier | FEF-FGR-002 |
| Domain | D3 — Governance Assurance |
| Quarantine date | 2026-07-25 |
| Quarantine authority | Attributable Founder task — repository governance recovery (this task) |
| Preceding record | Read-only D3 provenance and content investigation (this session) |
| Restored baseline reference | FEF-FGR-002-D3-MOB-001 (Mobilised); FEF-FGR-002-D3-RQC-001 (9 candidates prepared); FEF-FGR-002-D3-RQC-VALIDATION-REPORT (Pass with Conditions) |
| Effect of this manifest | None. Quarantine preserves material for possible future reuse after proper Founder authorisation. It does not judge technical quality, admit anything, register evidence, or create constitutional effect. |

## 1. Purpose

This manifest records, for full traceability, every artefact and tracked-file
change produced beyond the last Founder-authorised D3 boundary
(mobilisation complete; candidates prepared and validated Pass with
Conditions; Founder review and DG-2 admission not performed; evidence
mobilisation and registration not authorised). Nothing described here is
destroyed. Everything is preserved in this directory or in the accompanying
patch file for possible future reuse once a genuine Founder-authorised DG-2
admission and evidence-mobilisation gate is run.

## 2. Quarantined Documents (moved into this directory)

| Original filename | Claimed identifier / version | Claimed status | Claimed governance action | Depends on |
|---|---|---|---|---|
| `FEF-FGR-002-D3-RQ-VALIDATION-AND-ADMISSION-RECORD.md` | FEF-FGR-002-D3-RQVA-001 v1.0 | DG-2 Admit — Pass with disclosed non-independent condition | Allocates canonical `FEF-FGR-002-RQ-016` through `RQ-024`; declares DG-2 admission under capacity FEF-FGR-002-RA-002 | FEF-FGR-002-D3-RQC-001; FEF-FGR-002-D3-RQC-VALIDATION-REPORT |
| `FEF-FGR-002-D3-EVIDENCE-REQUIREMENT-MATRIX.md` | FEF-FGR-002-D3-ERM-001 v1.0 | Pass with Conditions | Derives 22 evidence-requirement references (D3-ERQ-01–22) from RQ-016–024 | FEF-FGR-002-D3-RQVA-001 |
| `FEF-FGR-002-D3-CANDIDATE-EVIDENCE-INVENTORY-AND-QUALIFICATION-RECORD.md` | FEF-FGR-002-D3-CEIQR-001 v1.0 | 31 Sources Qualified | Qualifies 31 candidate sources; 13 reused + 18 new Evidence Records (EV-032–EV-049) | FEF-FGR-002-D3-ERM-001 |
| `FEF-FGR-002-D3-EVIDENCE-REGISTRATION-AND-RQ-MAPPING-RECORD.md` | FEF-FGR-002-D3-ERRM-001 v1.0 | Ready with Conditions | Registers 31 D3 Evidence Records and maps them to RQ-016–024; source of the canonical register mutations below | FEF-FGR-002-D3-CEIQR-001 |
| `FEF-FGR-002-D3-EVIDENCE-MOBILISATION-VALIDATION-REPORT.md` | FEF-FGR-002-D3-EMVR-001 v1.0 | Pass with Conditions | Validates the requirement/qualification/registration package as a whole | FEF-FGR-002-D3-ERM-001; -CEIQR-001; -ERRM-001 |
| `FEF-FGR-002-D3-REVIEW-QUESTION-SET.md` | FEF-FGR-002-D3-RQS-001 v1.1 | Nine RQs Validated and Admitted through DG-2 | Canonical RQ-016–024 with full FEF-RQS-001 mandatory fields and evidence linkages | FEF-FGR-002-D3-RQVA-001; -ERRM-001 |

None of these six documents is backed by a distinct Founder Decision record
(no `FEF-FGR-002-FD-0NN` exists for D3), unlike every substantive D1/D2
action. The stated "admission authority" and "validator" in each case are
capacities held by the same acting agent that prepared the material.

## 3. Preserved Tracked-File Deltas

The exact diff of the following seven tracked files, as they stood
immediately before this quarantine/restoration action, is preserved verbatim
in
[FEF-FGR-002-D3-QUARANTINE-TRACKED-FILE-DIFFS.patch](FEF-FGR-002-D3-QUARANTINE-TRACKED-FILE-DIFFS.patch):

- `README.md`
- `docs/governance/reviews/FEF-FGR-002/FEF-FGR-002-EVIDENCE-REGISTER.md`
- `docs/governance/reviews/FEF-FGR-002/FEF-FGR-002-REVIEW-IDENTITY.md`
- `docs/governance/reviews/FEF-FGR-002/FEF-FGR-002-REVIEW-QUESTION-REGISTER.md`
- `docs/programme/FEF-DOCUMENT-MANIFEST.md`
- `docs/programme/FEF-FOUNDER-DASHBOARD.md`
- `docs/programme/FEF-MASTER-PROGRAMME.md`

Each of these seven files is being restored (this task) to accurately
reflect the authorised boundary state. The patch file above is the sole
record of the unauthorised state they briefly held (D3 RQ-016–024 "Admitted";
49 total Evidence Records including EV-032–049 mapped to D3). It can be used
to fully reconstruct that state if a future, properly authorised DG-2
admission and evidence-mobilisation gate reaches the same or a revised
conclusion.

## 4. Documents Remaining Active (Working Baseline)

The following remain in the active repository directory, outside quarantine,
because they fall within the last Founder-authorised D3 boundary:

- `FEF-FGR-002-D3-MOB-001-GOVERNANCE-ASSURANCE-MOBILISATION-RECORD.md` — D3 Mobilised
- `FEF-FGR-002-D3-RQC-001-GOVERNANCE-ASSURANCE-REVIEW-QUESTION-CANDIDATE-SET.md` — 9 temporary candidates prepared
- `FEF-FGR-002-D3-RQC-VALIDATION-REPORT.md` — Pass with Conditions

## 5. Non-Effects

This manifest and the quarantine action it records do not:

- delete any artefact;
- admit, answer, or reject a Review Question;
- allocate, revoke, or reuse a canonical RQ or Evidence Record identifier;
- register, qualify, or weigh evidence;
- create or freeze an Evidence Pack;
- create a Governance Finding or Founder Decision;
- modify an Open Question;
- create constitutional effect; or
- judge the technical quality or future validity of the quarantined material.

## 6. Reuse Path

Future reuse of any quarantined document requires: a genuine Founder-authorised
DG-2 admission gate (not a self-labelled operational capacity), re-validation
of currency against whatever D3 candidate set is active at that time, and a
fresh collision-safe identifier check before any canonical RQ or Evidence
Record identifier is reallocated. The identifiers `FEF-FGR-002-RQ-016` through
`RQ-024` and `EV-032` through `EV-049` are treated as **not currently
allocated** in the active registers as of this restoration; a future
authorised admission may reuse or renumber them.
