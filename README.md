# Loan Default Prediction — CS5998 Capstone Project

**Student:** L. M. Samararathna  
**Student ID:** 258737D  

## Project Overview
This project develops and compares machine learning models to predict 
loan default using the Lending Club dataset (2007–2018).

## Problem Type
Binary Classification — Default vs Fully Paid

## Dataset
- Source: Lending Club Loan Data (Kaggle)
- 2.26 million records · 151 columns
- Sampled 200,000 records for analysis

## Models Compared
| Model | ROC-AUC | Accuracy | Training Time |
|---|---|---|---|
| Logistic Regression | 0.7052 | 66% | 0.7s |
| Decision Tree | 0.6831 | 62% | 2.6s |
| Random Forest | 0.7069 | 65% | 20.8s |
| **XGBoost** | **0.7146** | **65%** | **4.1s** |

## Key Findings
- XGBoost achieved the best ROC-AUC score of 0.7146
- Loan grade is the most important predictor of default
- Higher interest rates are strongly associated with default

## Project Structure
- `Loan_Default_Prediction.ipynb` — Main notebook
- `Architecture_Diagram.png` — System architecture diagram

## Status
✅ Milestone 2 Complete
