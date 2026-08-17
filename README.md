# Diabetes Dataset Exploratory Data Analysis

An exploratory dive into early-stage diabetes risk data, looking for the symptoms and patient traits that actually separate a Positive diagnosis from a Negative one, using Python, Pandas, Matplotlib, and Seaborn.

## Overview

Diabetes is often caught late, after symptoms have piled up quietly for months. This project digs into the **Early Stage Diabetes Risk Prediction** dataset from the UCI Machine Learning Repository to ask a simple question: which symptoms and characteristics actually matter?

Rather than jumping straight to a predictive model, this is a ground-up exploration: inspecting the data, checking its quality, and letting the patterns in symptom prevalence and patient demographics tell their own story before drawing any conclusions.

## Tools

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## What's in the Analysis

- Dataset inspection and data-quality checks
- Missing-value and duplicate analysis
- Age and gender distributions
- Positive/Negative class balance
- Symptom prevalence across the full patient group
- Symptom proportions broken down by classification
- How age and gender relate to classification
- Feature/class correlation analysis
- Visualizations throughout, built with Matplotlib and Seaborn

## Key Findings

- The dataset covers 520 patients: 320 Positive, 200 Negative.
- **Polyuria** (excessive urination) and **polydipsia** (excessive thirst) stood out as the two symptoms most strongly associated with a Positive classification, consistent with their clinical description as early warning signs.
- **Sudden weight loss** and **partial paresis** also showed fairly strong positive associations.
- **Weakness** was the most commonly reported symptom overall, but it proved to be a weaker signal than polyuria or polydipsia, showing that prevalence alone doesn't guarantee predictive value.
- **Itching** was surprisingly uninformative: common in the dataset, but barely associated with classification either way.
- **Alopecia** actually leaned the other direction, showing a negative association with Positive classification.
- **Age** had only a weak relationship with classification, with a lot of overlap between the two groups, so it's not a strong differentiator on its own.

## Limitations

Please note that this is an associations-based analysis, not a causal one. The dataset also skews somewhat toward Positive cases, which can shape how strong certain patterns appear. And since this project stops at exploration, it doesn't test how well any of these features would actually hold up predicting outcomes for new, unseen patients.

A natural next step would be to take these findings and build out classification models to see how well they generalize.

## Dataset

This project uses the **Early Stage Diabetes Risk Prediction** dataset from the UCI Machine Learning Repository.

- **Dataset:** Early Stage Diabetes Risk Prediction
- **Source:** UCI Machine Learning Repository
- **DOI:** https://doi.org/10.24432/C5VG8H
- **License:** CC BY 4.0

It contains 520 patient records across 16 features tied to early-stage diabetes symptoms, gathered via patient questionnaires at Sylhet Diabetes Hospital in Sylhet, Bangladesh. Used here strictly for educational and exploratory purposes.

## Project Structure

```text
diabetes-eda/
├── diabetes_eda.ipynb
├── diabetes_data_upload.csv
└── README.md
```
