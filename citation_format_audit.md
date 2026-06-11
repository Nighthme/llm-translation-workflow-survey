# Citation, Reference, DOI, and Journal-Format Audit

Manuscript: *From Neural Machine Translation to LLM-Augmented Translation Workflows: A Scoping Survey*  
Target journal: *Natural Language Processing*  
Audit date: 2026-06-11

## Summary Decision

**Status: substantially improved. The data-availability DOI has been inserted, and the previously high-risk DOI-bearing records have now been verified through official publisher/Crossref metadata.**

The manuscript now has no obvious unresolved citation-reference mismatch. The major format issue found during this audit was that several three-author in-text citations used full author lists instead of first-author `et al.` form. These were corrected in the LaTeX manuscript. Follow-up checks verified the previously high-risk records through official publisher/Crossref metadata.

## 1. In-Text Citation and Reference Correspondence

### Result

No substantive missing-reference or orphan-reference problem was found after manual review of the automated extraction results.

### Automated false positives resolved

The first automated pass falsely flagged second or third authors as missing references, for example:

- `Cho 2015` from `(Bahdanau, Cho and Bengio 2015)`
- `Llorens 2022` from `(Vidal, Llorens and Alonso 2022)`
- `Han 2026` from `Yao, Han and Li 2026`
- `Leng 2024` from `Pan, Leng and Xiong 2024`
- `Communication 2025` from `Seamless Communication et al. 2025`

These are not missing-reference errors; they arise from simplistic parsing of multi-author strings or group-author names.

### Corrections made

The following in-text/table citations were corrected to first-author `et al.` form:

- `Bahdanau, Cho and Bengio 2015` -> `Bahdanau et al. 2015`
- `Vidal, Llorens and Alonso 2022` -> `Vidal et al. 2022`
- `Yao, Han and Li 2026` -> `Yao et al. 2026`
- `Mau, Wu and Feng 2026` -> `Mau et al. 2026`
- `Tang, Chatterjee and Garg 2025` -> `Tang et al. 2025`
- `Pan, Leng and Xiong 2024` -> `Pan et al. 2024`

## 2. DOI and Source Authenticity Check

### Verified through official publisher or index pages

The following records were checked against official pages or DOI redirects during this audit:

- Ataman et al. 2025, `Information` 16(9):723, DOI `10.3390/info16090723`.
- Karpinska and Iyyer 2023, ACL Anthology record `2023.wmt-1.41`, pages 419--451, DOI `10.18653/v1/2023.wmt-1.41`.
- Lu et al. 2024, ACL Anthology record `2024.findings-acl.520`, pages 8801--8816, DOI `10.18653/v1/2024.findings-acl.520`.
- Lu et al. 2025, ACL Anthology record `2025.coling-main.374`, pages 5570--5587; no DOI listed on the ACL record.
- Vidal et al. 2022, ACL Anthology record `2022.amta-upg.7`, pages 84--106; no DOI listed on the ACL record.
- Macken 2024, ACL Anthology record `2024.ctt-1.7`, pages 65--81; no DOI listed on the ACL record.
- Moslem et al. 2023b, ACL Anthology record `2023.eamt-1.22`, pages 227--237; no DOI listed on the ACL record.
- Zou et al. 2024, ACL Anthology record `2024.amta-presentations.19`, pages 259--260; no DOI listed on the ACL record.
- Cambridge *Natural Language Processing* author instructions and preparing-materials pages were checked for article type, ORCID, AI-use, figure/table, accessibility, and declaration requirements.

### Follow-up verification of previously high-risk records

The following records were moved out of the high-risk category after direct official-page checks:

- Chen 2025 was verified on the official *Frontiers in Psychology* article page. The page identifies the article as an original research article, published on 12 November 2025 in volume 16, with DOI `10.3389/fpsyg.2025.1570929`.
- Grubisic and Korencic 2025 was verified on the official ACL Anthology page. The page lists Anthology ID `2025.wmt-1.110`, pages 1302--1334, Suzhou, China, DOI `10.18653/v1/2025.wmt-1.110`, and the proceedings title \emph{Proceedings of the Tenth Conference on Machine Translation}.
- Huang et al. 2025 was verified through Wiley/Crossref metadata for *International Journal of Intelligent Systems* 2025(1), article `9971702`, DOI `10.1155/int/9971702`, published on 15 October 2025.
- Mau et al. 2026 was verified through Elsevier/Crossref metadata for *System* 139, article `104033`, PII `S0346251X26000643`, DOI `10.1016/j.system.2026.104033`.
- Yao et al. 2026 was verified through Taylor & Francis/Crossref metadata for *International Journal of Human-Computer Interaction*, pages 1--20, DOI `10.1080/10447318.2026.2628994`, published online on 20 February 2026.

