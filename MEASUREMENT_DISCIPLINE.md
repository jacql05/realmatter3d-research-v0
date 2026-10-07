# V0 Measurement Discipline

```text
DOCUMENT_KIND = REALMATTER3D_PUBLIC_RESEARCH_V0_MEASUREMENT_DISCIPLINE
AUTHORITY_CLASS = NOT_SSOT  # Authority: docs/SSOT/AUTHORITY_TERMS.md
STATUS = PACKAGE_MATERIALIZED
```

Authority: docs/SSOT/AUTHORITY_TERMS.md


These principles are research discipline for RealMatter3D Research V0.
They are **not** a scoring formula, product gate, or runtime specification.

---

## P1 — Name the pair first

State the comparison pair before stating a result.

If an instrument measures a different pair than the human judgment, say so.

## P2 — Declare observation and confounders

Eligible work declares:

- observation conditions relevant to the claim;
- known confounders;
- why the design can still answer the question — or why it cannot.

Undeclared confounders → slice not eligible.

## P3 — Separate human judgment from instruments

Keep separate columns / sections for:

- human-visible judgment on the named judgment pair;
- instrument outputs on the named instrument pair.

Do not silently substitute one for the other.

## P4 — Preserve the claim chain

```text
Evidence → Maturity → Claim Ceiling → Public Statement
```

Do not write the public statement first and invent maturity backward.

## P5 — Prefer kill / hold over invented scores

When evidence does not support a relationship:

- classify with an honest vocabulary (`INVALID / DISPROVEN SIGNAL`, `HOLD`, etc.);
- stop rather than inventing thresholds, weights, 0–100 scales, or overall scores.

## P6 — Negative results keep their bounds

A kill on one instrument / pair / condition set does not automatically kill all
uses of the raw measurement on its own declared pair.

State what was tested. Do not over-generalize.

## P7 — Private corpus stays marked

If a finding depends on private evidence that is not redistributed:

```text
CORPUS_BOUND = PRIVATE_CORPUS_DERIVED
```

Do not imply public reproducibility of that corpus.

## P8 — Design-only is not established

Design drafts, shadow capabilities, blocked operational detectors, and
unimplemented meters must not be narrated as established science.

## P9 — Completeness ≠ quality

Presence of evidence blocks, dual-chain readiness, or harvest completeness
does not assert visual fidelity.

## P10 — Open gaps stay open

If quantitative Primary-Pair fidelity under locked observation remains unproven,
leave it as an open question. Do not fill the gap with a placeholder score.
