# V0 Thesis and Comparison-Pair Law

```text
DOCUMENT_KIND = REALMATTER3D_PUBLIC_RESEARCH_V0_THESIS
AUTHORITY_CLASS = NOT_SSOT  # Authority: docs/SSOT/AUTHORITY_TERMS.md
STATUS = PACKAGE_MATERIALIZED
```

Authority: docs/SSOT/AUTHORITY_TERMS.md


## Thesis

For single-image **reference ↔ generated-3D** fidelity work:

- convenient automated signals are **not** automatically interchangeable with
  reference-grounded human-visible fidelity;
- meaningful comparison requires structure, not slogan metrics;
- quantitative fidelity scores and proven reference-grounded repair are
  **not** established.

V0 publishes this as a research posture of **negative results**,
**measurement discipline**, and **open questions**.

## Named comparison pair

Every fidelity-relevant statement must name the comparison pair it uses.

| Role | Meaning |
| --- | --- |
| **Reference** | The intended visual reference (commonly a source photograph of a specific object) |
| **Generated** | The committed generated 3D result under review |
| **Primary Pair (default research framing)** | Reference ↔ Generated, unless another pair is explicitly named |
| **Instrument pair** | The pair an automated meter actually measures (may differ from the human judgment pair) |

Hard rule:

```text
If the instrument pair ≠ the human judgment pair,
do not treat the instrument as a measurement of that human judgment
without an explicit bridging argument.
```

## Declared conditions

A comparison is research-eligible only when the following can be declared:

1. **Comparison pair** (named)
2. **Observation conditions** (viewer / lighting / camera / tone-mapping assumptions as applicable)
3. **Confounders** known to threaten the comparison
4. **Claim ceiling** (what the result may and may not mean)

If confounders cannot be declared, the slice is **not eligible**.

## Human judgment vs machine instruments

| Lane | Output class | May claim |
| --- | --- | --- |
| Human judgment | Categorical / structured visual judgment on a named pair | Human-visible fidelity judgment under declared conditions |
| Machine instrument | Numeric or class label on its declared instrument pair | Direct measurement of that instrument meaning only |

```text
AI_OR_MACHINE_STATUS ≠ HUMAN_JUDGMENT
INSTRUMENT_VALUE ≠ DIMENSION_FIDELITY_SCORE
```

## Claim chain (non-reversible)

```text
Evidence
  → Maturity
  → Claim Ceiling
  → Public Statement
```

Never reverse this order. Never inflate maturity to fit a desired statement.

## What V0 deliberately is not

- a universal or per-dimension fidelity score
- a production pass/fail gate
- a provider competition study
- a repair-proven method suite
- a complete fidelity science stack
