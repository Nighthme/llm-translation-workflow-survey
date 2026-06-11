# Evidence Map

## Current Corpus

Current evidence corpus after pilot screening, human-workflow expansion, and additional-source expansion:

- Total records in extraction table: 48
- Background-only records kept outside formal extraction: 7
- Candidate pending metadata outside formal extraction: 1

## Publication Year Distribution

| Year | Records |
|---|---:|
| 2022 | 1 |
| 2023 | 10 |
| 2024 | 20 |
| 2025 | 15 |
| 2026 | 2 |

Interpretation: the corpus is concentrated after the release of ChatGPT-style GenAI systems, with 2023-2025 forming the evidence core.

## Source Family Distribution

| Source family | Records |
|---|---:|
| ACL Anthology | 31 |
| ACL Anthology / arXiv | 2 |
| HiT-IT proceedings | 2 |
| Cambridge Core | 1 |
| Frontiers | 1 |
| Frontiers / PMC | 1 |
| MDPI | 1 |
| Nature Portfolio | 1 |
| SAGE | 1 |
| ScienceDirect | 1 |
| ScienceDirect / PolyU | 1 |
| Springer LNCS/LNAI proceedings | 1 |
| Springer | 1 |
| Taylor & Francis | 1 |
| Wiley | 1 |
| arXiv | 1 |

Interpretation: NLP conference literature still dominates model-centered workflow evidence, but the corpus now includes journal literature from HCI, translation education, social sciences, and applied AI sources.

## Consolidated Evidence Clusters

### 1. Automatic Post-Editing and LLM-as-Editor

Representative records:

- S004: GPT-4 for automatic translation post-editing.
- S005: LLaMA-2 guided by MQM annotations.
- S007: contextual sentence/document-level post-editing.
- S009: early GPT-3 post-editing and glossary use case.
- S015: LangMark multilingual APE dataset.
- S016: document-level APE using monolingual data.
- D001: ChatGPT-4o post-editing across English-Arabic domains.
- D002: reasoning-guided post-editing feedback for LLM optimization.
- D012: preliminary ChatGPT as MT engine and APE tool.

Analytical angle:
LLMs are frequently positioned as editors of NMT output rather than direct replacements for specialized MT systems. The new evidence adds cross-domain Arabic MTPE and synthetic feedback-based optimization.

### 2. Translation Quality Assessment and LLM-as-Evaluator

Representative records:

- S002: GEMBA.
- S003: GEMBA-MQM.
- S008: multi-model LQA pipeline.
- S011: Error Analysis Prompting.
- S012: MQM-APE evaluator-editor loop.
- D009: information needs for LLM-based MT evaluation.
- D013: human evaluation for ChatGPT translation quality.

Analytical angle:
LLM evaluation research is moving from scalar quality scores toward error spans, MQM-style explanations, information-aware prompting, and evaluator-editor loops. Human direct assessment remains important for calibrating claims about LLM quality.

### 3. Terminology, Domain, and Low-Resource Control

Representative records:

- S010: terminology integration with synthetic data and LLM post-editing.
- S013: metric-guided multi-agent terminology workflow.
- S014: LegISTyr test set for low-resource legal terminology.
- C003: human error markings and PE-TM prompting.
- D006: adaptive MT with in-context examples, fuzzy matches, and translation memories.
- D008: instruction-tuned medical-domain MT with specialized terminology.
- D011: GPT-4-generated terminology recognition tests.
- D014: concept-based GPT-4 prompting and translation memory.
- G001: retrieval-augmented LLM prompting for Mambai low-resource MT.
- G002: low-resource translation limitations from retrieval and understanding failures.
- G003: contrastive alignment instruction tuning for unseen low-resource languages.
- G011: in-house LLM fine-tuning with organization-specific translation memories.

Analytical angle:
Terminology control is one of the clearest workflow-level motivations for combining NMT, LLMs, human feedback, translation memories, task-specific metrics, and translator competence assessment.

Low-resource evidence now adds an important caution: retrieval, dictionaries, and prompts can help, but community-specific corpora, representative test sets, and linguistic understanding remain limiting factors.

### 4. Document-Level and Context-Aware Translation

Representative records:

- S001: context in NMT and evaluation.
- S006: document-level literary translation with LLMs.
- S007: contextual refinement.
- S016: document-level post-editing with monolingual data.
- D005: EMNLP document-level MT with LLMs.
- G008: LLM-based data augmentation for multimodal MT.
- G009: document-image MT with dynamic multi-pretrained model assembling.

Analytical angle:
LLMs' long-context capabilities are promising, but evidence shows persistent critical errors, metric disagreement, and uneven gains across domains. Document-level quality also exposes weaknesses in sentence-level evaluation.

The multimodal additions broaden this cluster from text-only documents to image-conditioned and document-image translation, where layout, visual context, and OCR-like errors become part of the translation workflow.

### 5. Human-Centered Workflow Outcomes

Representative records:

- C001: AI-assisted post-editing and cognitive ergonomics.
- C002: syntactic complexity in GPT-4 post-editing with students and expert translators.
- C004: GPT post-editing in learner translation.
- C006: eye-tracking in human-machine collaborative translation.
- C007: professional literary translators versus ChatGPT post-editing.
- C008: GenAI-assisted legal translation and student cognitive load.
- D003: GenAI translation versus human translation of scientific texts.
- D010: NMT plus human post-editing in intangible cultural heritage translation.
- D014: human-centered concept-based MT workflow with GPT-4 and translation memory.
- G010: simultaneous MT with LLMs, highlighting latency, robustness, and computation constraints for live workflows.

Analytical angle:
Human-centered studies show that LLM assistance reshapes rather than simply reduces translator effort. Cognitive load, decision effort, expertise, trust, cultural adequacy, domain knowledge, and over-editing must be evaluated alongside automatic MT quality metrics.

The simultaneous MT addition makes latency and deployment cost explicit workflow variables rather than only engineering details.

### 6. Fairness, Safety, Hallucination, and Robustness

Representative records:

- G004: fine-grained gender control in LLM-based MT.
- G005: Translate-with-Care dataset for gender bias, neutrality, and reasoning.
- G006: hallucination-focused preference optimization for LLM MT.
- G007: noisy-source in-context demonstrations for translation robustness.

Analytical angle:
LLM-augmented translation workflows must be evaluated for more than adequacy and fluency. Gender representation, reasoning consistency, hallucinated content, noisy-source robustness, and trust/safety risks are now a distinct evidence cluster.

### 7. Survey and Background Anchors

Representative records:

- S001: context in NMT and evaluation.
- D004: MT in the era of LLMs historical/emerging-problems survey.
- C005: trust, understanding, and translator responsibility.
- D015: translator training in digital intelligence.
- B001-B005: attention-based NMT, GNMT, Transformer, NLLB-200, and SEAMLESSM4T as background anchors.

Analytical angle:
These records will help frame the contribution of the present review: it is not a general MT/LLM survey, but a workflow-oriented scoping survey focused on where LLMs enter translation processes and how their effects are evaluated.

## Working Thesis

The emerging evidence suggests that LLMs are best understood as workflow components in machine translation systems: they act as post-editors, evaluators, terminology controllers, context refiners, explainers, adaptive translation-memory users, translator-training supports, and interaction partners. The central gap is not merely whether LLMs improve MT output quality, but whether LLM-augmented workflows are reliable, reproducible, cognitively ergonomic, terminology-aware, culturally adequate, and accountable in real translation settings.
