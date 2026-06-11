# Execution Log

## 2026-06-09

### Decisions

- Target journal selected: Natural Language Processing, Cambridge University Press.
- Article type: Survey Paper.
- Review design: scoping survey with PRISMA-ScR-informed search and screening.
- Main topic: NMT and LLMs in translation workflows, not direct MT quality comparison only.
- Time span: 2017-2026.

### Files Created

- `research_protocol.md`: working protocol, research questions, scope, inclusion/exclusion criteria, taxonomy, planned analysis.
- `search_strategy.md`: database-specific search strings and search log template.
- `screening_and_extraction.csv`: coding sheet for screening and data extraction.
- `seed_literature.csv`: first seed literature set.
- `manuscript_outline.md`: working outline for the target journal.

### Immediate Next Actions

1. Run pilot searches in ACL Anthology, Scopus, and Web of Science.
2. Export results to RIS/BibTeX/CSV where possible.
3. Deduplicate records.
4. Screen the first 30-50 candidate papers.
5. Revise taxonomy based on pilot screening.

### Pilot Search Notes

- First ACL Anthology pilot search identified four strong clusters: automatic post-editing, translation quality assessment, terminology control, and document-level/context-aware translation.
- The seed set was expanded from 8 to 16 records.
- Author metadata for the initially incomplete seed records was verified against ACL Anthology pages.

### Pilot Screening

- Pilot screening completed for 16 seed records.
- Outcome: 16 included for full review, 0 excluded.
- Extraction table populated with provisional coding fields.
- `pilot_screening_summary.md` created with cluster analysis and taxonomy revision.

### Search Expansion

- `search_strategy.md` expanded with Scopus and Web of Science main and workflow-specific search strings.
- A dedicated human workflow search line was added for translator interaction, cognitive load, trust, productivity, and human-AI collaboration.
- `expanded_search_candidates.csv` created with 8 candidate records for the next screening pass.
- `search_expansion_log.md` created.

### Expanded Candidate Screening

- Screened 8 expanded human-workflow candidates.
- Included for full review: 7.
- Provisionally included for full review: 0.
- Background only, excluded from formal evidence extraction: 1.
- `screening_and_extraction.csv` expanded from 16 to 23 formal/provisional records.
- `expanded_candidate_screening_summary.md` created.

### Evidence Mapping

- C008 metadata verified and moved from provisional to full inclusion.
- Research protocol taxonomy updated from preliminary taxonomy to revised post-pilot taxonomy.
- `evidence_map.md` created with year distribution, document type distribution, peer-review status, evidence clusters, and working thesis.

### Additional Sources Expansion

- Searched beyond ACL Anthology into Frontiers, Wiley, Nature Portfolio, MDPI, SAGE, Springer/ScienceDirect-indexed pages, HiT-IT proceedings, and arXiv.
- Created `additional_sources_candidates.csv` with 15 candidate records.
- Added 13 new records to `screening_and_extraction.csv`, expanding the formal evidence table from 23 to 36 records.
- Created `additional_sources_summary.md`.

### Metadata Cleanup and Quality Grading

- Verified D011-D014 metadata.
- Corrected D011 authors and year.
- Corrected D012 author, DOI, proceedings status, and summary details.
- Corrected D013 full author list, DOI, proceedings status, and summary details.
- Verified D014 as a peer-reviewed HCII 2024 Springer proceedings chapter and added it to the formal extraction table.
- Created `metadata_cleanup_quality.md`.
- Formal extraction table expanded from 36 to 37 records.

### Gap-Fill Literature Supplement

- Identified underrepresented evidence areas: low-resource/Indigenous-language MT, gender/fairness, hallucination and robustness, multimodal/document-image MT, simultaneous MT, enterprise translation-memory fine-tuning, and traditional NMT/Transformer background.
- Created `gap_fill_candidates.md`.
- Added 11 formal full-review records, G001-G011, to `screening_and_extraction.csv`.
- Marked 5 background anchors, B001-B005, for historical/methodological framing rather than workflow extraction.
- Updated `evidence_map.md`; formal extraction table expanded from 37 to 48 records.

### Target-Journal Drafting

