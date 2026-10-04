

# For Finding the best Paper's Bibtex of the paper , Using PROMT
===============
Act as a careful academic research assistant. I am writing the Related Work
section of a paper on: [TOPIC / KEYWORDS / SUB-AREA].

TASK
Find peer-reviewed papers I can cite and give each as a ready-to-use BibTeX
entry. Use only the venues listed below that are relevant to my topic.

STRICT RULES
1. SKIP all preprints: arXiv, SSRN, ResearchGate, TechRxiv, bioRxiv, and
   papers that are only under review on OpenReview. If a paper exists as a
   preprint AND a published version, cite the published version only.
2. SKIP all MDPI journals (Sensors, Applied Sciences, Electronics,
   Mathematics, Remote Sensing, etc.; DOI starting 10.3390) and Frontiers.
3. Journals must be Q1 (Scimago or Clarivate JCR). Conferences must be
   CORE A* or A. Confirm the current rank before including a paper; if it
   is not Q1 / A*/A, exclude it.
4. Recency: prioritize 2025-2026, allow 2023-2024 if highly relevant, and
   include at most [2-3] older foundational papers, labeled "foundational".

TOP JOURNALS (all Q1)
- ML/DL/AI: IEEE TPAMI, JMLR, Artificial Intelligence, JAIR, Machine
  Learning, IEEE TNNLS, Neural Networks, Nature Machine Intelligence
- Vision: IJCV, IEEE TIP, CVIU, Pattern Recognition, IEEE TCSVT, Medical
  Image Analysis, IEEE TMI, IEEE TGRS, ISPRS Journal
- General CS/Eng: JACM, ACM Computing Surveys, IEEE TKDE, ACM TOIS, IEEE TSE,
  ACM TOSEM, IEEE TC, ACM TOCS, IEEE TPDS, IEEE/ACM ToN, IEEE TDSC, IEEE TIFS,
  Journal of Cryptology, ACM TOG, IEEE TVCG, ACM TOCHI, TACL, Computational
  Linguistics, IEEE/ACM TASLP, IEEE T-RO, IJRR, IEEE TSP, IEEE TCYB,
  IEEE TII, Information Fusion

TOP CONFERENCES (all A*/A)
- ML: NeurIPS, ICML, ICLR, AISTATS, UAI, COLT, MLSys
- AI: AAAI, IJCAI
- Vision: CVPR, ICCV, ECCV, WACV
- NLP/LLM: ACL, EMNLP, NAACL, EACL
- Robotics: ICRA, IROS, RSS, CoRL
- Data mining/Web: KDD, WWW, WSDM, ICDM
- Security: IEEE S&P, USENIX Security, ACM CCS, NDSS
- Networking: SIGCOMM, NSDI, MobiCom, INFOCOM, SIGMETRICS
- Mobile/Sensing: SenSys, MobiSys, PerCom
- Systems: SOSP, OSDI, EuroSys, ASPLOS, USENIX ATC, FAST
- Databases: SIGMOD, VLDB, ICDE
- Software Eng.: ICSE, FSE, ASE
- HCI: CHI, UIST, CSCW
- Theory: STOC, FOCS, SODA
- PL: POPL, PLDI, OOPSLA
- Architecture/EDA: ISCA, MICRO, HPCA, DAC, ICCAD
- Graphics: SIGGRAPH, SIGGRAPH Asia
- Cryptography: CRYPTO, EUROCRYPT, ASIACRYPT
- IR: SIGIR | Social: ICWSM | Multimedia: ACM MM
- Bioinformatics: ISMB, RECOMB
- Speech/Signal: ICASSP, INTERSPEECH
- Verification: CAV
Allowed publishers/proceedings: IEEE, ACM, Springer, Elsevier, Wiley,
Taylor & Francis, SAGE, PMLR, NeurIPS Proceedings, CVF Open Access,
ACL Anthology, AAAI, IJCAI, USENIX, OpenReview (accepted papers only).

VERIFICATION
- Verify title, authors, venue, year, volume, pages/article number, and DOI
  via Google Scholar or the publisher page before including each paper.
- If you cannot browse, say so at the top. Never invent or guess a field;
  mark uncertain fields "UNVERIFIED".
- If you cannot find enough papers that meet all rules, return fewer.
  Do not relax the rules to reach a number.

OUTPUT (for each of [15-20] papers)
1. BibTeX (key: firstauthorYEARkeyword; @article for journals,
   @inproceedings for conferences)
2. One line: what the paper contributes
3. One line: where in Related Work to cite it
4. Venue, publisher, Q1 or A*/A, DOI
5. Status: VERIFIED (source) or UNVERIFIED

Group by sub-theme. End with a list of gaps you could not fill.



# only for Confirence Related work the pormot is , 
===========
==========================================

For a conference paper, we can structure the Related Work section into exactly four concise paragraphs, rather than making it look like a long thesis-style literature review.

Recommended 4-Paragraph Structure

Paragraph 1 — Importance + First Key Work
Start with why the research problem is important, then introduce the first highly relevant study. In about 2–3 sentences, explain what they did, why they did it, and what their work contributes.

Paragraph 2 — Subsequent / Current Works
Use transitions such as “Furthermore,” “Similarly,” “Building upon this,” “More recently,” “In a related study,” etc. Briefly explain what the researchers developed, proposed, introduced, or implemented, focusing only on aspects relevant to your research.

