# Research Architecture

## Artifact stack

| ID | Artifact | Question answered |
|---|---|---|
| 00 | Corpus Coverage Register | What is inside the research field, and how deeply has it been examined? |
| 01 | Source and Transmission Register | What source supports an observation, and how is it genealogically related to other sources? |
| 02 | Immutable Research Event Ledger | What happened, in what order, and what was believed immediately beforehand? |
| 03 | Experiment Registry | What was tested, under what constraints, blindness, and null model? |
| 04 | Prediction Register | What was registered before the target evidence was inspected? |
| 05 | Evidence Ledger | What is the smallest source-supported observation? |
| 06 | Claim Evolution Ledger | How did each proposition change over time? |
| 07 | Residual/Failure Ledger | What remains unexplained, failed, contradicted, or deliberately withheld? |
| 08 | Scale-Transform Atlas | How does each locally typed system move between scales or states? |
| 09 | Provenance/Ancestry Graph | How do sources, tests, evidence, claims, and transforms depend on one another? |
| 10 | Carrier Atlas | How do music, sound, color, glyph, name, text, myth, and ritual carry relations? |
| 11 | Generative Ontology | What operator vocabulary survives the accumulated tests? |
| 12 | First-Level 72 | What 72-address result can be justified from the layers beneath it? |

## Typed transforms

The unit of comparison is:

`N[type A] --operator--> M[type B]`

not merely `N → M`.

A numerical change, role change, carrier change, regime change, and genealogical generation may coexist. They receive separate typed edges even when they occur in the same narrative.

## Coverage is not completion

Coverage state and claim strength are independent. A deeply studied corpus may falsify a claim. A queued corpus cannot support a claim merely because it appears on the research route.

## Storage versus presentation

The ledgers are normalized: one observation, revision, relation, or outlier per row. Human-facing atlas views may pivot those records into wide identity/function matrices. Display limits never delete underlying records.

## Reconstruction warning

The initial event history is reconstructed from preserved conversation and version deltas. Entries use `EV-R` IDs and explicit chronology-quality fields. Once exact archival timestamps are recovered, new reconciliation events should be appended; reconstructed rows should not be silently rewritten.
