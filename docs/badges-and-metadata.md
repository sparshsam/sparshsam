# Standard Badges and Metadata

## README Badge Set

Use restrained badges. Badges should communicate maintenance, license, release, citation, and architecture status. Avoid decorative badges and vanity counters.

Recommended order:

```md
[![License](https://img.shields.io/github/license/sparshsam/REPO?style=flat-square)](LICENSE)
[![Release](https://img.shields.io/github/v/release/sparshsam/REPO?style=flat-square)](https://github.com/sparshsam/REPO/releases)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.RECORD.svg)](https://doi.org/10.5281/zenodo.RECORD)
[![Status: Maintained](https://img.shields.io/badge/status-maintained-2f6f5e?style=flat-square)](#maintenance)
[![Local-first](https://img.shields.io/badge/local--first-yes-44546a?style=flat-square)](#architecture)
[![Privacy-first](https://img.shields.io/badge/privacy--first-default-44546a?style=flat-square)](#privacy)
```

Use the DOI badge only after the first Zenodo record exists.

## Repository Metadata Block

Every README should include a compact identity block:

```md
## Project Metadata

- Category: proof infrastructure
- Class: applied-system
- Maturity: M2 maintained
- Data posture: local-first / private by default / public proof only
- Research themes: calm software, verification, ownership without surveillance
- Citation: pending DOI
- ORCID: https://orcid.org/0009-0007-1585-6927
```

## Required Root Files

Each serious repository should eventually contain:

- `README.md`
- `LICENSE`
- `CHANGELOG.md`
- `CONTRIBUTING.md`
- `CODE_OF_CONDUCT.md`
- `SECURITY.md`
- `CITATION.cff`
- `.zenodo.json`
- `docs/architecture.md`
- `docs/research-note.md`
- `docs/privacy-model.md`
- `docs/maintenance.md`
