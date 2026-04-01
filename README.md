# Artificial Intelligence in Physics Education: Opportunities for Students with Disabilities

**Author:** Taylor Reeves  
**Institution:** University of Toronto  
**Contact:** taylor.reeves@mail.utoronto.ca  
**Course:** PHYD72

---

## Overview

This repository contains all source files for the academic paper *Artificial Intelligence in Physics Education: Opportunities for Students with Disabilities*, along with an accompanying instructor resource guide. The paper examines how structural, cognitive, and social barriers affect students with disabilities in undergraduate physics programs, and evaluates how recent advances in artificial intelligence can help address these inequities.

The work draws on literature across physics education research, special education, and educational technology. It surveys current AI applications for both instructors and students, analyzes how tools such as adaptive tutoring systems, multimodal visualizations, and large language models can reduce cognitive load and support diverse learners, and identifies key concerns including overreliance, algorithmic bias, and the disproportionate impact of automated plagiarism detection on students who use assistive technologies. The paper concludes with five evidence-based recommendations for the responsible and inclusive integration of AI into undergraduate physics education.

---

## Repository Contents

| File | Description |
|---|---|
| `PHYD72_Reeves.tex` | Main LaTeX source file for the paper, typeset using the `aastex701` document class |
| `PHYD72_Reeves.bib` | BibTeX bibliography file containing all references cited in the paper |
| `Testing.pdf` | Instructor resource guide — *AI & Accessibility in Undergraduate Physics* — included as Appendix A of the compiled paper |
| `README.md` | This file |

---

## Compilation Instructions

The paper is typeset using the [AASTeX v7.0.1](https://journals.aas.org/aastex-package-for-manuscript-preparation/) document class and uses `biblatex` with `biber` for reference management. To compile from source you will need a full TeX Live or MiKTeX installation.

**Required packages** (all standard in TeX Live / MiKTeX):
- `aastex701` document class
- `biblatex` with `biber` backend
- `booktabs`
- `pifont`
- `graphicx` (loaded automatically by aastex)

**Compile sequence:**

```bash
pdflatex PHYD72_Reeves.tex
biber PHYD72_Reeves
pdflatex PHYD72_Reeves.tex
pdflatex PHYD72_Reeves.tex
```

Two additional `pdflatex` passes after `biber` are required to resolve all cross-references and citation numbers correctly.

**Note on the appendix:** The instructor resource guide (`Testing.pdf`) is included as Appendix A using `\includegraphics[page=N]{Testing.pdf}`. This file must be present in the same directory as the `.tex` file at compile time. No separate image conversion is required — `pdflatex` reads the PDF pages directly.

---

## Paper Structure

| Section | Title |
|---|---|
| 1 | Introduction |
| 2 | How Do Disabilities Manifest in Physics Education |
| 3 | How AI is Being Utilized in Physics Education |
| 4 | How AI Can Support Students with Disabilities in Physics Education |
| 5 | Concerns |
| 6 | Discussion and Summary |
| 7 | Recommendations |
| Appendix A | Instructor Resource Guide |

---

## ⚠️ Copyright and Intellectual Property Notice

**All contents of this repository — including but not limited to the paper manuscript, bibliography, instructor resource guide, and all associated source files — are the original intellectual property of Taylor Reeves and are protected under applicable Canadian and international copyright law.**

This work is **not licensed for public use, reproduction, distribution, modification, or redistribution** in any form, whether in whole or in part, by any individual or entity other than the author.

### Prohibited without express written consent:

- Copying, reproducing, or duplicating any portion of the manuscript or resource guide
- Distributing, sharing, forwarding, or publishing any file in this repository
- Adapting, modifying, translating, or creating derivative works based on this material
- Using any portion of this work in academic submissions, publications, or presentations
- Citing unpublished versions of this work without the author's explicit written permission

### Permitted uses:

- Viewing the repository contents for the purposes of academic supervision and evaluation by the University of Toronto and authorized course instructors
- Personal reference by the author

### Academic integrity:

This is an original academic work submitted in partial fulfillment of course requirements at the University of Toronto. Any unauthorized use of this material in another academic submission constitutes academic misconduct under the University of Toronto's [Code of Behaviour on Academic Matters](https://governingcouncil.utoronto.ca/secretariat/policies/code-behaviour-academic-matters-july-1-2019) and may be subject to disciplinary action.

### No implied license:

The presence of this repository on GitHub does not constitute a grant of any license, right, or permission to use, reproduce, or distribute this work. GitHub's Terms of Service allow the platform to host the content; they do not override the author's copyright or grant any rights to third parties.

---

## Contact

For permissions, inquiries, or to request access, please contact the author directly:

**Taylor Reeves**  
University of Toronto  
taylor.reeves@mail.utoronto.ca

All permission requests must be made in writing and will be considered on a case-by-case basis. Verbal agreements do not constitute permission.

---

*© Taylor Reeves, University of Toronto. All rights reserved.*
