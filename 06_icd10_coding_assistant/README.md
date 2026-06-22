# ICD-10 Coding Assistant

## Project Overview
AI-assisted tool for mapping clinical diagnoses 
and symptom descriptions to ICD-10 classification 
codes using intelligent keyword matching 
and similarity scoring.

## Business Problem
Accurate ICD-10 coding is essential for:
- Clinical documentation quality
- MSHI (OSMS) reimbursement accuracy
- Healthcare statistics and reporting
- Medical billing and insurance claims

Manual coding is time-consuming and error-prone.

## Examples

| Input | ICD-10 Code | Diagnosis |
|-------|------------|-----------|
| диабет 2 типа | E11 | Сахарный диабет 2 типа |
| высокое давление | I10 | Гипертоническая болезнь |
| боль в пояснице | M54.5 | Боль в нижней части спины |
| депрессия тоска | F32.9 | Депрессивный эпизод |

## Features
- Search by diagnosis name or symptoms
- Returns top-3 matching ICD-10 codes with scores
- Covers 8 major ICD-10 classes
- Urgency flagging for critical diagnoses
- Extensible to full ICD-10 database (10,000+ codes)

## ICD-10 Classes Covered
- Infectious (J, A)
- Cardiovascular (I)
- Endocrine (E)
- Gastrointestinal (K)
- Musculoskeletal (M)
- Mental Health (F)
- Urogenital (N)
- Neurological (G)

## Business Value
Supports healthcare professionals in improving 
coding accuracy and reducing administrative workload. 
Directly applicable to MSHI (OSMS) reporting 
in Kazakhstan's healthcare system.

## Tech Stack
Python, Pandas, difflib, Matplotlib, Seaborn

## Author
Aida Badenova
MSc Health Management — University of Leeds
nFactorial School 2026
