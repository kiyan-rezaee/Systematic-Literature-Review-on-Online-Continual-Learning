
# Online Continual Learning: A Systematic Literature Review of Approaches, Challenges, and Benchmarks


## Abstract
Online Continual Learning (OCL) is a critical area in machine learning, focusing on enabling models to adapt to evolving data streams in real-time while addressing challenges such as catastrophic forgetting and the stability-plasticity trade-off. This study conducts the first comprehensive Systematic Literature Review (SLR) on OCL, analyzing 81 approaches, extracting over 1,000 features (specific tasks addressed by these approaches), and identifying more than 500 components (sub-models within approaches, including algorithms and tools). We also review 83 datasets spanning applications like image classification, object detection, and multimodal vision-language tasks. Our findings highlight key challenges, including reducing computational overhead, developing domain-agnostic solutions, and improving scalability in resource-constrained environments. Furthermore, we identify promising directions for future research, such as leveraging self-supervised learning for multimodal and sequential data, designing adaptive memory mechanisms that integrate sparse retrieval and generative replay, and creating efficient frameworks for real-world applications with noisy or evolving task boundaries. By providing a rigorous and structured synthesis of the current state of OCL, this review offers a valuable resource for advancing research and addressing its critical challenges and opportunities.

## Our SLR Methodology

![Our Methodology](/Images/Methodology.jpg)
*Figure 1: Our systematic methodology in this work. Our methodology starts with (1) defining research objectives, followed by developing research questions. (2) A conceptual framework is designed, and (3) selection criteria such as relevancy are constructed. (4) A search strategy is implemented using initial keywords and refined to extract more publications. (5) Studies are selected by applying the criteria to identify highly relevant papers. (6) The selected studies are coded to classify entities such as approaches, features, and quality attributes. (7) Quality assessment is performed to ensure high relevance and high-quality papers are included using defined questions. Finally, (8) extracted data are synthesized, and (9) findings are reported to address the research questions.*




## Files in the Repository
Below is the tree structure of the files in this repository:

```
.
├── README.md     # Documentation for the repository
├── Research Questions.xlsx 
├── Conceptual Framework/
│   ├── Phase 1.xlsx    # Pool of Publications
│   ├── Phase 2.xlsx    # Inclusion/Exclusion Creteria
|   ├── Phase 3.xlsx    # Quality Assessment
│   └── Phase 4.xlsx    # Data Extraction
│── Extracted Entities
│   ├── Components (1).xlsx
│   ├── Components (2).xlsx 
│   ├── Features.xlsx 
│   ├── Quality_Attributes.xlsx
│   ├── Datasets.xlsx          
│   └── Entities Definitions.xlsx

```
You can directly access the Google Sheets document [here](https://docs.google.com/spreadsheets/d/1RfVwVnwkaRlRPQcCFm6iEh-JSG7Db_xMKZc9SxaBJP4/edit?usp=sharing).

