# Online Continual Learning: A Systematic Literature Review of Approaches, Challenges, and Benchmarks

## Overview
This repository contains the materials and data supporting our systematic literature review (SLR) on Online Continual Learning (OCL). The study provides a comprehensive analysis of approaches, challenges, benchmarks, and future directions in the field.
Access the full paper directly: [arXiv link](https://arxiv.org/abs/2501.04897)

---

## Abstract
Online Continual Learning (OCL) is a critical area in machine learning, focusing on enabling models to adapt to evolving data streams in real-time while addressing challenges such as catastrophic forgetting and the stability-plasticity trade-off. This study conducts the first comprehensive Systematic Literature Review (SLR) on OCL, analyzing 81 approaches, extracting over 1,000 features (specific tasks addressed by these approaches), and identifying more than 500 components (sub-models within approaches, including algorithms and tools). 

We also review 83 datasets spanning applications like image classification, object detection, and multimodal vision-language tasks. Our findings highlight key challenges, including reducing computational overhead, developing domain-agnostic solutions, and improving scalability in resource-constrained environments. Furthermore, we identify promising directions for future research, such as leveraging self-supervised learning for multimodal and sequential data, designing adaptive memory mechanisms that integrate sparse retrieval and generative replay, and creating efficient frameworks for real-world applications with noisy or evolving task boundaries. 

By providing a rigorous and structured synthesis of the current state of OCL, this review offers a valuable resource for advancing research and addressing its critical challenges and opportunities.

---

## Methodology

![Our Methodology](/Images/Methodology.jpg)  
*Figure 1: Our systematic methodology in this work.*

The methodology involves the following steps:

1. **Defining Research Objectives:** Establish the primary goals of the review.
2. **Developing Research Questions:** Formulate key questions guiding the review process.
3. **Designing a Conceptual Framework:** Structure the study process.
4. **Implementing a Search Strategy:** Use initial keywords and refine them to extract publications.
5. **Selecting Studies:** Apply selection criteria to identify relevant papers.
6. **Coding Selected Studies:** Classify entities such as approaches, features, and quality attributes.
7. **Quality Assessment:** Ensure only high-quality and relevant papers are included.
8. **Synthesizing Data:** Extract and synthesize data to address research questions.
9. **Reporting Findings:** Present insights and conclusions.

---

## Files in the Repository

Below is the directory structure of this repository:

```
.
├── README.md                 # Documentation for the repository
├── Research Questions.xlsx   # Research questions guiding the review
├── Conceptual Framework/
│   ├── Phase 1.xlsx          # Pool of publications
│   ├── Phase 2.xlsx          # Inclusion/Exclusion criteria
│   ├── Phase 3.xlsx          # Quality assessment
│   └── Phase 4.xlsx          # Data extraction
├── Extracted Entities/
│   ├── Components (1).xlsx   # Extracted components part 1
│   ├── Components (2).xlsx   # Extracted components part 2
│   ├── Features.xlsx         # Features identified in studies
│   ├── Quality_Attributes.xlsx
│   ├── Datasets.xlsx         # Datasets reviewed
│   └── Entities Definitions.xlsx
```

Access the full dataset via Google Sheets [here](https://docs.google.com/spreadsheets/d/1RfVwVnwkaRlRPQcCFm6iEh-JSG7Db_xMKZc9SxaBJP4/edit?usp=sharing).

---

## Citation
If you use or reference this work, please cite us using the following BibTeX entry:

```bibtex
@misc{bidaki2025onlinecontinuallearningsystematic,
      title={Online Continual Learning: A Systematic Literature Review of Approaches, Challenges, and Benchmarks}, 
      author={Seyed Amir Bidaki and Amir Mohammadkhah and Kiyan Rezaee and Faeze Hassani and Sadegh Eskandari and Maziar Salahi and Mohammad M. Ghassemi},
      year={2025},
      eprint={2501.04897},
      archivePrefix={arXiv},
      primaryClass={cs.LG},
      url={https://arxiv.org/abs/2501.04897}, 
}
```

## Acknowledgments
We appreciate all the researchers who contributed to the field of Online Continual Learning and inspired this systematic literature review. Special thanks to our collaborators for their support in making this work possible.
