# Submission Readiness Review

Manuscript: *From Neural Machine Translation to LLM-Augmented Translation Workflows: A Workflow-Oriented Scoping Survey*  
Target journal: *Natural Language Processing*  
Review date: 2026-06-11

## Overall Judgement

**Decision: close to submission-ready after repository DOI insertion and high-risk reference verification.**

The manuscript has a viable survey-paper architecture, a coherent workflow-level contribution, a documented extraction corpus, required declaration sections, four figures, three tables, and a public repository release package. The data-availability DOI has now been inserted, and the previously metadata-pending DOI-bearing records have been verified.

## Strengths

- The topic is timely and well matched to *Natural Language Processing*: LLMs, NMT, evaluation, workflow design, human-centred NLP, reproducibility, and responsible NLP.
- The article type is appropriate. The journal accepts Survey Papers.
- The paper has a clear central contribution: reframing LLM translation from direct model comparison to workflow-level translation infrastructure.
- The manuscript has a complete macro-structure: abstract, keywords, introduction, background/methods, evidence synthesis, discussion/research agenda, conclusion, acknowledgements, author contribution, competing interests, funding, data availability, ethics, and references.
- The heading structure is now cleaner: five first-level sections and sixteen second-level sections.
- The manuscript includes four figures and three tables, including PRISMA-style flow, timeline, workflow map, and research gap matrix.
- The extraction corpus is documented locally, with screening and data-release files prepared.

## Major Issues Before Submission

### 1. Reference metadata should receive a final copy-edit

The data availability statement now points to Zenodo DOI `https://doi.org/10.5281/zenodo.20645622` and the GitHub repository `https://github.com/Nighthme/llm-translation-workflow-survey`. Huang et al. (2025), Mau et al. (2026), and Yao et al. (2026) have been verified through official publisher/Crossref metadata.

Recommended action: run a final copy-edit for punctuation, capitalization, and proceedings metadata after any later manuscript edits.

### 2. Reference metadata is incomplete

Several references lack full metadata: page ranges, volume/issue, complete proceedings titles, or DOI where likely available. Some references use abbreviated proceedings descriptions. This is risky for Cambridge author-date style.

Examples needing metadata verification include Castilho and Knowles 2024, Karpinska and Iyyer 2023, Lu et al. 2024, Lu et al. 2025, Macken 2024, Moslem et al. 2023b, Vidal et al. 2022, and Zou et al. 2024.

Recommended action: do one reference metadata pass against DOI/ACL/Crossref records and standardise all entries.

### 3. Search methodology needs more formal reproducibility detail

The methods describe sources and search terms, but the manuscript would be stronger if it reported database-specific strings, search dates, and screening workflow more explicitly in the main text or a supplementary file.

Recommended action: add a short paragraph stating exact final search date, who screened, how disagreements/uncertain records were handled, and where full search strings are archived.

### 4. PRISMA-style counts need clearer naming

The current counts are internally coherent, but the wording should continue to distinguish "background-only," "excluded," and "full-review" records. For a scoping review, this is acceptable, but the flow should explicitly distinguish background records from excluded records.

Recommended action: revise the PRISMA figure caption and `prisma_counts.md` to clarify whether the 7 records are excluded, background-only, or both.

### 5. The corpus is relatively small for a broad 2017-2026 survey

Forty-eight full-review records can support a scoping survey, but the title is broad. Reviewers may ask whether major MT/LLM translation studies were missed.

Recommended action: either narrow the title/scope to "workflow-oriented scoping survey" or add a paragraph justifying depth-over-breadth sampling and targeted search expansion.

## Moderate Issues

- The abstract still says "working extraction corpus"; change to "final extraction corpus" if the corpus is now final.
- The paper should avoid overclaiming "field is moving" unless tied to evidence clusters.
- Some sections read as polished narrative synthesis, but fewer paragraphs explicitly compare evidence quality across studies.
- The human-centred workflow section is important but still relatively short compared with its stated importance.
- The repository package now uses `https://github.com/Nighthme/llm-translation-workflow-survey`; confirm that the public GitHub release and Zenodo record remain accessible before submission.
- The LaTeX log has only minor warnings: four underfull hboxes and one small overfull hbox in references. These are not blockers.

## Minor Issues

- Consider using "LLM-Augmented" consistently in title/running title and sentence case elsewhere.
- Some figure captions could be more explanatory for standalone reading.
- The AI-use disclosure is present, but it should match the exact target journal wording if the submission system asks for a separate disclosure.
- Temporary figure-check PNGs should not be included in the final repository release.

## Submission Readiness Score

| Dimension | Score | Comment |
|---|---:|---|
| Journal fit | 8.5/10 | Strong topic fit for *Natural Language Processing*. |
| Originality | 7.5/10 | Workflow framing is useful; needs sharper contrast with existing MT/LLM surveys. |
| Method transparency | 6.5/10 | Good local files; main text needs stronger formal reporting. |
| Literature coverage | 7/10 | Good focused corpus; broad title may invite coverage challenges. |
| Reference quality | 8/10 | Reference style has been harmonised and high-risk DOI records have been verified. |
| Figures/tables | 8/10 | Usable and now visually improved. |
| Declarations/data | 8.5/10 | Required sections present and repository DOI inserted. |
| Language polish | 7/10 | Clear, but needs final compression and stronger signposting. |

## Recommendation

Complete one focused final pre-submission revision round:

1. Run one final reference metadata and punctuation pass.
2. Confirm final PDF layout after any metadata edits.
3. Strengthen methods transparency in the manuscript.
4. Clarify PRISMA/background/exclusion categories.
5. Add 2-3 paragraphs that explicitly position the paper against existing MT/LLM surveys.
6. Run one final language and formatting pass.

After those changes, the manuscript should be credible for submission as a Survey Paper.
