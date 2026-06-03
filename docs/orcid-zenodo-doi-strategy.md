# ORCID, Zenodo, and DOI Strategy

This workflow connects software releases, papers, specifications, and public research notes into a durable citation record.

## Sources Checked

- Zenodo GitHub integration: https://help.zenodo.org/docs/github/
- GitHub citation guidance: https://docs.github.com/articles/referencing-and-citing-content
- Zenodo developer metadata note for `.zenodo.json`: https://developers.zenodo.org/
- ORCID record guidance: https://info.orcid.org/documentation/integration-guide/orcid-record/

## ORCID Strategy

ORCID should be the canonical researcher identity. GitHub should be the development surface. Zenodo should be the archival and citation surface.

Actions:

1. Use the canonical public ORCID URL in the GitHub profile README: https://orcid.org/0009-0007-1585-6927.
2. Add the same ORCID to `CITATION.cff` in every mature repository.
3. Add Zenodo software records, papers, architecture notes, and protocol specifications to ORCID Works.
4. Use consistent creator name formatting: `Sparsh Sam`.
5. Keep employment, affiliation, and funding fields sparse unless there is a durable institution to list.

## Zenodo Workflow

For each mature repository:

1. Add `CITATION.cff`.
2. Add `.zenodo.json`.
3. Enable GitHub integration in Zenodo for the repository.
4. Create a GitHub release with semantic versioning.
5. Let Zenodo archive the release and issue a DOI.
6. Add the DOI badge to the README.
7. Add the DOI to `CITATION.cff` after the first DOI exists.
8. Add the work to ORCID.

Zenodo creates DOI-versioned records for releases. Use the concept DOI for general citation of the project and version DOI for exact reproducibility.

## Release Naming

Use factual release titles:

- `OpenProof v0.2.0: Local Hash Verification and Timestamp Records`
- `QuietLedger v0.3.0: Local Budget Export and Restore`
- `PDFReader v1.1.0: Workspace Restore and Annotation Persistence`

Avoid persuasive release names.

## DOI Readiness Review Priorities

First wave:

- `openproof`
- `quietledger`
- `pdfreader-by-sparsh`

Second wave:

- `elora-vault`
- `opensprout`

Third wave:

- `wordwise`
- `shesafe`

## Metadata Rule

Only publish a DOI when the release has:

- a stable README;
- a license;
- citation metadata;
- a changelog entry;
- enough documentation for a reader to understand the architecture and limits.