- Checked current *Natural Language Processing* author guidance: Survey Papers require an abstract, 3-5 keywords, author-date references, numbered subheadings, and required conflict-of-interest, funding, data-availability, and ethics statements.
- Created `manuscript_draft_nlp_cambridge.md`, a structured first draft aligned to the target journal's Survey Paper format.
- Created `target_journal_format_checklist.md`.
- Current manuscript draft length: approximately 6,258 words. It is a first full-structure draft and needs expansion to the journal's approximate 10,000-16,000-word Survey Paper range before submission.

### LaTeX and PDF Draft

- Expanded the manuscript into a LaTeX draft: `manuscript_nlp_cambridge_expanded.tex`.
- Added four TikZ figures directly in the LaTeX source:
  - PRISMA-style flow diagram;
  - timeline from attention-based NMT to LLM-augmented workflows;
  - workflow map of LLM-augmented translation;
  - research gap matrix.
- Added two expansion sections: cross-cluster synthesis and implications for NLP research.
- Final rough manuscript word-count estimate: approximately 10,027 words.
- Compiled with XeLaTeX to `manuscript_nlp_cambridge_expanded.pdf`.
- Compilation succeeded with non-fatal overfull/underfull box warnings, mainly from wide tables, TikZ figures, and long DOI strings.

### Pre-submission Polishing

- Compressed wide tables and TikZ figures using smaller table fonts, ragged-right table columns, and figure scaling.
- Removed red TODO markers from the LaTeX draft and replaced them with neutral pre-submission placeholders for author details, ORCID, CRediT contributions, and repository link.
- Added an ORCID submission line for the corresponding author.
- Confirmed funding statement, conflict-of-interest statement, data-availability statement, ethics statement, and AI-use disclosure are present.
- Updated PRISMA wording from working corpus to final extraction corpus and retained the final draft counts: identified records `n=63`, screened after deduplication and metadata cleanup `n=56`, background-only/excluded `n=7`, full-review extraction corpus `n=48`, and one metadata-pending record retained outside final extraction.
- Standardized same-author same-year author-date citations: Kocmi and Federmann 2023a/2023b; Moslem et al. 2023a/2023b.
- Recompiled `manuscript_nlp_cambridge_expanded.pdf`; final rough word-count estimate is approximately 10,102 words and the PDF remains 25 pages.

### Author and Funding Metadata

- Added author metadata for Xiongfei Wang.
- Added affiliation: Faculty of English Language and Culture, Guangdong University of Foreign Studies, Guangzhou, China, 510420.
- Added corresponding author email: `pencinus@qq.com`.
- Added ORCID: `https://orcid.org/0009-0005-9560-6420`.
- Updated author contribution statement for single-author submission.
- Updated funding statement: 2024 Postgraduate Research and Innovation Projects at Guangdong University of Foreign Studies, project *Metaphor Interpretation and Translation of Large Language Models*, Grant No. `24GWCXXM-016`.
- Recompiled the LaTeX manuscript to PDF after metadata insertion.

### Figure and Heading Polishing

- Replaced the Figure 1 horizontal timeline with a vertical timeline layout to remove node overlap and strengthen the visual link between each year and its milestone.
- Updated Figure 1--4 box fills to a muted journal-style palette: pale blue, teal, amber, coral, and neutral gray with dark gray borders.
- Reorganised excessive first-level headings into five main numbered sections: Introduction; Background and methods; Evidence synthesis; Discussion and research agenda; Conclusion.
- Converted workflow clusters and methodological details into second-level subsections.
- Recompiled the revised manuscript as `manuscript_nlp_cambridge_expanded_revised.pdf` and visually checked the Figure 1 page export for overlap.

### Repository Release Package

- Created `repository_release_package/` as a GitHub/Zenodo-ready public data release folder.
- Added release metadata files: `README.md`, `CITATION.cff`, `.zenodo.json`, and `LICENSE.md`.
- Added documentation files: `documentation/codebook.md`, `documentation/prisma_counts.md`, and `documentation/release_checklist.md`.
- Copied public data files into `data/`: `screening_and_extraction.csv`, `expanded_search_candidates.csv`, `additional_sources_candidates.csv`, and `seed_literature.csv`.
- Copied search, screening, metadata-cleanup, evidence-map, and protocol files into `documentation/`.
- Copied the LaTeX manuscript source into `manuscript/` for transparency.

### Pre-Submission Revision After Readiness Review

