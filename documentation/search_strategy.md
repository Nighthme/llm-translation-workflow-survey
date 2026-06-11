# Search Strategy

## Core Concept Blocks

### Block A: Translation Technology

```text
"machine translation" OR "neural machine translation" OR NMT OR "translation technology" OR "computer-assisted translation" OR CAT OR "translation workflow" OR "automatic post-editing"
```

### Block B: LLMs and Modern NLP Models

```text
"large language model*" OR LLM OR "generative AI" OR ChatGPT OR GPT OR GPT-3 OR GPT-4 OR GPT-4o OR Gemini OR Claude OR LLaMA OR BLOOM OR PaLM OR "instruction-tuned" OR Transformer
```

### Block C: Workflow Functions

```text
workflow OR "post-editing" OR "quality estimation" OR "translation quality assessment" OR "quality evaluation" OR terminology OR "term consistency" OR "style adaptation" OR "domain adaptation" OR "document-level" OR context OR "human evaluation" OR translator OR "human-AI collaboration"
```

## Master Search String

```text
("machine translation" OR "neural machine translation" OR NMT OR "translation technology" OR "computer-assisted translation" OR CAT OR "translation workflow" OR "automatic post-editing")
AND
("large language model*" OR LLM OR "generative AI" OR ChatGPT OR GPT OR GPT-3 OR GPT-4 OR GPT-4o OR Gemini OR Claude OR LLaMA OR BLOOM OR PaLM OR "instruction-tuned" OR Transformer)
AND
(workflow OR "post-editing" OR "quality estimation" OR "translation quality assessment" OR "quality evaluation" OR terminology OR "term consistency" OR "style adaptation" OR "domain adaptation" OR "document-level" OR context OR "human evaluation" OR translator OR "human-AI collaboration")
```

## ACL Anthology Search Variants

ACL Anthology search is often more effective with shorter strings:

```text
"large language models" "machine translation"
"ChatGPT" "machine translation"
"GPT-4" "post-editing" "machine translation"
"large language models" "translation quality"
"LLM" "quality estimation" "machine translation"
"document-level" "large language models" "translation"
"terminology" "large language models" "machine translation"
```

## Scopus / Web of Science Fielded Draft

### Scopus Main Search

```text
TITLE-ABS-KEY(("machine translation" OR "neural machine translation" OR NMT OR "translation technology" OR "computer-assisted translation" OR "automatic post-editing")
AND
("large language model*" OR LLM OR "generative AI" OR ChatGPT OR GPT OR GPT-4 OR Gemini OR Claude OR LLaMA OR Transformer)
AND
("post-editing" OR workflow OR "quality estimation" OR "translation quality assessment" OR terminology OR "document-level" OR context OR "human evaluation" OR translator))
AND PUBYEAR > 2016
```

Recommended Scopus filters:

- Year: 2017-2026
- Document type: Article, Conference Paper, Review
- Subject areas: Computer Science; Arts and Humanities; Social Sciences; Engineering
- Language: English for the first formal pass; non-English sources may be added as supplementary records if metadata and full text are usable

### Scopus Workflow-Specific Searches

Automatic post-editing:

```text
TITLE-ABS-KEY(("machine translation" OR NMT OR "neural machine translation")
AND
("large language model*" OR LLM OR ChatGPT OR GPT-4 OR GPT OR "generative AI")
AND
("post-editing" OR "automatic post-editing" OR APE OR "machine translation post-editing" OR MTPE))
AND PUBYEAR > 2016
```

Quality assessment and evaluation:

```text
TITLE-ABS-KEY(("machine translation" OR NMT OR "neural machine translation")
AND
("large language model*" OR LLM OR ChatGPT OR GPT-4 OR GPT OR "generative AI")
AND
("quality assessment" OR "quality estimation" OR "human evaluation" OR MQM OR COMET OR BLEU OR TER OR "error analysis"))
AND PUBYEAR > 2016
```

Terminology and domain control:

