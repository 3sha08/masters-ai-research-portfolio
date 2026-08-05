# **Comparative Evaluation of Large Language Models for Business Decision Support**

## Overview

This project presents a comparative evaluation of three leading Large Language Models (LLMs) **ChatGPT (GPT-5.5)**, **Google Gemini 3.6 Flash**, and **Claude Sonnet** for enterprise business decision support. Using the Tableau Sample Superstore dataset, the study investigates how different LLMs interpret identical business information and generate executive-level recommendations.

A standardized business summary generated through Python-based exploratory data analysis (EDA) was provided to each model using the same prompt. The resulting responses were evaluated using qualitative and quantitative criteria, including business understanding, numerical accuracy, evidence-based reasoning, hallucination resistance, executive readability, and recommendation quality.

---

## Objectives

- Perform business analytics using the Tableau Sample Superstore dataset.
- Generate a standardized business summary through Python.
- Evaluate ChatGPT, Gemini, and Claude using an identical prompt.
- Compare the quality of AI-generated executive business recommendations.
- Assess factual accuracy, reasoning quality, and decision support capabilities.
- Identify strengths and limitations of each Large Language Model.

---

## Dataset

- **Dataset:** Tableau Sample Superstore
- **Records:** 9,994
- **Features:** 21

---

## Technologies Used

- Python 3.x
- Google Colab
- Pandas
- NumPy
- Matplotlib
- OpenPyXL
- ChatGPT (GPT-5.5)
- Google Gemini 3.6 Flash
- Claude Sonnet

---

## Project Workflow

```
Tableau Sample Superstore Dataset
                │
                ▼
Python Data Analysis
                │
                ▼
Business Summary Generation
                │
                ▼
Standardized Prompt
                │
      ┌─────────┼─────────┐
      ▼         ▼         ▼
 ChatGPT     Gemini     Claude
      │         │         │
      └─────────┼─────────┘
                ▼
Business Recommendations
                │
                ▼
Comparative Evaluation
                │
                ▼
Research Findings
```

---

## Evaluation Criteria

- Business Understanding
- Numerical Accuracy
- Evidence-Based Reasoning
- Hallucination Resistance
- Handling Missing Information
- Executive Readability
- Actionable Recommendations
- Quantitative Analysis

---

## Project Structure

```
03_LLM_Comparative_Evaluation/
│
├── README.md
├── requirements.txt
├── LLM_Comparative_Evaluation.ipynb
├── Sample - Superstore.xls
└── prompts/
    ├── ChatGPT_Prompt.txt
    ├── Gemini_Prompt.txt
    └── Claude_Prompt.txt
```

---

## Key Findings

- All three LLMs demonstrated excellent business understanding and evidence-based reasoning.
- ChatGPT produced concise and highly readable executive reports.
- Gemini generated detailed quantitative business insights through derived calculations.
- Claude delivered the most comprehensive executive analysis with extensive numerical reasoning and structured recommendations.
- Standardized prompts enable objective comparison of LLM capabilities for business decision support.

---

## Future Work

- Compare additional Large Language Models.
- Evaluate Retrieval-Augmented Generation (RAG).
- Investigate AI agent-based business decision support.
- Expand experiments to healthcare, finance, manufacturing, and supply chain datasets.
- Develop automated evaluation metrics for LLM comparison.

---

## Author

**Trisha Dasari**
Gmail: 3shadas@gmail.com 
