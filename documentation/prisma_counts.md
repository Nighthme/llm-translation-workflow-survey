# PRISMA-Style Counts

This file documents the final working counts used in the manuscript draft.

## Counts

| Stage | Count | Notes |
|---|---:|---|
| Records identified through database, venue, and citation searches | 63 | Includes database searches, venue searches, citation chasing, and targeted gap-filling searches. |
| Records after deduplication and metadata cleanup | 56 | Deduplication used title, DOI, venue, URL, author, and preprint/proceedings relationship checks. |
| Records screened for scope and publication status | 56 | Records were screened for relevance to MT/NMT/LLM translation workflows. |
| Records not included in full extraction | 7 | Two records were retained for background or target-journal calibration; five records were excluded or kept outside extraction because of scope or metadata instability. |
| Final full-review extraction corpus | 48 | Records included in the formal extraction and synthesis corpus. |
| Record retained outside final extraction pending metadata | 1 | Metadata or publication status required additional caution at the time of drafting. |

## Interpretation

The counts are PRISMA-style counts for a scoping survey rather than effect-size units for meta-analysis. The side branch in the manuscript figure combines records outside full extraction, but the narrative separates background/calibration records from excluded or metadata-caution records. Conceptually overlapping records were retained when they addressed different workflow roles, datasets, evaluation protocols, language pairs, or human-interaction settings.

## Related Files

- `data/screening_and_extraction.csv`
- `documentation/search_strategy.md`
- `documentation/metadata_cleanup_quality.md`
- `documentation/pilot_screening_summary.md`
- `documentation/expanded_candidate_screening_summary.md`