```text
TITLE-ABS-KEY(("machine translation" OR NMT OR "translation technology")
AND
("large language model*" OR LLM OR ChatGPT OR GPT-4 OR "generative AI")
AND
(terminology OR glossary OR "term consistency" OR "domain adaptation" OR "terminology-constrained"))
AND PUBYEAR > 2016
```

Document-level and context-aware translation:

```text
TITLE-ABS-KEY(("machine translation" OR NMT OR "neural machine translation")
AND
("large language model*" OR LLM OR ChatGPT OR GPT-4 OR "generative AI")
AND
("document-level" OR "context-aware" OR context OR discourse OR coherence OR consistency))
AND PUBYEAR > 2016
```

### Web of Science Main Search

```text
TS=(("machine translation" OR "neural machine translation" OR NMT OR "translation technology" OR "computer-assisted translation" OR "automatic post-editing")
AND
("large language model*" OR LLM OR "generative AI" OR ChatGPT OR GPT OR "GPT-4" OR Gemini OR Claude OR LLaMA OR Transformer)
AND
("post-editing" OR workflow OR "quality estimation" OR "translation quality assessment" OR terminology OR "document-level" OR context OR "human evaluation" OR translator))
AND PY=(2017-2026)
```

Recommended Web of Science indexes:

- Science Citation Index Expanded
- Social Sciences Citation Index
- Arts and Humanities Citation Index
- Conference Proceedings Citation Index, if available
- Emerging Sources Citation Index may be searched but flagged separately if the target analysis distinguishes core indexes

### Web of Science Workflow-Specific Searches

```text
TS=(("machine translation" OR "neural machine translation" OR NMT)
AND
("large language model*" OR LLM OR ChatGPT OR GPT OR "GPT-4" OR "generative AI")
AND
("automatic post-editing" OR "post-editing" OR MTPE OR APE))
AND PY=(2017-2026)
```

```text
TS=(("machine translation" OR "neural machine translation" OR NMT)
AND
("large language model*" OR LLM OR ChatGPT OR GPT OR "GPT-4" OR "generative AI")
AND
("quality assessment" OR "quality estimation" OR MQM OR COMET OR BLEU OR TER OR "error analysis"))
AND PY=(2017-2026)
```

```text
TS=(("machine translation" OR "neural machine translation" OR NMT)
AND
("large language model*" OR LLM OR ChatGPT OR GPT OR "GPT-4" OR "generative AI")
AND
(terminology OR glossary OR "term consistency" OR "domain adaptation" OR "terminology-constrained"))
AND PY=(2017-2026)
```

```text
TS=(("machine translation" OR "neural machine translation" OR NMT)
AND
("large language model*" OR LLM OR ChatGPT OR GPT OR "GPT-4" OR "generative AI")
AND
("document-level" OR "context-aware" OR context OR discourse OR coherence OR consistency))
AND PY=(2017-2026)
```

## Human Translator Interaction / Cognitive Load / Trust Search Line

This search line is designed to correct the pilot-screening gap: human workflow outcomes were underrepresented in the first seed set.

### Concept Block D: Human Workflow Outcomes

```text
translator* OR "human translator*" OR "professional translator*" OR "student translator*" OR "post-editor*" OR "human-in-the-loop" OR "human-AI collaboration" OR "human-machine collaboration" OR "cognitive load" OR "cognitive effort" OR "cognitive ergonomics" OR eye-tracking OR eyetracking OR keylogging OR keystroke* OR "technical effort" OR "temporal effort" OR productivity OR trust OR reliance OR acceptance OR "perceived usefulness" OR "user experience"
```

### Scopus Human Workflow Search

```text
TITLE-ABS-KEY(("machine translation" OR "neural machine translation" OR NMT OR "post-editing" OR MTPE OR "translation workflow")
AND
("large language model*" OR LLM OR "generative AI" OR ChatGPT OR GPT OR "GPT-4" OR Claude OR Gemini)
AND
(translator* OR "professional translator*" OR "student translator*" OR "post-editor*" OR "human-AI collaboration" OR "human-machine collaboration" OR "cognitive load" OR "cognitive effort" OR "cognitive ergonomics" OR eye-tracking OR eyetracking OR keylogging OR keystroke* OR "technical effort" OR "temporal effort" OR productivity OR trust OR reliance OR acceptance OR "perceived usefulness" OR "user experience"))
AND PUBYEAR > 2016
```