Paragraph 3 — Grouped Comparison of 4–5 Studies
Bring several related papers together into one coherent paragraph. Instead of describing each paper separately, synthesize them by explaining what approaches they used, what models/frameworks they developed, what datasets or techniques they employed, and what limitations or gaps remain.

Paragraph 4 — Research Gap + Our Solution
Conclude the Related Work by identifying the specific gap in the existing studies and then explain, in 1–2 sentences, how your proposed work addresses that gap. This should naturally lead into your methodology.

Writing Style

We should avoid repetitive phrases like:

“This paper proposed…”
“This paper proposed…”
“This paper proposed…”

Instead, we can vary the academic language:

Furthermore, researchers developed...

Similarly, the authors introduced...

Building upon these approaches, ...

In a related study, ...

More recently, ...

The authors designed...

They developed...

They employed...

Their framework incorporated...

The study demonstrated...
However, these approaches remain limited by...
Despite these advances,...
Nevertheless,...
These studies highlight the need for...
So the overall flow will be:
Importance of problem → Existing key work → Several related approaches → Limitations/research gap → Our proposed solution

This will make the section conference-appropriate, compact, connected, and analytical, rather than simply becoming a paper-by-paper summary.

========================================




# 📚 How to Write a Winning Research Paper — A Visual Guide

A six-part infographic series breaking down exactly how to structure every major section of a research paper — **Abstract, Introduction, Related Work, Literature Review, Methodology, and Conclusion** — with color-coded, paragraph-by-paragraph templates you can apply to your own writing.

Created and maintained by **Irfanul Kabir Hira**.

---

## 🗂️ Contents

| # | Section | Paper Type | Structure |
|---|---------|-----------|-----------|
| 1 | [Abstract](#1-abstract) | Journal / General | Importance → Research Gap → Objective → Methodology → Key Findings → Implications |
| 2 | [Introduction](#2-introduction) | Journal | Importance → Background → Background → Problem Statement → Research Gap → Evidence → Research Gap → Evidence → Local Context → Study Objectives → Paper Aim |
| 3 | [Related Work](#3-related-work-conference) | Conference | Importance + Key Work → Subsequent Works → Grouped Comparison → Research Gap + Solution (4-paragraph structure) |
| 4 | [Literature Review](#4-literature-review-journal) | Journal | Field Importance → Foundational Work → Thematic Sub-strands → Synthesis & Limitations → Research Gap → Study Aim |
| 5 | [Methodology](#5-methodology) | Journal / Conference | 11 modular, non-paragraph-limited building blocks (Overview → Data → Preprocessing → Model → Evaluation → Setup → XAI → Reproducibility) |
| 6 | [Conclusion](#6-conclusion) | Journal / General | Key Message → Key Research Findings → Broader Implications → Main Research Contribution → Future Directions → Call to Action |

---

## 1. Abstract
![How to write a winning abstract](assets/abstract_infographic.png)

A tight, six-block abstract structure: state why the problem matters, name the gap, state your objective, summarize your method, report your key result, and close with the practical implication.

## 2. Introduction
![How to write a winning introduction](assets/Introduction_Section.png)

A journal-style, ten-block introduction that layers importance, background, problem statement, and repeated gap–evidence pairs before narrowing into the study's objectives and aim — the same skeleton used in high-impact journal papers.

## 3. Related Work (Conference)
![How to write a winning related work section](assets/Related_work_Confirence.png)

A compact **4-paragraph** related-work structure built for space-constrained conference papers: importance + first key work, subsequent works, a grouped comparison of several studies, and the gap your paper fills.

## 4. Literature Review (Journal)
![How to write a winning literature review section](assets/Literature_review_Journal.png)

An expanded, **thematic** literature review for journal papers with more room to breathe — organizing prior work into strands (foundational, ML-based, deep learning, sensor fusion), followed by a dedicated synthesis-and-limitations paragraph before the gap and study aim.

## 5. Methodology
![How to write a winning methodology section](assets/methodology_infographic.png)

Unlike the other sections, Methodology isn't paragraph-limited — it's **11 modular subsections**, each with a clear job: pipeline overview, dataset description, data-splitting strategy (with explicit leakage prevention), feature composition, EDA, preprocessing, model architecture, evaluation metrics, hyperparameter setup, explainability (XAI), and a reproducibility statement.

## 6. Conclusion
![How to write a winning conclusion section](assets/conclusion_infographic.png)

A six-block conclusion template that restates the key message, synthesizes findings into numbered lessons, broadens the implications, states the core contribution, and closes with future directions and a call to action.

---

## 💡 How to Use This Guide

1. Pick the section you're writing.
2. Follow the labeled blocks top to bottom as a checklist, not a rigid script.
3. Swap in your own dataset, citations, and findings — the colors are there to help you see the *shape* of a strong section, not to be copied verbatim.
4. For Methodology specifically, remember: every technical claim should be backed by an **equation, a table, or a citation**.

## ✍️ Writing Style Notes

- Avoid repeating the same opener across paragraphs/subsections (e.g. "This paper proposed…", "In this study, we…").
- Vary transitions: *Furthermore, Building upon this, More recently, To begin with, Subsequently, This is achieved by…*
- Every research gap should lead directly into what your paper does about it — don't leave the gap hanging.

## 📄 License

These infographics and this guide are shared for educational purposes. Feel free to reference or adapt the structure for your own writing; please credit the author if reposting the visuals themselves.

## 👤 Author

**Irfanul Kabir Hira**
Feel free to connect for feedback, collaboration, or questions about the structures used here.
