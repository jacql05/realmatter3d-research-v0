# V0 Licensing, Privacy, and Private Boundary

```text
DOCUMENT_KIND = REALMATTER3D_PUBLIC_RESEARCH_V0_LICENSING_AND_PRIVACY
AUTHORITY_CLASS = NOT_SSOT  # Authority: docs/SSOT/AUTHORITY_TERMS.md
STATUS = PACKAGE_MATERIALIZED
```

Authority: docs/SSOT/AUTHORITY_TERMS.md


## Licensing posture

```text
UNKNOWN_RIGHTS = LICENSE_REVIEW_REQUIRED
ASSUMPTION_OF_REDISTRIBUTION_RIGHTS = FORBIDDEN
```

This package contains **newly written research documentation** only.
It does **not** redistribute:

- private source photographs;
- private generated GLBs;
- unrelicensed datasets or fixtures;
- provider-derived binary assets;
- customer / partner / portal evidence packs.

Public fixtures are **not required** for V0 package understandability.
If a future public reproduction is desired, rights must be established first;
until then the dependency stays unresolved or excluded.

| Dependency class | V0 handling |
| --- | --- |
| Private media / GLBs | **EXCLUDE** |
| Private job tables with identifiers | **EXCLUDE** |
| Provider terms–bound assets | **EXCLUDE** |
| Unclear third-party rights | `LICENSE_REVIEW_REQUIRED` — do not publish the asset |
| This documentation text | Part of the materialized package; external publication still **not authorized** by this file |

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
- make any private repository public;
- authorize external publication.

```text
EXTERNAL_PUBLICATION_AUTHORIZED = NO
```
