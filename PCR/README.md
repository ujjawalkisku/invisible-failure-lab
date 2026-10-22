# Persistent Constraint Reasoning (PCR)

**A research program of Invisible Failure Lab**  
**Investigator:** Ujjawal Kisku  
**Status:** Active research; historical findings undergoing publication review

## Research Objective

Persistent Constraint Reasoning (PCR) investigates whether AI systems preserve governing constraints as information, operational states, and instructions evolve.

The central question is:

**When an AI system encounters new information, does it preserve the rules governing what it is authorized to conclude, record, or change?**

PCR examines the relationship between evidence, interpretation, operational state, and decision authority.

## Research Areas

| Investigation area | Decision boundary under examination |
|---|---|
| Temporal authority | Whether ambiguous timing statements become unsupported commitments |
| Inventory receipt integrity | Whether an intended return becomes a recorded completed receipt |
| Obligation settlement | Whether physical movements are treated as authority to settle separate obligations |
| Repayment evidence provenance | Whether inferred dates are promoted into confirmed due-date fields |
| Structured handoff integrity | Whether evidence qualifications survive conversion into restricted output formats |

These areas represent historical research directions, not claims of demonstrated defects in every investigation.

## Featured Investigation

### [Inventory Receipt Integrity](../investigations/inventory-receipt-integrity.md)

A saved AI response recorded an inventory return as completed while describing physical receipt as pending.

An explicit-rule comparison preserved the receipt-confirmation boundary.

**Evidence-supported interpretation:** An operational-state inconsistency was observed in the initial response. Strict rule penetration remained indeterminate. The explicit-rule comparison deflected the tested challenge.

## Research Method

PCR investigations use IFL's [Boundary Testing Methodology](../methodology/boundary-testing.md).

Each investigation seeks to establish:

1. The governing decision boundary.
2. The controlled pressure mechanism.
3. The expected and observed behavior.
4. Whether the boundary held, was violated, or remains unresolved.
5. The limitations of the available evidence.

Passing controls and contradictory observations are retained.

## Evidence and Limitations

Historical PCR investigations include exploratory conversational tests and subsequent evidence reviews.

Saved conversational outputs are not equivalent to verified backend execution or production incidents.

Where model identity, session independence, reproducibility, or downstream consequences cannot be verified, the published findings must explicitly acknowledge those limitations.

## Publication Status

The inventory receipt investigation is available in this repository.

Additional historical investigations will be added following source verification and disclosure review. Their inclusion will not imply that every tested scenario produced a failure.

---

*Persistent Constraint Reasoning is an IFL research program, not a standardized industry benchmark or certified evaluation framework.*
