# Metadata Cleanup and Quality Grading

## Scope

This pass focused on records D011-D014, which had incomplete metadata or uncertain publication status after the additional-source expansion.

## Metadata Cleanup Results

| ID | Status | Cleanup Result |
|---|---|---|
| D011 | Verified | Authors corrected to Marina Sanchez-Torron, Egemen Ipek, Vanessa Enriquez Raido. Year corrected from 2026 to 2025 based on e-pub ahead-of-print status. DOI verified: `10.1007/s40593-025-00465-x`. |
| D012 | Verified | Author verified as Michael Farrell. HiT-IT 2023 proceedings, pages 108-113. DOI verified: `10.26615/issn.2683-0078.2023_009`. |
| D013 | Verified | Full 16-author list verified. HiT-IT 2023 proceedings, pages 282-287. DOI verified: `10.26615/issn.2683-0078.2023_023`. |
| D014 | Verified and added | Publication status verified as a peer-reviewed HCII 2024 Springer proceedings chapter by Ming Qian and Chuiqing Kong, pages 118-134. Added to formal extraction table. Chapter DOI still needs final formatting verification; book DOI is `10.1007/978-3-031-60615-1`. |

## Deduplication Check

No duplicates were found among D011-D014 and existing records.

Potential conceptual overlaps, not duplicates:

- D012 overlaps conceptually with D007 and S004 because all address ChatGPT/GPT as translator or post-editor, but D012 is distinct by language pair, source venue, and evaluation design.
- D013 overlaps conceptually with S002, S003, S008, S011, and D009 because all address LLM-based MT evaluation, but D013 is distinct because it uses human Direct Assessment of ChatGPT versus commercial MT systems.
- D014 overlaps conceptually with D006 and C003 because all involve adaptive or human-in-the-loop workflows, but D014 is distinct because it proposes concept-based prompting plus translation memory.

## Quality Grading Scheme

Quality grading is provisional and designed for scoping-review weighting rather than exclusion.

| Grade | Meaning |
|---|---|
| A | Peer-reviewed journal or major NLP/HCI conference paper with clear methods, strong fit, and usable evaluation details. |
| B | Peer-reviewed conference/workshop/proceedings paper or journal article with good topical fit but limited scope, short format, preliminary design, or missing artifacts. |
| C | High-value preprint, technical report, or weakly documented study; useful but should be interpreted cautiously. |
| Background | Conceptual, broad, or adjacent source useful for framing but not formal evidence extraction. |

## Quality Grades for D011-D014

| ID | Grade | Rationale |
|---|---|---|
| D011 | A- | Peer-reviewed journal article with strong terminology/HITL relevance. Slightly downgraded because it is translator assessment/education-oriented rather than a direct MT workflow evaluation. |
| D012 | B | Peer-reviewed/proceedings paper with direct MT/APE relevance, but explicitly preliminary, limited to English-Italian Wikipedia texts, and based on the free-plan ChatGPT version. |
| D013 | B+ | Peer-reviewed/proceedings paper with human Direct Assessment and domain comparison. Short preliminary format and incomplete artifact reporting prevent an A grade. |
| D014 | B+ | Peer-reviewed HCII/Springer proceedings chapter with strong human-centered workflow relevance. Small-example/evaluator design and chapter DOI/artifact uncertainty prevent an A grade. |

## Corpus Count After Cleanup

- Formal extraction records before cleanup: 36
- D014 newly added: 1
- Formal extraction records after cleanup: 37

