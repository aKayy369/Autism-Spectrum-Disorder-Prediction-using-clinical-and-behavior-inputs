# Autism Spectrum Disorder Detection using Machine Learning

## Overview
This project focuses on Autism Spectrum Disorder (ASD) detection using behavioral screening datasets and phenotypic clinical datasets. The goal is to preprocess the data, perform exploratory analysis, handle missing values, and prepare the dataset for machine learning-based ASD prediction.

The project combines:
- Behavioral questionnaire data
- Clinical phenotypic data (ABIDE II dataset)
- Data preprocessing and cleaning
- Feature engineering
- Statistical analysis
- Machine Learning preparation

---

## Datasets Used

### 1. Behavioral Dataset
Contains:
- Autism Quotient responses (A1–A10)
- Social responsiveness metrics
- Age
- Anxiety disorder indicators
- Genetic disorders
- Family ASD history
- Ethnicity and demographic information

Dataset Shape:
- 1985 rows
- 28 columns

### 2. ABIDE II Phenotypic Dataset
Contains:
- Clinical ASD diagnostic information
- IQ metrics
- Behavioral scales
- ADOS/ADI-R scores
- MRI-related metadata
- Psychological assessments

Dataset Shape:
- 1114 rows
- 348 columns

---

## Features Implemented

- Data Cleaning
- Missing Value Analysis
- Age Filtering
- Column Standardization
- Exploratory Data Analysis
- Dataset Merging Preparation
- Statistical Summaries
- Feature Inspection

---

## Technologies Used

- Python
- Pandas
- NumPy
- Jupyter Notebook

---

## Data Preprocessing Steps

### Behavioral Dataset
- Loaded CSV data
- Checked missing values
- Performed feature inspection
- Analyzed age distributions

### ABIDE II Dataset
- Loaded dataset with latin1 encoding
- Standardized column names
- Removed extra whitespace from columns
- Filtered age range between 5 and 18 years
- Renamed AGE_AT_SCAN to Age_Years
- Analyzed missing data percentages

---

## Project Structure

```bash
project/
│
├── notebooks/
│   └── autism_analysis.ipynb
│
├── datasets/
│   ├── data_csv.csv
│   └── ABIDEII_Composite_Phenotypic.csv
│
├── requirements.txt
├── README.md
└── app.py
