# Data Dictionary and Integrity Rules

## Identifier namespaces

| Prefix | Entity |
|---|---|
| COR | Corpus branch |
| SRC | Source or source set |
| EV | Research event |
| EV-R | Reconstructed historical research event |
| EXP | Experiment |
| PRED | Registered prediction |
| EVD | Atomic evidence observation |
| CLM | Stable claim |
| RES | Residual or failed prediction |
| ST | Typed transform table |

## Referential rules

- Evidence rows may support or challenge multiple claims but must record the originating experiment when one exists.
- Claim revisions reuse the stable Claim ID and increment revision.
- An event may alter multiple claims; each claim revision names the event.
- Transform rows cite claim, evidence, and event IDs rather than repeating unsupported conclusions.
- Downstream checksums are labeled and contribute no independent-convergence vote.
- Exact citations are mandatory before an observation graduates from reconstructed research record to publication-grade evidence.
- Blank is not false. Use `UNKNOWN`, `NOT_APPLICABLE`, or `PENDING` where the distinction matters.

## Transform-table columns

| Field | Meaning |
|---|---|
| Sequence | Native order, not imposed comparison order |
| Tradition_System | Local system |
| Primary_Source_Layer | Source and recension |
| Upstream_Typed_Scale | Count plus object type |
| Upstream_Identity | Local identity |
| Upstream_Function | Local function |
| Operator | Typed transformation |
| Downstream_Typed_Scale | Result count plus object type |
| Downstream_Identity | Resulting identity/address |
| Downstream_Function | Resulting function |
| Inheritance | What persists |
| Loss_Addition | What disappears or appears |
| Role_Office | Kept separate from identity |
| Address_Domain | Planet, sign, decan, day, direction, realm, etc. |
| Orientation_Sequence | Forward/reverse, day/night, cycle offset, and similar |
| Hierarchy_Type | Authority, capability, process, succession, provenance, or address |
| Counterpart_Pair | Source-native counterpart only |
| Outlier | Non-peer, mediator, container, withheld, remnant, etc. |
| Carrier | Name, glyph, music, color, text, table, myth, ritual |
| Transmission_Status | Direct, plausible, independent, downstream, or unknown |
| Evidence_State | Current state without erasing history |
| Evidence_IDs | Atomic supporting/challenging evidence |
| Claim_IDs | Current affected claims |
| Event_IDs | Research events that established the row |
| Residual | Remaining mismatch or unknown |
