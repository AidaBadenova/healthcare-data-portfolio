# AI Clinical Notes Structuring

## Project Overview
AI-assisted system for transforming unstructured 
physician notes into structured healthcare data 
including symptoms, ICD-10 codes, vital signs, 
urgency level, and clinical summary.

## Business Problem
Physicians spend significant time on documentation.
AI-assisted structuring helps to:
- Reduce administrative burden on physicians
- Improve data quality and standardization
- Enable downstream analytics on clinical data
- Support clinical decision-making

## Example

**Input (physician note):**
Patient 45 years old. Complains of cough 5 days,

temperature 38.5, weakness. Throat is red.

**Output (structured data):**
```json
{
  "symptoms": ["cough", "fever", "weakness"],
  "vital_signs": {"temperature": "38.5°C"},
  "icd10_code": "J06.9",
  "icd10_name": "Acute upper respiratory infection",
  "urgency": "routine",
  "summary": "Patient with URTI symptoms. Routine follow-up."
}
```

## Technologies
- Python, Rule-based NLP
- Regular Expressions for vital signs extraction
- ICD-10 medical terminology
- Prompt Engineering principles
- Healthcare clinical documentation standards

## Business Value
Inspired by emerging AI-assisted clinical 
documentation solutions. Supports healthcare 
organizations in improving efficiency 
of clinical workflows and data quality.

## Tech Stack
Python, Pandas, Matplotlib, Seaborn

## Author
Aida Badenova
MSc Health Management — University of Leeds
nFactorial School 2026
