# Gap-Fill Literature Supplement

## Purpose

This pass supplements underrepresented areas in the current corpus rather than expanding the review indiscriminately. The added records target gaps in low-resource translation, gender/fairness, hallucination and robustness, multimodal/document-image MT, simultaneous MT, enterprise translation-memory fine-tuning, and pre-LLM NMT/Transformer background.

## Formal Full-Review Additions

| ID | Area Filled | Decision | Rationale |
|---|---|---|---|
| G001 | Low-resource/RAG prompting | Include | Adds Indigenous/lesser-resourced language evidence using GPT-4, Llama 2, Mixtral, dictionary entries, and retrieved examples for Mambai. |
| G002 | Low-resource limitations | Include | Adds a critical WMT study showing that retrieval and understanding both limit LLM translation for Southern Quechua-Spanish. |
| G003 | Low-resource instruction tuning | Include | Adds contrastive alignment instruction tuning for unseen low-resource languages, useful for the tuning/adaptation section. |
| G004 | Gender control | Include | Adds fine-grained entity-level gender control in LLM-based MT and an LLM-as-evaluator angle for gender inflection. |
| G005 | Gender bias and reasoning | Include | Adds a 2025 dataset and evaluation study on genderless-to-gendered translation bias and reasoning errors across GPT-4, NLLB, Google Translate, and mBART-50. |
| G006 | Hallucination mitigation | Include | Adds direct evidence on hallucinated translations in LLM MT and preference-optimization mitigation. |
| G007 | Robustness/noisy input | Include | Adds noisy-source in-context demonstration evidence for translation robustness. |
| G008 | Multimodal MT data augmentation | Include | Adds LLM-based data augmentation for multimodal MT. |
| G009 | Document image MT | Include | Adds document-image MT with dynamic multi-pretrained model assembly, broadening document-level translation beyond plain text. |
| G010 | Simultaneous MT | Include | Adds real-time/simultaneous MT evidence using LLMs, including latency and computation constraints. |
| G011 | Enterprise TM fine-tuning | Include | Adds in-house translation and translation-memory fine-tuning evidence with Llama 3 8B. |

## Background Anchors

| ID | Area | Use |
|---|---|---|
| B001 | Attention-based NMT | Background citation for the transition from phrase-based/statistical MT to attention-based NMT. |
| B002 | GNMT | Background citation for production-scale NMT and sentence-level neural translation. |
| B003 | Transformer | Background citation for the Transformer architecture as the bridge between modern NMT and LLMs. |
| B004 | NLLB-200 | Background citation for massively multilingual human-centered NMT, low-resource coverage, toxicity, and human evaluation. |
| B005 | SEAMLESSM4T | Background citation for multimodal speech/text MT and responsible deployment evaluation. |

## Revised Gap Assessment

The corpus is now stronger in low-resource, fairness, robustness, hallucination, multimodality, and enterprise workflow adaptation. Remaining weak areas are:

- direct evidence from commercial CAT-tool deployments with professional translators;
- privacy/confidentiality studies specific to translation workflows rather than general LLM privacy;
- longitudinal workplace adoption studies measuring trust, responsibility, and productivity over time;
- legal/medical high-stakes professional MTPE with audited risk outcomes;
- reproducibility packages for prompt-based translation workflows.

## Screening Notes

The gap-fill additions are all kept because they fill distinct analytical functions. Some are not human-workflow studies, but they are directly relevant to workflow risk and design: low-resource retrieval, gender control, hallucination mitigation, robustness, multimodal document processing, simultaneous MT, and TM-based customization.
