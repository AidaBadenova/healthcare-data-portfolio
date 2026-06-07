Diabetes Risk Prediction using Machine Learning
Project Overview

This project focuses on predicting diabetes risk using demographic and clinical patient data.

The goal was to build a machine learning classification model capable of identifying patients at increased risk of diabetes and supporting early risk detection through healthcare analytics.

Dataset Features
Age
Gender
BMI
Hypertension
Heart disease
Smoking history
HbA1c level
Blood glucose level
Machine Learning Pipeline

The project includes:

Exploratory Data Analysis (EDA)
Missing value handling
OneHotEncoding
StandardScaler
Train/Test Split with stratification
Pipeline-based preprocessing
Random Forest Classification
Threshold tuning
ROC-AUC evaluation
Feature importance analysis
Key Results
ROC-AUC: 0.98
Recall for diabetes class: 0.98
High recall optimization for healthcare-oriented classification
Feature importance analysis identified HbA1c level and blood glucose level as the strongest predictors associated with diabetes risk
Why Recall Matters in Healthcare

In healthcare-related classification tasks, recall is especially important because missing a high-risk patient may lead to delayed diagnosis or treatment.

For this reason, the model threshold was adjusted to improve diabetes detection performance.

Tools

Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn

Files
diabetes_prediction.ipynb
submission.csv
Author

Aida Badenova
