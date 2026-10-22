# Invisible Failure Lab

**AI decision-integrity research conducted by Ujjawal Kisku.**

Invisible Failure Lab investigates how AI systems turn source information into operational records and decisions: whether an expected delivery becomes received stock, a calculated date becomes a commitment, or a physical movement becomes an obligation settlement.

These distinctions matter when people use AI-generated records to allocate inventory, schedule follow-up, or decide what remains owed. The research examines the decision boundary and the evidence supporting each field; these cases do not establish actual production losses.

## Featured investigation: inventory receipt integrity

In a saved inventory conversation, the model posted a return while also describing physical receipt as pending. An explicit-rule comparison kept stock unchanged until receipt confirmation. The contradiction is observed; a strict rule penetration remains Indeterminate in the initial scenario because the receipt gate was not explicit.

Read [Inventory receipt integrity](investigations/inventory-receipt-integrity.md).

## Persistent Constraint Reasoning

The **PCR research program** examines whether constraints survive changing evidence, corrections, and structured handoffs. Start with the [research library](PCR/README.md) or [findings index](PCR/findings-index.md).

| Investigation | Question examined |
|---|---|
| [Temporal authority](PCR/temporal-authority.md) | Which commitment governs after a correction or conflicting update? |
| [Obligation settlement](PCR/obligation-settlement.md) | Does moving stock authorize reducing a recorded obligation? |
| [Repayment provenance](PCR/repayment-provenance.md) | Does a register preserve the source's wording and uncertainty? |
| [Structured handoff](PCR/structured-handoff.md) | Do exported fields preserve the difference between calculation and confirmation? |

## How IFL conducts controlled stress tests

IFL identifies the workflow's governing rule, states the judgment scope, introduces controlled pressure, and preserves the exact prompts and responses. Review separates source facts, calculations, administrative choices, and authorization; it compares questionable outputs with passing controls and records **Deflected**, **Penetrated**, or **Indeterminate** outcomes only within the supported scope.

See the [boundary-testing methodology](methodology/boundary-testing.md) and [evidence standards](evidence-standards.md). The practical aim is a bounded, authorized workflow review with evidence-backed findings and useful limitations—not guaranteed defect discovery.

The published candidates describe exploratory saved-conversation evidence, not universal model defects or independently reproduced production incidents. Public excerpts are limited; full source locators remain in a separate private audit.

## Research status and contact

IFL is independent exploratory research led by Ujjawal Kisku. This repository is being prepared for public release; a verified contact route will be added before external outreach. No customer engagement, certified evaluation, or production incident is claimed by the research cases.
