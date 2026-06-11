# Codebook

This codebook describes the main fields used in the release package.

## Main Extraction Table

File: `data/screening_and_extraction.csv`

| Field | Description |
|---|---|
| `record_id` | Stable internal identifier for the record. |
| `title` | Publication title. |
| `authors` | Author names as recorded during metadata cleanup. |
| `year` | Publication or availability year. |
| `venue` | Journal, conference, workshop, repository, or source venue. |
| `source_database` | Database or discovery source used to identify the record. |
| `doi` | Digital Object Identifier, where available. |
| `url` | Source URL or landing page. |
| `peer_review_status` | Peer-review or publication-status classification. |
| `document_type` | Article, conference paper, survey, preprint, dataset paper, or related document type. |
| `screening_title_abstract` | Title/abstract screening decision. |
| `screening_full_text` | Full-text or metadata-level screening decision. |
| `exclusion_reason` | Reason for exclusion, if applicable. |
| `model_category` | Broad model category, such as NMT, LLM, LLM evaluator, MTPE, or hybrid workflow. |
| `llm_name_or_family` | Named LLM, model family, or proprietary/open model family. |
| `nmt_or_mt_system` | NMT or MT system used, compared, or discussed. |
| `workflow_stage` | Translation workflow stage addressed by the record. |
| `translation_task` | Specific translation-related task or workflow function. |
| `language_pairs` | Language pair(s), language direction(s), or language scope. |
| `domain` | Domain or genre, such as general MT, legal, medical, literary, enterprise, or education. |
| `dataset_or_corpus` | Dataset, benchmark, corpus, or data source used in the study. |
| `evaluation_metrics` | Automatic metrics, human evaluation methods, process measures, or qualitative methods. |
| `human_evaluation` | Whether and how human evaluation was used. |
| `professional_translators_involved` | Whether professional translators were involved. |
| `participant_count` | Number of participants, annotators, or evaluators, where reported. |
| `prompt_reported` | Whether LLM prompts or prompt templates were reported. |
| `code_available` | Whether code was reported as available. |
| `data_available` | Whether data, annotations, or benchmark resources were reported as available. |
| `main_findings` | Brief summary of the record's main finding(s). |
| `limitations` | Reported or inferred limitations relevant to the survey. |
| `reproducibility_notes` | Notes on reproducibility, model versioning, prompts, data, or code. |
| `ethics_or_privacy_notes` | Ethics, confidentiality, privacy, bias, safety, or risk notes. |
| `taxonomy_tags` | Tags used for thematic synthesis and evidence clustering. |
| `notes` | Additional project notes. |

## Expanded Search Candidate Table

File: `data/expanded_search_candidates.csv`

| Field | Description |
|---|---|
| `candidate_id` | Stable internal candidate identifier. |
| `title` | Candidate publication title. |
| `authors` | Candidate author names. |
| `year` | Publication or availability year. |
| `venue_or_source` | Venue or discovery source. |
| `source_type` | Journal article, conference paper, preprint, or other source type. |
| `search_line` | Search line or thematic expansion route that identified the candidate. |
| `workflow_stage` | Translation workflow area addressed. |
| `why_candidate` | Reason the candidate was considered relevant. |
| `url` | Source URL or DOI link. |
| `screening_status` | Screening status. |
| `screening_decision` | Include, exclude, background, or related decision. |
| `notes` | Additional screening notes. |

## Additional Sources Candidate Table

File: `data/additional_sources_candidates.csv`

| Field | Description |
|---|---|
| `candidate_id` | Stable internal candidate identifier. |
| `title` | Candidate publication title. |
| `authors` | Candidate author names. |
| `year` | Publication or availability year. |
| `venue_or_source` | Venue or discovery source. |
| `source_type` | Journal article, conference paper, preprint, or other source type. |
| `source_family` | Publisher, database, proceedings family, or discovery family. |
| `workflow_stage` | Translation workflow area addressed. |
| `screening_decision` | Include, exclude, background, or related decision. |
| `why_candidate` | Reason the candidate was considered relevant. |
| `url` | Source URL or DOI link. |

## Coding Notes

The release is designed for transparency and reproducibility of a scoping survey. The coding categories are interpretive and workflow-oriented; they should not be treated as mutually exclusive effect-size categories.
