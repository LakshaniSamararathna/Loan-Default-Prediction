# Loan Default Prediction - CS5998 Capstone Project

**Student Name:** L. M. Samararathna  
**Student ID:** 258737D  

Master of Data Science & Artificial Intelligence   
University of Moratuwa  

---

## Project Overview
This project develops and compares machine learning models to predict 
loan default using the Lending Club dataset (2007–2018). An end-to-end 
binary classification pipeline was built covering data preprocessing, 
exploratory data analysis, model training, hyperparameter tuning, and 
comparative evaluation.

---

## Dataset
- **Source:** Lending Club Loan Data — Kaggle
- **Link:** https://www.kaggle.com/datasets/wordsforthewise/lending-club
- **File:** accepted_2007_to_2018Q4.csv
- **Records:** 200,000 sampled from 2.26M

---

## Models Compared
| Model | ROC-AUC | Accuracy | Training Time |
|---|---|---|---|
| Logistic Regression (Baseline) | 0.7052 | 66% | 0.7s |
| Decision Tree | 0.6831 | 62% | 2.6s |
| Random Forest | 0.7069 | 65% | 20.8s |
| XGBoost (Default) | 0.7146 | 65% | 4.1s |
| **XGBoost (Tuned)** | **0.7158** | **65%** | **~8s** |

---

## Key Findings
- XGBoost (Tuned) achieved the best ROC-AUC of 0.7158
- Loan grade is the most important predictor of default
- Cost-sensitive learning effectively handles class imbalance
- Hyperparameter tuning via RandomizedSearchCV improved performance marginally

---

## Repository Structure
| File | Description |
|---|---|
| `Loan_Default_Prediction.ipynb` | Main Notebook — Full Pipeline |
| `Architecture_Diagram.png` | System Architecture Diagram |
| `README.md` | Project Overview |

---

## Status
✅ Milestone 1 — Project Definition — Complete  
✅ Milestone 2 — Technical Checkpoint — Complete  
✅ Milestone 3 — Final Submission — Complete
