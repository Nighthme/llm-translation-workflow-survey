# Research Protocol

## Working Title

From Neural Machine Translation to LLM-Augmented Translation Workflows: A Scoping Survey

## Target Journal

Natural Language Processing, Cambridge University Press.

The target article type is a Survey Paper. The journal scope explicitly includes machine translation, translation technology, NLP applications, large language models, multilingual and low-resource language projects, and survey papers that describe the state of the art of a specific topic.

## Review Type

Scoping survey with a PRISMA-ScR-informed search and screening process.

This is not planned as a meta-analysis because the field uses heterogeneous tasks, models, language pairs, datasets, prompts, evaluation metrics, and human evaluation protocols.

## Rationale

Machine translation research has moved from phrase-based and neural machine translation toward Transformer-based NMT and, more recently, LLM-augmented translation workflows. However, existing studies are dispersed across model evaluation, automatic post-editing, quality estimation, document-level translation, terminology control, and human translator interaction. A workflow-oriented survey can clarify how LLMs complement, replace, or reshape NMT-centered translation pipelines.

## Primary Research Question

How have neural machine translation and large language models been integrated into translation workflows, and what methodological, evaluative, and practical gaps remain in current NLP research?

## Sub-Questions

1. What translation workflow stages have NMT, Transformer-based systems, and LLMs been applied to?
2. How do studies evaluate LLM-augmented translation workflows, and how do these evaluation practices differ from traditional MT evaluation?
3. What incremental contributions do LLMs appear to offer over NMT-centered approaches?
4. What risks and limitations recur across current studies, especially regarding hallucination, terminology drift, over-editing, privacy, reproducibility, and closed-source models?
5. What research agenda follows for NLP researchers studying translation technology?

## Time Span

2017-2026.

Rationale: 2017 marks the Transformer turning point for modern NMT. The 2022-2026 period captures the rapid emergence of ChatGPT-style and open-source LLMs in translation workflows.

## Sources

Primary sources:

- ACL Anthology
- Scopus
- Web of Science Core Collection
- IEEE Xplore
- ACM Digital Library
- ScienceDirect
- SpringerLink
- Cambridge Core

Supplementary sources:

- arXiv, clearly tagged as preprint
- Google Scholar for backward and forward citation chasing
- References of included survey papers and WMT/EAMT/AMTA papers

## Inclusion Criteria

- Studies involving machine translation, neural machine translation, Transformer-based MT, LLMs, or generative AI in translation workflows.
- Studies addressing at least one workflow stage: pre-translation preparation, draft generation, interactive translation, post-editing, quality estimation, quality assessment, terminology management, style control, context handling, error explanation, or translator training.
- Empirical studies, system papers, evaluation papers, user studies, survey papers, benchmark papers, and shared-task papers.
- Any language pair, language direction, or domain.
- Peer-reviewed papers and high-value preprints, with publication status recorded.

## Exclusion Criteria

- Papers on general text generation, summarization, question answering, or language learning with no substantive translation component.
- Pure model architecture papers that report MT scores but do not address translation workflows, evaluation practices, or applied translation technology.
- Opinion pieces, blog posts, news articles, non-scholarly essays, and vendor marketing material.
- Papers without accessible full text or with insufficient methodological detail.
- Duplicate reports of the same study unless the later version substantially extends the earlier one.

## Revised Taxonomy After Pilot Screening

1. Pre-translation support
2. Draft generation and direct translation
3. Automatic post-editing
4. Interactive and human-in-the-loop post-editing
5. Terminology, style, and domain control
6. Document-level and context-aware translation
7. Quality estimation, translation quality assessment, and LLM-as-evaluator methods
8. Error explanation, feedback, and evaluator-editor loops
9. Datasets, benchmarks, and shared tasks
10. Multi-agent and workflow orchestration approaches
11. Human workflow outcomes: cognitive load, effort, productivity, trust, and translator expertise
12. Evaluation methodology, reproducibility, ethics, privacy, and professional risk

## Planned Analysis

Descriptive mapping:

- Publication year
- Venue type
- Peer-reviewed versus preprint
- Model/system type
- Workflow stage
- Language pair and domain
- Dataset and evaluation metric
- Human participant involvement
- Availability of code, data, prompt, and model details

Thematic synthesis:

- How the field conceptualizes LLMs: translator, editor, evaluator, assistant, explainer, or workflow orchestrator.
- Evaluation mismatch between model-centered metrics and translator-centered workflow outcomes.
- Evidence gaps in professional translation settings, low-resource languages, specialized domains, and reproducibility.

Final contribution:

- A workflow-oriented taxonomy of LLM-augmented translation research.
- A comparison of NMT-centered and LLM-augmented workflow designs.
- A research agenda for evaluation, reproducibility, human-AI collaboration, and multilingual equity.

## Reporting Standards

- Use a PRISMA-style flow diagram for search and screening.
- Use PRISMA-ScR as a transparency checklist where applicable.
- Include an ethics statement.
- Include an AI-use statement, especially if AI tools are used for screening support, data extraction support, translation, coding assistance, or manuscript editing.
