# Diabetes Risk Prediction using Machine Learning

## Project Overview

This project focuses on predicting diabetes risk using demographic and clinical patient data.

The objective was to develop a machine learning classification model capable of identifying patients at elevated risk of diabetes while maintaining a balanced trade-off between precision and recall.

## Dataset

73,718 patient records including:

* Age
* Gender
* BMI
* Hypertension
* Heart Disease
* Smoking History
* HbA1c Level
* Blood Glucose Level

Target variable:

* Diabetes (0 = No Diabetes, 1 = Diabetes)

Class distribution:

* No Diabetes: 91%
* Diabetes: 9%

## Methodology

* Exploratory Data Analysis (EDA)
* Missing Value Assessment
* Encoding with get_dummies()
* Train/Test Split (80/20, stratified)
* Class Imbalance Handling using class_weight='balanced'
* Random Forest Classification
* Hyperparameter Optimization using Optuna
* Threshold Tuning for F1-score Optimization
* Feature Importance Analysis

## Results

| Metric            | Score |
| ----------------- | ----- |
| F1-score          | 0.815 |
| Precision         | 0.93  |
| Recall            | 0.72  |
| Accuracy          | 0.97  |
| ROC-AUC           | 0.98  |
| Optimal Threshold | 0.75  |

## Key Findings

* HbA1c Level and Blood Glucose Level were the strongest predictors of diabetes risk.
* Threshold optimization significantly improved the balance between precision and recall.
* F1-score was selected as the primary metric because both missed diabetes cases and excessive false positive predictions may have negative healthcare implications.

## Business Value

Early identification of patients at risk of diabetes can support preventive interventions, reduce long-term complications, and improve healthcare resource allocation.

In the context of Kazakhstan's Mandatory Social Health Insurance (MSHI / OSMS) system, predictive analytics can help healthcare organizations improve population health management and preventive care programs.

## Tech Stack

Python, Pandas, NumPy, Scikit-learn, Optuna, Matplotlib, Seaborn, Random Forest

## Author

Aida Badenova

MSc Health Management, Planning and Policy (University of Leeds)

nFactorial School 2026

LinkedIn:
linkedin.com/in/aida-badenova-35895a3b4

