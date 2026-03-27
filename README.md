# Hotel Chain A — Booking Cancellation Prediction

## Overview
This project was completed as part of the 5DATA004C Data Science Project Lifecycle module 
at the University of Westminster (2025/26) in collaboration with OCTAVE, the Data and 
Advanced Analytics division of the John Keells Group.

The objective is to analyse historical booking data from Hotel Chain A to identify 
cancellation patterns, quantify revenue loss, and build a predictive model to estimate 
cancellation risk at booking level.

## Contents
| File | Description |
|---|---|
| `Hotel-A-train.csv` | Training dataset (27,499 records) |
| `Hotel-A-validation.csv` | Validation dataset |
| `Hotel-A-test.csv` | Test dataset |
| `Hotel-A-data-dictionary.csv` | Feature descriptions |
| `Hotel A cancellation analysis.ipynb` | Main analysis notebook |

## Approach
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Outlier Treatment (IQR Winsorization)
- Label Encoding
- Revenue Loss Analysis
- Predictive Modelling: Logistic Regression, Decision Tree, Random Forest
- Model Evaluation: Accuracy, Precision, Recall, F1, ROC-AUC, Cross-Validation

## Requirements
All libraries are pre-installed in Google Colab. No additional installation used.
