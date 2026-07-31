# FEF-FGR-002-EP-005-PMCR-001 — EP-005 Provenance and Membership-Control Remediation Record

| Control Field | Recorded Value |
|---|---|
| Record identifier | FEF-FGR-002-EP-005-PMCR-001 |
| Review identifier | FEF-FGR-002 |
| Domain | D5 — Governance Lifecycle and Evolution |
| Affected pack | FEF-FGR-002-EP-005 v1.0 — Frozen |
| Successor opened | FEF-FGR-002-EP-005 v2.0 — Validation Pending |
| Remediation date | 2026-07-31 |
| Entry baseline | `114617edeb363210b643d4437301a862ce2c1c88` |
| Preparation capacities | FEF-FGR-002-RA-002 — Review Administrator; RA-005 — Evidence Custodian |
| Validation arrangement | Future RA-006 validation under disclosed non-independent combination; not performed by this record |
| Remediation outcome | **Successor Prepared — Revalidation and Re-Freeze Required** |

## 1. Purpose and Authority

The Founder accepted the D5 DG-4 integrity stop, confirmed that DG-4 did not complete and produced no verdict, and authorised a bounded remediation of the frozen EP-005 provenance and membership-control defect.

This record determines and implements the methodology-compliant correction mechanism without modifying frozen EP-005 v1.0 or its companion Manifest. It does not perform remediation revalidation or re-freeze, resume DG-4, allocate S05, create or open a session, authorise examination, answer an RQ, create an examination finding, close D5, or commence D6/D7.

## 2. Method Determination

| Method control | Requirement | Application |
|---|---|---|
| FEF-EPS-001 §7.2 | A changed integrity value after freeze increments the major version and requires re-freeze | The membership fingerprint changes; successor version is v2.0 |
| FEF-EPS-001 §7.3 | A frozen pack is never overwritten; corrections produce a linked successor | v1.0 and MAN-001 remain byte-identical; v2.0 and MAN-002 are new files |
| FEF-EPS-001 §11.2 | Preserve predecessor; open successor; state trigger; identify changed items; reassess treatment and impact; revalidate; re-freeze; notify roles | Construction and impact steps are completed here; revalidation and re-freeze remain separately authorised |
| FEF-EPS-001 §11.3 | A Supplemental Pack is proportionate for newly admitted or corrected material when full replacement is disproportionate | Not selected: the defect is inside the parent pack's own provenance and membership control, so a complete successor is required |
| FEF-EPS-001 §12.3 | Integrity is checked at acquisition, freeze, and session entry; mismatch is Critical until resolved or bounded | The attempted DG-4 correctly stopped; v1.0 reliance remains blocked |
| FEF-FGRER-001 §§5.2, 6, 10, 15 | Failed validation preserves the failed version, identifies correction authority, blocks the gate, and requires revalidation | Historical records are preserved and DG-4 remains incomplete |

**Selected mechanism:** same pack identity, successor major version `FEF-FGR-002-EP-005 v2.0`, complete successor Manifest `FEF-FGR-002-EP-005-MAN-002`, Validation Pending until separately authorised revalidation and DG-3 re-freeze.

## 3. Confirmed Defect and Discovery

The attempted D5 DG-4 Session-Entry Validation performed its required source-currency and integrity check and found that EP-005 v1.0 §6.1 labels the wrong EV-072 pair as the two D5 acquisition inputs:

| D5 use | Qualification record | Correct SHA-256 | v1.0 selected |
|---|---|---|---|
| RQ-032, Execution Loop 001 | FEF-FGR-002-D5-RQ032-EMQR-001 | `c26de951d3a14d10954505bb035ac7dd38e2c2ae0c1b521c0907c009a8beb8ac` | D4 digest `31807d1de36002ebf359348bea764f8711476405de5c08669f0586c48853502d` |
| RQ-034, Execution Loop 003 | FEF-FGR-002-D5-RQ034-EMQR-001 | `543ec7643017f6a2e8fc4bd2eb5a4681e1056814786049b0d63b1296a4a99a98` | RQ-032 digest `c26de951d3a14d10954505bb035ac7dd38e2c2ae0c1b521c0907c009a8beb8ac` |

