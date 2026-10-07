# V0 Licensing, Privacy, and Private Boundary

```text
DOCUMENT_KIND = REALMATTER3D_PUBLIC_RESEARCH_V0_LICENSING_AND_PRIVACY
AUTHORITY_CLASS = NOT_SSOT  # Authority: docs/SSOT/AUTHORITY_TERMS.md
STATUS = PACKAGE_MATERIALIZED
```

Authority: docs/SSOT/AUTHORITY_TERMS.md


## Licensing posture

```text
PUBLIC_DOCUMENTATION_LICENSE = CC-BY-4.0
LICENSE_SCOPE = the seven public documentation files in this carrier only
LICENSE_URI = https://creativecommons.org/licenses/by/4.0/
```

The seven documentation files in this carrier are licensed under
[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/):

- README.md
- THESIS_AND_COMPARISON.md
- NEGATIVE_FINDINGS.md
- MEASUREMENT_DISCIPLINE.md
- OPEN_QUESTIONS.md
- NON_CLAIMS.md
- LICENSING_AND_PRIVACY.md

Material outside those seven files keeps the unresolved-rights posture:

```text
UNKNOWN_RIGHTS = LICENSE_REVIEW_REQUIRED
ASSUMPTION_OF_REDISTRIBUTION_RIGHTS = FORBIDDEN
```

That posture applies to excluded third-party assets, media, GLBs, datasets,
evidence, job records, and any other material that is not one of the seven
documentation files. Those materials are not licensed CC-BY-4.0.

This package contains **newly written research documentation** only.
It does **not** redistribute:

- private source photographs;
- private generated GLBs;
- unrelicensed datasets or fixtures;
- provider-derived binary assets;
- customer / partner / portal evidence packs.

Public fixtures are **not required** for V0 package understandability.
If a future public reproduction of excluded material is desired, rights must
be established first; until then the dependency stays unresolved or excluded.

| Dependency class | V0 handling |
| --- | --- |
| Private media / GLBs | **EXCLUDE** — `UNKNOWN_RIGHTS = LICENSE_REVIEW_REQUIRED`; not CC-BY-4.0 |
| Private job tables with identifiers | **EXCLUDE** — `UNKNOWN_RIGHTS = LICENSE_REVIEW_REQUIRED`; not CC-BY-4.0 |
| Provider terms–bound assets | **EXCLUDE** — `UNKNOWN_RIGHTS = LICENSE_REVIEW_REQUIRED`; not CC-BY-4.0 |
| Unclear third-party rights | `LICENSE_REVIEW_REQUIRED` — do not publish the asset; not CC-BY-4.0 |
| These seven documentation files | `PUBLIC_DOCUMENTATION_LICENSE = CC-BY-4.0` |

## Privacy posture

Excluded from the public package:

- production runtime and infrastructure details;
- credentials and secrets;
- provider integration internals;
- customer, partner, Founder, or portal review artifacts;
- internal job identifiers and commercial case names;
- private operational learning corpora.

Where a finding was learned from private corpora, the finding is stated in
generalized form and marked:

```text
CORPUS_BOUND = PRIVATE_CORPUS_DERIVED
```

## Private / public separation

```text
Public research package = projection
Private production repository = remains private authority
Public package ≠ authority over private production systems
```

This materialization does **not**:

- create a new repository;
- make any private repository public.

Current publication status of this carrier:

```text
EXTERNAL_PUBLICATION_AUTHORIZED = YES
```
