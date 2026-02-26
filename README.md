# Replication Package: GenAI and Multi-Agent Systems for Software Testing (Rapid Review)

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.18791805.svg)](https://doi.org/10.5281/zenodo.18791805)


This repository contains the replication package and supplementary materials for the paper: 
**"What solutions based on Generative Artificial Intelligence are available to support testing-related activities in Software Engineering: A Rapid Literature Review"**.

## Overview
This study presents a Rapid Literature Review (RLR) mapping the state-of-the-art in **Multi-Agent Systems (MAS)** and **Generative AI (GenAI)** applied to software testing. We analyzed 55 primary studies retrieved from Scopus (published up to late 2025) to identify architectural patterns, supported testing activities, and common challenges like the Oracle Problem and "Fail-to-Pass" scenarios.

## Repository Structure

The data is organized to reflect the PRISMA flow and the theoretical alignment with Software Engineering standards:

- `protocol/`:
    - `search_strategy.txt`: The exact search strings and logic applied in Scopus.
- `data/`: 
    - **Core Extraction & Synthesis:**
        - `extraction_table.csv`: Primary data extraction sheet (Final synthesis).
        - `extraction_swebok_mapping.csv`: **Advanced analysis mapping GenAI/MAS solutions to the SWEBOK (Software Engineering Body of Knowledge) knowledge areas and testing levels.**
        - `extraction_pt_br.csv`: Data extraction version in Portuguese.
    - **Selection Process (Rayyan):**
        - `rayyan_screening_all.csv`: Initial screening of titles and abstracts (exported from Rayyan).
        - `rayyan_fulltext_review.csv`: List of papers assessed during the full-text eligibility phase.
        - `included_studies.csv`: Final list of the 55 included primary studies.
    - **Analysis & Visualization:**
        - `review_metrics.csv`: Statistical data regarding the review results and bibliometrics.
- `LICENSE`: CC0 1.0 Universal.
- `README.md`: This file.

## Search Strategy
The search was conducted in the **Scopus** database using the following logic (PICOC):

* **Population:** Software Testing activities.
* **Intervention:** Generative AI and Multi-Agent Systems.
* **Context:** Software Engineering.

>`(Software Test*'' OR Based Test'' OR Dynamic Test*'' OR Test* Oracle*'' OR Test* Design'' OR Test* Execution'' OR Test* Report*'' OR Test* Plan*'' OR Test* Autom*'' OR Autom* Test*'' OR Test Case*'' OR Bug Detection'' OR Fault Detection'' OR Error Detection'' OR Failure Detection'') AND (multi-agent system'' OR multiagent system'' OR multi agent system'' OR Agent*'' OR MAS OR EMAS) AND (LLM OR Large Language Model'' OR ChatGPT'' OR Gemini'' OR GenAI'' OR Generative'' OR Deepseek'' OR Copilot'' OR ``Mistral'')`

## Summary of Findings
* **Dominant Models:** GPT-4 and GPT-3.5 (OpenAI).
* **Core Activities:** Test Generation, GUI Testing, and Test Orchestration/CI.
* **Emerging Patterns:** Transition from single-prompt LLM assistance to autonomous Multi-Agent orchestration.

## How to Cite
If you use this dataset or the findings from our review, please cite our work:

```bibtex
@article{moliterno2026genai,
  title={What solutions based on Generative Artificial Intelligence are available to support testing-related activities in Software Engineering: A Rapid Literature Review},
  author={Moliterno, Nicolas Guilhermo Silva},
  journal={SBC Computing Reviews},
  year={2026},
  doi={https://doi.org/10.5281/zenodo.18791805}
}
```

## License

This project is dedicated to the public domain under the **Creative Commons CC0 1.0 Universal** license. 

You can copy, modify, distribute and perform the work, even for commercial purposes, all without asking permission. In the spirit of academic collaboration, we kindly request that you cite the original paper if you use these datasets in your research.

See the [LICENSE](LICENSE) file for the full legal text.