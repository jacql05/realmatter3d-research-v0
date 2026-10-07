# V0 Negative Findings

```text
DOCUMENT_KIND = REALMATTER3D_PUBLIC_RESEARCH_V0_NEGATIVE_FINDINGS
AUTHORITY_CLASS = NOT_SSOT  # Authority: docs/SSOT/AUTHORITY_TERMS.md
STATUS = PACKAGE_MATERIALIZED
CORPUS_BOUND = PRIVATE_CORPUS_DERIVED_WHERE_NOTED
```

Authority: docs/SSOT/AUTHORITY_TERMS.md


Negative findings retain their experimental bounds. They are **not** universal
laws. Where underlying evidence used private corpora, that bound is stated
explicitly. No private job identifiers, product names, images, or GLBs are
reproduced here.

---

## NF-01 — Quantitative fidelity scoring relationship not established

| Field | Value |
| --- | --- |
| Finding | No defensible quantitative measurement relationship was established that would justify a fidelity score for generated-3D results vs reference-grounded human-visible fidelity |
| Maturity | Established as a research-program outcome |
| Claim ceiling | Negative program outcome only — does **not** prove that no future relationship can ever exist |
| Corpus bound | Derived from a closed private research program that reused existing offline evidence; **not** a public reproducible scorecard |
| Public statement | Quantitative fidelity scoring is **not established** |

```text
RESEARCH_STOPPED ≠ QUANTITATIVE_FIDELITY_ESTABLISHED
```

---

## NF-02 — Color instrument vs human-visible color (disproven as fidelity relationship)

| Field | Value |
| --- | --- |
| Finding | A common color-distribution instrument measured on a **submitted-foreground ↔ albedo** pair is **not** a valid measurement relationship to human-visible color judgment on a **reference-photo ↔ generated-3D viewer** pair |
| Classification | `INVALID / DISPROVEN SIGNAL` for that human-visible color use |
| Why (bounds) | Instrument pair and human judgment pair were not the same; confounders (pair mismatch, dark-subject / histogram effects, threshold near-miss class labels) explained apparent association without a remaining eligible offline relationship |
| Maturity | Slice-level kill on private offline evidence |
| Claim ceiling | Does **not** invalidate recording the instrument as a distribution error on its own pair; does **not** create a Color Fidelity score |
| Corpus bound | **Private-corpus-derived**; exploratory paired sample; non-authoritative as a public statistical result |
| Public statement | That instrument is a **direct measurement of its declared pair**, and an **invalid / disproven signal** for human-visible color fidelity on the Primary Pair under the tested conditions |

```text
INSTRUMENT_VS_OWN_PAIR = DIRECT MEASUREMENT (pre-established meaning)
INSTRUMENT_VS_HUMAN_VISIBLE_COLOR = INVALID / DISPROVEN SIGNAL
hist_or_distribution_distance ≠ Color Fidelity
```

---

## NF-03 — Convenient automated labels ≠ human-visible material/color failure

| Field | Value |
| --- | --- |
| Finding | Human-visible material/color failures can coexist with automated labels that report no washout / no blur / quality-class PASS |
| Mechanism classes | Naming drift (label name ≠ measured quantity); semantic scope mismatch; threshold near-miss; produced-but-not-harvested fields; readiness/completeness flags mistaken for quality |
| Maturity | Supported by structured signal-gap audit on private cohort evidence |
| Claim ceiling | Documents a **gap class**, not a fix; does not authorize threshold changes or new classifiers by itself |
| Corpus bound | **Private-corpus-derived** case-study audit; n-exploratory |
| Public statement | Automated convenience labels are **not interchangeable** with reference-grounded human-visible fidelity without an explicit semantic bridge |

---

## NF-04 — Luma / ΔL crush-priority use invalid

| Field | Value |
| --- | --- |
| Finding | Frequent large negative mean Lab ΔL must **not** be treated as evidence of generated darkening/crush priority |
| Maturity | Active negative semantic learning record |
| Claim ceiling | Invalidates that **priority / phenotype use**; does not forbid measuring or displaying the raw metric |
| Corpus bound | **Private-corpus-derived** offline paired human pass/fail study |
| Public statement | Raw metric ≠ crush-priority phenotype without a validated mapping |

---

## NF-05 — Shadow severity ≠ sole blur detector

| Field | Value |
| --- | --- |
| Finding | Shadow / crush severity signals are not a valid sole detector for output blur; the planes are separable |
| Maturity | Established on a closed input-risk research track |
| Claim ceiling | Proxy falsification / separability — not a claim that blur detection is solved |
| Corpus bound | Research-track conclusion; public statement is the principle, not a private case dump |
| Public statement | Do not use shadow severity alone as blur |

---

## Inequalities preserved by V0

```text
metric improvement ≠ reference-grounded improvement
measurement relationship ≠ dimension Fidelity score
dimension measurement ≠ Product PASS
observed correlation ≠ Validated Cause
distribution distance ≠ Color Fidelity
edge-energy proxy ≠ Geometry Fidelity
sharpness proxy ≠ Geometry Fidelity
texture metric ≠ Surface Fidelity
readiness / dual-chain completeness ≠ visual quality
label name ≠ measured semantics
```

## Explicitly not published here

- Private job IDs, product names, or portal review rows
- Numeric tables that would require unrelicensed private media to interpret
- Provider-named competitive rankings
- Any invented benchmark scores