- Revised the abstract to describe the evidence set as the final extraction corpus rather than a working corpus.
- Added an explicit positioning paragraph distinguishing the survey from context-oriented NMT surveys and broader model-centred MT/LLM surveys.
- Strengthened the methods section with the formal protocol consolidation date, database/venue search logic, screening responsibility, uncertainty handling, and archived search-strategy documentation.
- Clarified the PRISMA-style side branch by separating background/calibration records from excluded or metadata-unstable records.
- Updated `repository_release_package/documentation/prisma_counts.md` to match the clarified PRISMA wording.
- Improved reference metadata for several ACL/Cambridge/DOI-verifiable records, including page ranges, proceedings names, and DOI where reliably available.
- Recompiled the manuscript as `manuscript_nlp_cambridge_expanded_revised.pdf`; the PDF is now 26 pages with only minor reference-line underfull/overfull warnings.

### Citation, DOI, and Target-Journal Format Audit

- Checked in-text author-date citations against the reference list and resolved automated false positives caused by multi-author and group-author strings.
- Corrected remaining three-author in-text citations to first-author `et al.` form.
- Checked DOI syntax and verified a representative set of DOI/source records against official DOI, ACL Anthology, MDPI, and Cambridge pages.
- Flagged several 2025/2026 or ahead-of-print records as high-risk because they could not be verified by public DOI/title search during the final spot-check.
- Created `citation_format_audit.md` documenting citation correspondence, DOI/source status, reference-style risks, and target-journal format compliance.
- Added explicit in-text callouts for Figure 1--4 and Table 1--3 to align with Cambridge figure/table placement guidance.
- Recompiled `manuscript_nlp_cambridge_expanded_revised.pdf`; compilation succeeded and the revised source was synced into `repository_release_package/manuscript/`.

### High-Risk Reference Follow-Up and Reference Style Harmonisation

- Re-checked the five high-risk DOI-bearing records against official publisher/index pages.
- Verified Chen 2025 through the official Frontiers article page and Grubisic and Korencic 2025 through the official ACL Anthology page.
- Retained Huang 2025, Mau 2026, and Yao 2026 as metadata-pending records because public DOI/title checks did not resolve them in this environment.
- Updated `screening_and_extraction.csv` so metadata-pending records no longer appear as fully verified.
- Converted the reference list from full given names to surname-initials Cambridge-style author-date entries.
- Recompiled `manuscript_nlp_cambridge_expanded_revised.pdf`; compilation succeeded with only minor underfull reference-line warnings.

### Repository Link Update

- Updated release-package GitHub repository links to use `https://github.com/Nighthme/llm-translation-workflow-survey`.
- Removed the remaining `USERNAME` placeholders from `CITATION.cff`, `documentation/release_checklist.md`, and `documentation/submission_readiness_review.md`.

### Zenodo DOI Insertion

- Added the Zenodo DOI `https://doi.org/10.5281/zenodo.20645622` to the manuscript data-availability statement.
- Updated release-package metadata in `README.md`, `CITATION.cff`, `.zenodo.json`, and `documentation/release_checklist.md`.
- Updated citation and submission-readiness audit files so data availability is no longer marked as provisional.

### Final High-Risk Reference Verification

- Verified Mau et al. 2026 through Elsevier/Crossref metadata for *System* 139, article `104033`, PII `S0346251X26000643`, DOI `10.1016/j.system.2026.104033`.
- Verified Huang et al. 2025 through Wiley/Crossref metadata for *International Journal of Intelligent Systems* 2025(1), article `9971702`, DOI `10.1155/int/9971702`.
- Verified Yao et al. 2026 through Taylor & Francis/Crossref metadata for *International Journal of Human-Computer Interaction*, pages 1--20, DOI `10.1080/10447318.2026.2628994`.
- Removed `metadata_pending` flags for these records from `screening_and_extraction.csv` and updated the citation audit/readiness files accordingly.

### Desk-Reject Risk Reduction Revision

- Retitled the manuscript as a workflow-oriented scoping survey to better align title scope with the extraction corpus.
- Strengthened the introduction by foregrounding the workflow taxonomy, evidence-role mapping, and distinction from model-centred MT/LLM surveys.
- Added methods language on the final protocol date, public audit trail, single-author screening, uncertainty handling, and metadata verification.
- Clarified the PRISMA-style count wording as forty-eight full-review records plus eight background, exclusion, unstable, or metadata-caution records.
- Compressed repeated open-challenges prose and added a dedicated limitations subsection covering scope, single-author screening, fast-moving metadata, and uneven evidence.