The v1.0 membership fingerprint therefore reproduces its documented input but does not represent the two controlling D5 qualification acquisitions for EV-072.

## 4. Historical EV-072 Provenance Reconstruction

All three objects were read directly from Git using the exact controlled path `docs/programme/FEF-DOCUMENT-MANIFEST.md` and hashed as raw object content with SHA-256. No current live file was substituted.

| Acquisition | Commit | Full SHA-256 | Result |
|---|---|---|---|
| D4 RQ-025 | `533b694d75db4a3377edc7a6dccf5ec2b41ebbd5` | `31807d1de36002ebf359348bea764f8711476405de5c08669f0586c48853502d` | Reproduced; historical D4 input only |
| D5 RQ-032 | `bb47b0bc514f9f147b37b7131720cbca5590f800` | `c26de951d3a14d10954505bb035ac7dd38e2c2ae0c1b521c0907c009a8beb8ac` | Reproduced; first D5 input |
| D5 RQ-034 | `42de97ed065f44f7e89cf6c32637f0aacaee93df` | `543ec7643017f6a2e8fc4bd2eb5a4681e1056814786049b0d63b1296a4a99a98` | Reproduced; second D5 input |

The D5 inputs are distinct and ordered by their controlling Execution Loops: RQ-032 first, RQ-034 second.

## 5. Why FFICR-001 and FFICVR-001 Did Not Correct This Defect

FFICR-001 and FFICVR-001 addressed a different integrity layer: FR-001 v1.0 and VR-001 v1.0 had described assembly-state whole-file hashes as frozen-state whole-file hashes. They correctly preserved EP-005 bytes and corrected FR-001/VR-001 to the actual frozen whole-file hashes.

Their membership check treated the membership ledger already printed in EP-005 as the input authority and verified that its digest was reproducible and unaffected by freeze annotations. They did not independently compare the EV-072 special-evidence pair against both controlling D5 EMQR acquisition rows and the corresponding historical Git objects. Their statements that special-evidence provenance was unchanged were therefore internally consistent with the frozen pack but incomplete against the underlying qualification records. This newly evidenced gap does not invalidate the corrected whole-file fingerprints; it requires a successor because the pack's provenance input and membership fingerprint themselves change.

## 6. Canonical Membership Reconstruction

The canonical algorithm is SHA-256 over 25 ordered lines of `EV-NNN:<digest>`, with dual acquisition digests joined by `|` in acquisition order and a trailing newline.

The complete ledger is recorded verbatim in successor Pack v2.0 §9.1. The reconstruction:

- preserves the same 25 Evidence Record identifiers and order;
- replaces only EV-072's wrongly selected pair with the verified D5 pair;
- preserves EV-080's two acquisition inputs in their established order;
- preserves every other recorded qualification digest; and
- preserves 41 source-to-RQ mappings, 42 source-to-requirement links, and 24 requirements.

| Fingerprint state | SHA-256 | Treatment |
|---|---|---|
| Frozen v1.0 membership fingerprint | `59414d0803ed114171c35a821d4581a80e8df92121260d868eaee4fd76e925fc` | Historical; reliance blocked; not relabelled as corrected |
| Prior diagnostic reconstruction | `c3a88eb9cbb2c8e4b38ee18cdc9c5f92a11087dcfd2ea66a32ea668766571a0f` | Diagnostic only before this remediation |
| Governed v2.0 reconstructed candidate | `c3a88eb9cbb2c8e4b38ee18cdc9c5f92a11087dcfd2ea66a32ea668766571a0f` | Reproduced twice during construction; remains non-controlling until formal revalidation and re-freeze |

Agreement with the diagnostic value was observed, not forced.

### 6.1 Successor Construction-State Integrity