### Web of Science Human Workflow Search

```text
TS=(("machine translation" OR "neural machine translation" OR NMT OR "post-editing" OR MTPE OR "translation workflow")
AND
("large language model*" OR LLM OR "generative AI" OR ChatGPT OR GPT OR "GPT-4" OR Claude OR Gemini)
AND
(translator* OR "professional translator*" OR "student translator*" OR "post-editor*" OR "human-AI collaboration" OR "human-machine collaboration" OR "cognitive load" OR "cognitive effort" OR "cognitive ergonomics" OR eye-tracking OR eyetracking OR keylogging OR keystroke* OR "technical effort" OR "temporal effort" OR productivity OR trust OR reliance OR acceptance OR "perceived usefulness" OR "user experience"))
AND PY=(2017-2026)
```

### Supplementary Human Workflow Queries

```text
"AI-assisted post-editing" "cognitive load"
"large language models" "post-editing" translator "cognitive effort"
"ChatGPT" "post-editing" translator trust
"large language models" "translation workflow" "human-AI collaboration"
"GPT-4" "post-editing" "professional translators"
"machine translation post-editing" "eye-tracking" "large language models"
```

## Google Scholar Supplementary Queries

```text
"LLM-augmented translation workflow"
"large language models" "machine translation" "post-editing"
"large language models" "translation quality assessment" MQM
"ChatGPT" "machine translation" "human evaluation"
"large language models" "terminology" "machine translation"
```

## Search Log Template

| Date | Database | Search string | Filters | Hits | Export file | Notes |
|---|---|---|---|---:|---|---|
|  | ACL Anthology |  | 2017-2026 |  |  |  |
|  | Scopus |  | 2017-2026, article/conference/review |  |  |  |
|  | Web of Science |  | 2017-2026 |  |  |  |
|  | Scopus | Human workflow search | 2017-2026, article/conference/review |  |  | translator interaction/cognitive load/trust |
|  | Web of Science | Human workflow search | 2017-2026 |  |  | translator interaction/cognitive load/trust |
|  | IEEE Xplore |  | 2017-2026 |  |  |  |
|  | ACM Digital Library |  | 2017-2026 |  |  |  |
|  | Google Scholar |  | first 100 results |  |  | supplementary |

## Gap-Fill Search Lines Added After Evidence Mapping

These lines are intended to fill underrepresented cells in the evidence map.

### Low-Resource and Retrieval-Augmented Translation

```text
("large language model*" OR LLM OR GPT OR ChatGPT OR Llama OR Mixtral)
AND ("machine translation" OR "automatic translation")
AND ("low-resource" OR "lesser-resourced" OR Indigenous OR endangered)
AND (retrieval OR dictionary OR glossary OR "in-context learning" OR prompting)
```

### Fairness, Gender, Hallucination, and Robustness

```text
("large language model*" OR LLM OR GPT OR ChatGPT)
AND ("machine translation" OR translation)
AND (gender OR fairness OR bias OR hallucination OR robustness OR "noisy source" OR safety OR trust)
```

### Multimodal, Document-Image, and Speech/Simultaneous MT

```text
("large language model*" OR LLM OR "pre-trained model*" OR multimodal)
AND ("machine translation" OR "document image translation" OR "simultaneous machine translation" OR "speech translation")
AND (image OR document OR layout OR speech OR latency OR multimodal)
```

### Enterprise and Translation-Memory Adaptation

```text
("large language model*" OR LLM OR Llama OR GPT)
AND ("translation memory" OR "in-house translation" OR "computer-assisted translation" OR CAT)
AND (fine-tuning OR adaptation OR customization OR enterprise OR organization-specific)
```
