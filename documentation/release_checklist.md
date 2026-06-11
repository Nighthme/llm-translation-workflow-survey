# Release Checklist

Use this checklist before creating the GitHub release that will be archived by Zenodo.

## Before GitHub Upload

- Confirm that GitHub repository links use `https://github.com/Nighthme/llm-translation-workflow-survey`.
- Confirm that no copyrighted full-text PDFs are included.
- Confirm that `data/screening_and_extraction.csv` contains only bibliographic metadata, screening decisions, coding notes, and source links.
- Confirm that the author affiliation, email, and ORCID are correct.
- Confirm that the license is suitable for public release.
- Confirm that the formerly metadata-pending records documented in `documentation/citation_format_audit.md` remain supported by the official publisher/Crossref metadata checked on 2026-06-11.
- Confirm whether to keep `manuscript/manuscript_nlp_cambridge_expanded_revised.pdf` in the public release. It is included here as a working manuscript PDF for review convenience.
- Confirm that `documentation/citation_format_audit.md`, `documentation/submission_readiness_review.md`, and `documentation/target_journal_format_checklist.md` are acceptable for public release.

## Recommended GitHub Steps

1. Create a repository named `llm-translation-workflow-survey`.
2. Upload the contents of `repository_release_package/` to the repository root.
3. Commit with a message such as `Initial dataset and documentation release`.
4. Create a release tagged `v1.0.0`.

## Recommended Zenodo Steps

1. Connect the GitHub repository to Zenodo.
2. Trigger archival by publishing the GitHub release.
3. Copy the Zenodo DOI.
4. Confirm that the manuscript data-availability statement uses the final DOI `https://doi.org/10.5281/zenodo.20645622`.

## Manuscript Data-Availability Template

```latex
\section*{Data availability statement}
The screening records, search strategy, evidence map, codebook, metadata-cleanup notes, and PRISMA-style count documentation supporting this survey are available in Zenodo at \url{https://doi.org/10.5281/zenodo.20645622}. The corresponding GitHub repository is available at \url{https://github.com/Nighthme/llm-translation-workflow-survey}.
```
