# Evaluating Prompting Strategies for AI-Assisted Enterprise Decision Support Using Large Language Models

## Overview

This project investigates the effectiveness of different prompting strategies for Large Language Models (LLMs) in enterprise decision support. Using a real-world retail sales dataset, the study evaluates how prompt design influences the quality, reliability, and actionability of AI-generated business recommendations.

Google Gemini 3.6 Flash was used to generate recommendations under four prompting strategies: Zero-shot, Structured, Role-based, and Few-shot prompting. The responses were systematically evaluated based on factual accuracy, evidence-based reasoning, hallucination resistance, executive readability, and decision-making usefulness.

This project demonstrates a reproducible workflow for integrating Large Language Models into business analytics while emphasizing transparent and trustworthy AI-assisted decision support.

---

# Research Objectives

The objectives of this project are to:

- Analyze a real-world retail sales dataset using Python.
- Generate business insights through exploratory data analysis.
- Evaluate the impact of different prompting strategies on LLM-generated recommendations.
- Compare response quality across Zero-shot, Structured, Role-based, and Few-shot prompting.
- Identify prompting techniques that produce reliable, evidence-based business recommendations.

---

# Dataset

**Dataset:** Sample Superstore

**Domain:** Retail Sales Analytics

**Source:** Tableau Sample Superstore Dataset

**Records:** 9,994

**Features:** 21

The dataset contains transactional information including:

- Sales
- Profit
- Product Categories
- Customer Segments
- Geographic Regions
- States
- Order Information
- Shipping Information

---

# Research Methodology

The project followed the workflow below:

1. Data loading and preprocessing using Python.
2. Exploratory Data Analysis (EDA).
3. Business performance analysis.
4. Sales visualization.
5. Generation of business summaries.
6. Evaluation of four prompting strategies using Google Gemini 3.6 Flash.
7. Comparative analysis of AI-generated recommendations.
8. Documentation of findings and conclusions.

---

# Prompting Strategies Evaluated

## Experiment 1 – Zero-Shot Prompting

The model received only the business summary without additional examples or formatting guidance.

---

## Experiment 2 – Structured Prompting

The model received a structured analytical framework with explicit instructions for evidence-based reasoning and uncertainty handling.

---

## Experiment 3 – Role-Based Prompting

The model was assigned the role of a Chief Strategy Officer (CSO) responsible for preparing executive recommendations.

---

## Experiment 4 – Few-Shot Prompting

The model received an example business analysis before evaluating the actual business summary.

---

# Evaluation Criteria

Each prompting strategy was evaluated using the following criteria:

- Business Understanding
- Numerical Accuracy
- Evidence-Based Reasoning
- Hallucination Resistance
- Handling of Missing Information
- Executive Readability
- Actionability of Recommendations

---

# Key Findings

- Structured prompting consistently generated the most evidence-based recommendations.
- Few-shot prompting produced the most consistent analytical responses.
- Role-based prompting generated executive-oriented recommendations with strong strategic focus.
- Zero-shot prompting produced useful recommendations but occasionally inferred conclusions beyond the available evidence.
- Prompt engineering significantly influenced the quality and reliability of AI-generated business recommendations.

---

# Technologies Used

## Programming Language

- Python

## Libraries

- Pandas
- NumPy
- Matplotlib
- OpenPyXL

## Large Language Model

- Google Gemini 3.6 Flash

## Development Environment

- Google Colab

---

# Repository Structure

```
01_AI_Assisted_Decision_Support/

│── README.md

│── AI_Assisted_Decision_Support_System.ipynb

│── Sample - Superstore.xls

│── requirements.txt

│── figures/

│── prompts/

│── reports/
```

---

# Results

The comparative evaluation demonstrated that prompt engineering plays a significant role in improving the quality of AI-assisted enterprise decision support.

Among the evaluated prompting strategies:

- Structured Prompting achieved the highest factual consistency.
- Few-Shot Prompting produced the most reliable recommendations.
- Role-Based Prompting generated executive-quality strategic insights.
- Zero-Shot Prompting provided comprehensive but less constrained responses.

---

# Limitations

This study has several limitations:

- Only one dataset was evaluated.
- Only one Large Language Model (Google Gemini 3.6 Flash) was used.
- Business recommendations were generated from summarized data rather than raw transactional records.
- Human evaluation was used for comparative assessment.

Future work may include evaluation across multiple datasets, additional LLMs, and automated evaluation metrics.

---

# Future Work

Future research may explore:

- Comparative evaluation of multiple Large Language Models.
- Chain-of-Thought prompting.
- Retrieval-Augmented Generation (RAG).
- AI agents for enterprise decision support.
- Automated benchmarking frameworks for prompt evaluation.

---

# Author

**Trisha Dasari**

Master of Arts in Information Technology Management

Webster University

Email: 3shadas@gmail.com

---

# License

This project is intended for academic, educational, and research purposes.
