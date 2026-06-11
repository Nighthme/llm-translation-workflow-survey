# Pilot Screening Summary

## Scope

Pilot screening was conducted on 16 seed records identified from the target journal, ACL Anthology, WMT, EAMT, AMTA, NAACL, ACL, COLING, and TermTrends.

## Screening Outcome

All 16 seed records were retained for full review.

Reasons:

- Each record directly concerns machine translation, NMT, LLMs, or translation technology.
- Each record maps onto at least one workflow function rather than only generic NLP text generation.
- The set covers both direct LLM use and hybrid NMT plus LLM workflows.

## Emerging Clusters

1. Automatic post-editing
2. Translation quality assessment and LLM-as-evaluator workflows
3. Terminology-constrained translation and terminology control
4. Document-level and context-aware translation
5. Dataset and benchmark construction
6. Multi-agent or multi-role LLM translation workflows

## Taxonomy Revision Suggested by Pilot

The original taxonomy should be revised slightly:

1. Pre-translation support
2. Draft generation and direct translation
3. Automatic post-editing
4. Interactive and human-in-the-loop post-editing
5. Terminology, style, and domain control
6. Document-level and context-aware translation
7. Quality estimation, quality assessment, and LLM-as-evaluator methods
8. Error explanation, feedback, and evaluator-editor loops
9. Datasets, benchmarks, and shared tasks
10. Multi-agent and workflow orchestration approaches
11. Reproducibility, ethics, privacy, and professional risk

## Early Analytical Observations

- LLMs are often framed less as replacements for NMT and more as post-editors, evaluators, terminology assistants, or context-aware refiners.
- Evaluation remains fragmented. Model-centered metrics such as BLEU, COMET, TER, MetricX, and terminology metrics coexist with MQM, human preference, trustworthiness, and expert annotation.
- Closed-source LLM dependence is a recurring reproducibility problem, especially for GPT-4-based evaluators and post-editors.
- Human workflow outcomes are underrepresented. Few pilot records clearly measure translator productivity, cognitive load, trust, or professional decision-making.
- The most promising novelty for the survey is a workflow-oriented synthesis connecting APE, LQA, terminology control, context, and multi-agent systems.

## Immediate Follow-Up

1. Extract full-text details for model names, prompts, datasets, and code/data availability.
2. Expand the search beyond ACL Anthology to Scopus and Web of Science.
3. Add a specific search branch for human translator interaction, productivity, cognitive load, and trust.
4. Add a specific search branch for privacy and professional translation workflows.

