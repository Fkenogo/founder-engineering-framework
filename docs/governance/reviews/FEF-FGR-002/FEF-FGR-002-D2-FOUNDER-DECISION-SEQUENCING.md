# FEF-FGR-002 — D2 Founder Decision Sequencing

| Control Field | Recorded Value |
|---|---|
| Record identifier | FEF-FGR-002-D2-FDS-001 |
| Review identifier | FEF-FGR-002 |
| Source findings | GF-009 through GF-014 |
| Version | 1.0 |
| Status | Recommended Consideration Order Only |
| Founder Decisions created | 0 |

## 1. Purpose

This record recommends an order for Founder consideration. It does not select
a disposition, draft a decision, combine findings, or create substantive
precedence.

## 2. Recommended Order

| Order | Finding | Sequencing Rationale |
|---:|---|---|
| 1 | GF-009 — Evidence Qualification Controls Permitted Reliance | Establishes whether and for what purpose a source may be relied upon. |
| 2 | GF-010 — Evidence Class Does Not Automatically Determine Weight | Establishes the judgement boundary for qualified evidence before conflict enters the sufficiency gate. |
| 3 | GF-011 — Sufficiency Requires Explicit Gap, Conflict, and Stop Treatment | Determines whether the qualified, weighted evidence set permits a bounded conclusion or requires a stop. |
| 4 | GF-012 — Frozen Evidence Baselines Require Versioned Change Control | Establishes the stable baseline needed for later traceability and reuse. |
| 5 | GF-013 — Traceability and Reuse Must Preserve Source Authority | Controls how the frozen source is used and reused without authority elevation. |
| 6 | GF-014 — Evidence Custody Is Operational and Does Not Decide Meaning | Confirms the operational responsibility supporting qualification, freeze, and traceability while preserving D3/D4 boundaries. |

## 3. GF-010 Versus GF-011

GF-011 could precede GF-010 because sufficiency is the broader proceed/stop
gate and includes conflict as one input. The default order remains GF-010
before GF-011 because:

1. GF-009 first determines permitted reliance.
2. GF-010 then separates class and weight from automated judgement.
3. GF-011 applies that bounded judgement, together with coverage, gaps,
   limitations, and conflict, to a proposition-specific proceed/stop treatment.

This order reduces the risk that “sufficiency” is read as an automatic score.
Reversing GF-010 and GF-011 would not be invalid if the Founder keeps both
questions distinct.

## 4. Dependency Chains

```text
GF-009 → GF-010 → GF-011
GF-012 → GF-013
GF-009 + GF-012 + GF-013 → GF-014 operational context
```

- GF-009 is the prerequisite for both weight and sufficiency.
- GF-010 and GF-011 should be considered in the same review window but remain
  separately dispositioned.
- GF-012 should precede GF-013 because lineage requires a stable baseline.
- GF-014 is best considered after the substantive controls it operationally
  supports are understood.

## 5. Coordinated Consideration Without Combination

The Founder may consider these pairs together for context:

- GF-009 and GF-011 — qualification versus sufficiency;
- GF-010 and GF-011 — judgement versus proceed/stop treatment;
- GF-012 and GF-013 — freeze versus traceability;
- GF-014 with GF-009, GF-012, and GF-013 — custody support.

Each finding must retain a separate attributable disposition because the
evidence, risks, conditions, and later-domain effects differ.

## 6. Non-Effects

This sequencing:

- is not substantive approval;
- creates no Founder Decision or identifier;
- does not constrain the Founder’s selected consideration order;
- modifies no finding or Open Question;
- creates no constitutional effect;
- does not authorise downstream work.
