# Loan Default Prediction Project

---

## Contacts:
**Name**: Ibrahim Denis Fofanah  
**Email**: if57774n@pace.edu

**Status**: ✅ Complete

---

## Project Description:
This project aims to help lending institutions identify high-risk borrowers by predicting the likelihood of loan default using historical data. The project follows a full data science pipeline including data cleaning, EDA, feature engineering, model development, evaluation, and presentation.

We use **Logistic Regression** to classify borrowers as likely to default (1) or repay (0) based on their financial and personal attributes.

---

## 🗂 Navigating this Repo:

- `data/`
  - `raw/`: Contains the original dataset (not pushed to GitHub)
  - `processed/`: Cleaned and feature-engineered datasets

- `notebooks/`
  - `01_data_cleaning.ipynb`: Initial cleaning and outlier treatment
  - `02_eda_analysis.ipynb`: Exploratory Data Analysis (EDA)
  - `03_feature_engineering.ipynb`: Encoding and prep for modeling
  - `04_model_training.ipynb`: Logistic Regression training & evaluation

- `reports/`
  - `Loan_Default_First_Deliverable.pdf`
  - `Loan_Default_Final_Deliverable.pdf`

- `README.md`: This file  
- `requirements.txt`: Python packages required to run the project

---

## Related Project Materials

### Slide Decks:
- 2025-03-25: [First Delivery – Data & EDA](reports/Loan_Default_First_Deliverable.pdf)
- 2025-04-01: [Second Delivery – Modeling, Findings, and Recommendations](reports/Loan_Default_Final_Deliverable.pdf)
- 2025-04-22: [Final Delivery – Final Presentation](reports/Loan_Default_Final_Deliverable.pdf)

---

##  Technical Overview

- **Model**: Logistic Regression (scikit-learn)
- **Target Variable**: `Current_loan_status` → recoded to `loan_default` (0 = no default, 1 = default)
- **Features Used**:
  - Loan amount, interest rate, income, loan intent, credit history, employment duration, home ownership, and loan grade (encoded)
- **Evaluation**:
  - Accuracy: 79%
  - Precision (Default class): 68%
  - Recall (Default class): 4%
  - Confusion Matrix, F1 Score, Classification Report

---

## Key Business Insights

- **High income** and **long credit history** reduce default risk
- **Loan grades D & E**, **high loan amounts**, and **medical debt** are associated with higher default
- Business can use these findings to make smarter approval and pricing decisions

---

## Final Thoughts

This project was submitted as part of the Spring 2025 Practical Data Science course at Pace University. All code, reports, and outputs are maintained in this repository for future reference.

