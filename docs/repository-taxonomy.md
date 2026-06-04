# Repository Taxonomy

## Categories

| Category | Definition | Repositories |
| --- | --- | --- |
| Proof infrastructure | Systems for verification, timestamping, audit, and evidence. | `openproof` |
| Behavioral finance | Tools that shape financial decisions while preserving agency. | `elora-vault`, `quietledger` |
| Local-first productivity | Desktop or browser tools where user data remains locally controlled. | `pdfreader-by-sparsh`, `quietledger` |
| Care and stewardship | Software for maintaining living routines and long-running personal records. | `opensprout` |
| Reflective ritual | Quiet tools for language, attention, journaling, or deliberate practice. | `wordwise` |
| Civic integrity | Public-interest tools for safety, accountability, and trusted records. | `shesafe` |
| Research identity | Profile, standards, publication metadata, and ecosystem documentation. | `sparshsam` |
| Private infrastructure | Proprietary systems not publicly inspectable. Works involving internal operational logic, client workflows, or business-specific infrastructure. | `tworacle` |

## Repository Classes

Each repository should declare one class in its README metadata block:

- `research-prototype`: exploratory but coherent; not yet stability-focused.
- `applied-system`: usable software with documented architecture and maintenance intent.
- `reference-implementation`: implementation of a described protocol, RFC, or paper.
- `tooling`: developer, document, data, or release tooling.
- `archive`: preserved output with limited active development.

## Maturity Levels

- `M0 concept`: public idea, early scaffolding, no stability guarantees.
- `M1 working`: core workflow works, README explains limits.
- `M2 maintained`: releases, issues, contribution standards, citation metadata.
- `M3 citeable`: Zenodo DOI, changelog, architecture note, stable license.
- `M4 reference`: documented protocol or design spec with tests and examples.

## Standard Topics

Use a small shared vocabulary across repositories:

- `calm-software`
- `local-first`
- `privacy-first`
- `open-source`
- `behavioral-infrastructure`
- `self-custody`
- `proof-systems`
- `personal-data`
- `verification`
- `human-centered-computing`

Avoid topics that pull the ecosystem toward hype or compulsion:

- `gamification`
- `crypto`
- `web3`
- `defi`
- `growth-hacking`

Chain-specific topics may remain when technically necessary, but should not be the lead identity.

