# Explainable Artificial Intelligence (XAI) for Machine Learning Models: A Comparative Study Using SHAP and LIME

## Overview

Artificial Intelligence (AI) models have achieved remarkable predictive performance across various application domains. However, many high-performing machine learning models operate as "black boxes," making it difficult to understand how predictions are generated. This lack of transparency limits trust, accountability, and adoption in critical domains such as healthcare, finance, and enterprise decision-making.

This project investigates the application of Explainable Artificial Intelligence (XAI) techniques to improve the interpretability of machine learning models. A Random Forest classifier was developed using the UCI Heart Disease dataset, and two widely adopted explainability methods—SHAP (SHapley Additive Explanations) and LIME (Local Interpretable Model-Agnostic Explanations)—were comparatively evaluated to explain model predictions.

The project demonstrates a reproducible workflow for building interpretable machine learning models while comparing global and local explanation techniques to improve transparency, trust, and responsible AI adoption.

---

# Research Objectives

The objectives of this research are to:

- Develop a machine learning model for heart disease prediction.
- Perform exploratory data analysis (EDA) on healthcare data.
- Evaluate model performance using standard classification metrics.
- Generate global feature importance using SHAP.
- Generate local prediction explanations using LIME.
- Compare SHAP and LIME for model interpretability.
- Demonstrate how Explainable AI improves transparency and trust in machine learning systems.

---

# Dataset

**Dataset:** UCI Heart Disease Dataset

**Domain:** Healthcare

**Source:** UCI Machine Learning Repository / Kaggle

**Problem Type:** Binary Classification

The dataset contains patient health information including:

- Age
- Sex
- Chest Pain Type
- Resting Blood Pressure
- Cholesterol
- Fasting Blood Sugar
- Resting ECG
- Maximum Heart Rate
- Exercise-Induced Angina
- ST Depression
- Number of Major Vessels
- Thalassemia
- Target (Heart Disease)

---

# Research Methodology

The project follows the workflow below:

1. Dataset loading and preprocessing.
2. Missing value analysis and data cleaning.
3. Exploratory Data Analysis (EDA).
4. Feature engineering and train-test split.
5. Random Forest model development.
6. Model evaluation.
7. SHAP explanation generation.
8. LIME explanation generation.
9. Comparative evaluation of explainability techniques.
10. Documentation of findings and conclusions.

---

# Explainability Techniques

## SHAP (SHapley Additive Explanations)

SHAP explains model predictions by assigning each feature a contribution value based on cooperative game theory. It provides both global and local explanations while maintaining theoretical consistency.

The project evaluates:

- SHAP Summary Plot
- SHAP Bar Plot
- Global Feature Importance
- Local Feature Contributions

---

## LIME (Local Interpretable Model-Agnostic Explanations)

LIME explains individual predictions by approximating the complex machine learning model with an interpretable local surrogate model.

The project evaluates:

- Individual Prediction Explanations
- Local Feature Contributions
- Decision Transparency
- Instance-Level Interpretability

---

# Evaluation Metrics

The machine learning model is evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC Score
- Confusion Matrix

The explainability techniques are compared using:

- Global Explainability
- Local Explainability
- Interpretability
- Computational Complexity
- Ease of Interpretation
- Practical Usefulness

---

# Key Findings

- Random Forest achieved strong predictive performance on the heart disease dataset.
- SHAP provided comprehensive global and local feature explanations.
- LIME effectively explained individual patient predictions.
- SHAP demonstrated greater consistency for overall model interpretation.
- LIME provided intuitive explanations for single prediction analysis.
- Combining SHAP and LIME improved model transparency and trustworthiness.

---

# Technologies Used

## Programming Language

- Python

## Machine Learning

- Scikit-learn

## Explainable AI

- SHAP
- LIME

## Libraries

- Pandas
- NumPy
- Matplotlib

## Development Environment

- Google Colab

---

# Repository Structure

02_Explainable_AI/
│
├── README.md
├── Explainable_AI.ipynb
├── Heart_Disease.csv
├── requirements.txt
│
├── figures/
│   ├── Dataset_Workflow.png
│   ├── Correlation_Heatmap.png
│   ├── SHAP_Summary_Plot.png
│   ├── SHAP_Bar_Plot.png
│   ├── LIME_Explanation.png
│   ├── Confusion_Matrix.png
│   └── Feature_Importance.png
│
├── reports/
│   ├── Explainable_AI_Research_Paper.pdf
│   └── Explainable_AI_Research_Paper.docx
│
└── data/
    └── Heart_Disease.csv

---

# Results

The comparative evaluation demonstrated that Explainable AI techniques significantly improve the transparency and interpretability of machine learning models.

Among the evaluated approaches:

- SHAP provided comprehensive global feature importance analysis.
- LIME generated intuitive explanations for individual predictions.
- Both methods enhanced model transparency and user trust.
- Explainable AI complements predictive performance by making machine learning models easier to understand and validate.

---

# Limitations

This study has several limitations:

- Evaluation was conducted using a single healthcare dataset.
- Only one machine learning algorithm (Random Forest) was evaluated.
- Explainability techniques were limited to SHAP and LIME.
- Human evaluation of explanations was beyond the scope of this research.

Future work may include deep learning models, additional XAI techniques, and multiple datasets.

---

# Future Work

Future research may explore:

- Deep Learning Explainability
- Explainable Transformer Models
- Counterfactual Explanations
- Integrated Gradients
- Attention Visualization
- Explainable Large Language Models
- Responsible AI Frameworks
- Multi-modal Explainable AI
- Human-Centered AI Evaluation

---

# Author

**Trisha Dasari**

Master of Arts in Information Technology Management

Webster University

Email: td8m28@gmail.com

---

# License

This project is intended for academic, educational, and research purposes.