| Artefact | Construction-state SHA-256 | Treatment |
|---|---|---|
| EP-005 v2.0 successor pack | `5595bee43f5b88c4d3536371f498b5bd7b84b1808c9b2307a5a0136dbf134dc6` | Candidate construction control; not a frozen fingerprint |
| EP-005-MAN-002 successor manifest | `38705706c03026325d86467282ef28e9931567c7a469e55069a5a1974c418827` | Candidate construction control; not a frozen fingerprint |

These values allow the separately authorised remediation revalidation to
verify the exact submitted successor files before any lifecycle annotations
or freeze action. They do not replace future frozen-state fingerprints.

## 7. Independent Reproduction

Two implementations reproduced the same candidate fingerprint:

1. a Node.js SHA-256 calculation built from manifest-parsed static digests plus the historically verified EV-072 and EV-080 dual inputs; and
2. the system `shasum -a 256` implementation over the literal 25-line successor ledger, including its trailing newline.

Both produced `c3a88eb9cbb2c8e4b38ee18cdc9c5f92a11087dcfd2ea66a32ea668766571a0f`. This construction check is not the separately authorised RA-006 remediation revalidation.

## 8. Treatment and Impact Assessment

| Control | Impact |
|---|---|
| Evidence membership identity/count | None — same 25 Evidence Records |
| Evidence class/admissibility | None — EV-013 and EV-072 remain Conditionally Admitted; EV-014 remains Context Only |
| Qualification | None — correction aligns the pack to existing qualification records |
| RQ/requirement mappings | None — 41/42/24 preserved |
| Limitations/uncertainty/permitted use | None |
| Open Questions | None — eight mappings remain open and unchanged |
| RQ wording/state | None — RQ-032 through RQ-037 remain Admitted, Pending, Unexamined |
| D6/D7 boundaries | None — both uncommenced |
| DG-4 | Incomplete; stopped at integrity check; no verdict |
| Session/examination | S05 unallocated; no session; examination unauthorised and uncommenced |

No expanded substantive impact was identified.

## 9. Predecessor and Successor Control

| Version | State | Controlling treatment |
|---|---|---|
| EP-005 v1.0 / MAN-001 | Frozen historical predecessor; byte-preserved | Whole-file and membership fingerprints remain discoverable historical controls; blocked from session reliance because of the EV-072 defect |
| EP-005 v2.0 / MAN-002 | Validation Pending — Not Frozen | Corrected successor candidate; not controlling and not usable until separately authorised revalidation and re-freeze |

There is no point at which both membership fingerprints are represented as current controlling values. At this stage no EP-005 version is eligible to support DG-4: v1.0 is integrity-blocked and v2.0 is not Frozen.

## 10. Records and Programme Synchronisation

This remediation creates:

- FEF-FGR-002-EP-005 v2.0 successor Evidence Pack;
- FEF-FGR-002-EP-005-MAN-002 successor Manifest; and
- this PMCR-001 remediation record.

It updates only the Evidence Pack Register, Review Identity, Master Programme, Founder Dashboard, and Document Manifest to register the successor and current blocked lifecycle state. Historical PFSERR-001, qualification records, FR-001, VR-001, FFICR-001, and FFICVR-001 remain unchanged.

## 11. Non-Effects

This remediation does not modify or refreeze v1.0, complete validation, issue a validation verdict, perform or resume DG-4, allocate S05, create or open a session, authorise or commence examination, answer an RQ, create a Governance Finding or Founder Decision, close D5, commence D6/D7, modify FRAS, perform Framework Evolution, or affect constitutional material.

## 12. Outcome and Next Governed Activity

**Outcome: Successor Prepared — Revalidation and Re-Freeze Required.**

The next governed activity is Founder review and separate authorisation of remediation revalidation. If that validation passes, a separately authorised DG-3 action may re-freeze successor v2.0 and establish its whole-file, manifest, and membership fingerprints as the sole current controlling set. DG-4 remains blocked until that sequence is complete and separately reauthorised.
