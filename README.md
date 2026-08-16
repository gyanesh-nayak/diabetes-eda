# Diabetes Dataset — Exploratory Data Analysis

Exploratory data analysis of a diabetes patient dataset using Python, Pandas, Matplotlib, and Seaborn.

## Overview

This project performs exploratory data analysis (EDA) on the Early Stage Diabetes Risk Prediction dataset from the UCI Machine Learning Repository.

The goal was to investigate patient characteristics and symptom patterns and identify features that show stronger associations with Positive and Negative classifications.

## Tools

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Analysis

The analysis includes:

- Dataset inspection and data-quality checks
- Missing-value and duplicate analysis
- Age and gender distributions
- Positive/Negative class distribution
- Symptom prevalence
- Symptom proportions by classification
- Age and gender relationships with classification
- Feature/class correlation analysis
- Data visualizations using Matplotlib and Seaborn

## Key Findings

- The dataset contains 520 patients, with 320 Positive and 200 Negative classifications.
- Polyuria and polydipsia showed the strongest associations with the Positive classification.
- Sudden weight loss and partial paresis also showed relatively strong positive associations.
- Weakness had the highest overall symptom prevalence but was less strongly associated with classification than polyuria and polydipsia.
- Itching had very little association with classification despite being relatively common.
- Alopecia showed a negative association with Positive classification.
- Age showed only a weak association with classification, with substantial overlap between the two groups.

## Limitations

This analysis identifies associations rather than causal relationships. The dataset is moderately imbalanced toward the Positive classification, and the analysis does not evaluate predictive performance on unseen patients.

A future project could use these features to build and evaluate classification models.

## Dataset

This project uses the Early Stage Diabetes Risk Prediction dataset from the UCI Machine Learning Repository.

- Dataset: Early Stage Diabetes Risk Prediction
- Source: UCI Machine Learning Repository
- DOI: https://doi.org/10.24432/C5VG8H
- License: CC BY 4.0

The dataset contains 520 patient records and 16 features related to early-stage diabetes symptoms. The data was collected using questionnaires from patients at Sylhet Diabetes Hospital in Sylhet, Bangladesh.

The dataset is used here for educational and exploratory data-analysis purposes.

## Project Structure
```text
diabetes-eda/
├── diabetes_eda.ipynb
├── diabetes_data_upload.csv
└── README.md
