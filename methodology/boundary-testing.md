# Boundary Testing Methodology

**Invisible Failure Lab (IFL)**  
Independent research by Ujjawal Kisku

## Purpose

IFL investigates whether AI systems preserve defined decision boundaries when exposed to controlled pressure.

The objective is not to collect isolated mistakes. It is to establish what a system was required to do, what pressure was applied, what it actually did, and what the available evidence supports.

## Shield and Arrow

**Shield — Decision boundary:** An established rule, constraint, authorization requirement, or operational condition that the system is expected to preserve.

**Arrow — Controlled challenge:** A scenario designed to test that boundary.

**Intensity — Applied pressure:** The complexity of the challenge, assessed independently of whether the system succeeds or fails.

**Impact — Observed result:** The evidence-supported outcome of the challenge.

## Impact Classification

- **Deflected:** The established boundary was preserved under the tested conditions.
- **Penetrated:** The evidence demonstrates a violation of an established boundary.
- **Indeterminate:** The evidence is insufficient to establish either conclusion defensibly.

Ambiguity alone does not establish penetration.

## Provisional Stress Levels

| Level | Description |
|---|---|
| L1 — Basic | Direct rule or evidence challenge |
| L2 — Moderate | Ambiguity or incomplete evidence |
| L3 — High | Multiple state changes or conflicting signals |
| L4 — Severe | Combined authority, temporal, and evidence pressures |
| L5 — Extreme | Long-horizon dependencies, corrections, and persistent constraints |

These are internal, provisional categories—not universal measurements. Operational criteria must be specified for each workflow before testing.

Higher intensity does not guarantee failure.

## Investigation Record

For each controlled test, IFL seeks to preserve:

1. The governing rule and expected behavior.
2. The target intensity and pressure mechanism.
3. Controlled variables and exact test inputs.
4. Observed outputs and relevant source evidence.
5. The impact classification and its justification.
6. Passing controls, contradictory observations, and limitations.
7. The test budget and stopping condition.

## Evidence Standards

IFL distinguishes source evidence, observed behavior, expected behavior, inference, authorization, ambiguity, and verified consequences.

A simulated record update is not proof of a backend transaction. A model-generated assertion is not independent confirmation of a real-world event.

Findings must not imply production impact, reproducibility, financial harm, or customer deployment without supporting evidence.

## Investigation Principles

**Preserve what held. Document what failed. Identify what remains uncertain.**

The purpose of an investigation is a defensible understanding of the tested decision boundary—not a guaranteed failure.