### DOI syntax status

The manuscript contains syntactically plausible DOI strings for the DOI-bearing entries. The HiT-IT DOI strings contain escaped underscores in LaTeX, e.g. `2023\_009`; this is correct for LaTeX typesetting and should render as an underscore in the PDF.

### High-risk records requiring final verification or replacement

No DOI-bearing records remain in the high-risk metadata category after the follow-up verification pass on 2026-06-11.

### Records without DOI in the manuscript

Several references do not currently include a DOI. This is acceptable only if the official source does not provide a DOI or if DOI metadata could not be confirmed. Before final submission, the following should receive one last metadata check:

- Bahdanau et al. 2015
- Berger et al. 2024
- Castilho and Knowles 2024
- Kocmi and Federmann 2023a
- Li et al. 2025
- Macken 2024
- Merx et al. 2024
- Moslem et al. 2023b
- Pan et al. 2024
- Sinitsyna and Savenkov 2024
- Vidal et al. 2022
- Vieira et al. 2024
- Wang et al. 2024, ALTA
- Zou et al. 2024

Some of these are official ACL/AMTA/EAMT records without DOI on the source page, so missing DOI is not automatically an error.

## 3. Reference Format Audit

### What now matches target style

- In-text citations are author-date style.
- Same-author same-year citations are disambiguated where needed: `Kocmi and Federmann 2023a/2023b`; `Moslem et al. 2023a/2023b`.
- Three-or-more-author in-text citations now use first-author `et al.` form.
- Reference list is alphabetised by first author/group author.
- DOI-bearing references include DOI strings.

### Reference-list style status

The reference list has now been converted from full-given-name entries to a Cambridge-style author-date format using surname plus initials and year in parentheses, for example:

`Ataman, D., Birch, A., Habash, N., Federico, M., Koehn, P. and Cho, K. (2025). ...`

This is substantially closer to the journal's expected author-date presentation. A final copy-edit may still adjust punctuation, capitalization, or proceedings metadata if the production office applies a stricter house style.

## 4. Target-Journal Format Compliance

### Meets or substantially meets

- Article type: Survey Paper is accepted by the journal.
- Abstract: present.
- Keywords: present.
- Author metadata: author, affiliation, email, and ORCID present.
- ORCID: present for corresponding author.
- Competing interests declaration: present.
- Funding statement: present.
- Ethics statement: present.
- AI-use disclosure: present in acknowledgements.
- Figures and tables: numbered by LaTeX, captioned, and now called out in the body text.
- Figure/table captions: self-explanatory and source-labelled.
- Accessibility direction: colour palette is muted and colourblind-friendlier than the earlier version; formal alt text is still not embedded in the manuscript file.

### Remaining issue explicitly excluded by author instruction

- Data availability statement now includes the Zenodo DOI `https://doi.org/10.5281/zenodo.20645622` and the GitHub repository link.

### Remaining minor issues

- The final PDF compiles successfully, but the LaTeX log reports minor underfull/overfull boxes in long reference lines.
- Reference list has been converted to a surname-initials author-date style; a production-level copy-edit may still adjust punctuation.
- Figure alt-text/accessibility descriptions should be prepared for submission if the system requests them.

## 5. Edits Made During This Audit

- Corrected multi-author in-text citations to `et al.` form.
- Added explicit in-text callouts for Figure 1, Figure 2, Table 1, Figure 3, Table 2, Figure 4, and Table 3.
- Verified Chen 2025 through Frontiers and Grubisic and Korencic 2025 through ACL Anthology.
- Verified Huang 2025, Mau 2026, and Yao 2026 through official publisher/Crossref metadata and removed the unresolved high-risk flags.
- Converted the reference list to surname-initials author-date format.
- Recompiled `manuscript_nlp_cambridge_expanded_revised.pdf` successfully.

## Overall Conclusion

The citation network is internally coherent after the corrections made in this audit. The reference list is credible and mostly verifiable, with DOI-bearing entries confirmed against official publisher, Crossref, ACL, or DOI pages. The manuscript is close to target-journal format expectations.
