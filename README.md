#  Loan Default Prediction – Final Project

## Project Overview
This project explores historical loan data to identify risk factors that lead to loan default. It uses a logistic regression model to predict whether a customer will default or repay a loan based on multiple financial and personal features.

---

## Business Problem
How can lenders better identify high-risk borrowers before issuing loans?
---

## Dataset Details
- **Source**: [Kaggle – Loan Default Dataset](https://www.kaggle.com/)
- **Sample Size**: 32,586 records
- **Each Row Represents**: A single customer loan application
- **Target Variable**: `Current_loan_status` (0 = No Default, 1 = Default)

---

## Data Preparation
- Removed outliers (loan amounts over $3.5M capped at the 95th percentile)
- Handled missing values via imputation
- Encoded categorical features (loan_grade, home_ownership, loan_intent)

---

## Exploratory Data Analysis (EDA)
Key visualizations included:
1. Loan Amount Distribution
2. Credit History vs Loan Default
3. Loan Grade vs Default Rate
4. Home Ownership vs Default Rate
5. Loan Intent vs Default Rate

Additional visuals provided in the appendix:
- Loan Amount Distribution (Before Cleaning)
- Employment Duration vs Loan Default
- Confusion Matrix & Classification Report

---

## Model Summary
- **Model Type**: Logistic Regression
- **Accuracy**: 79%
- **Precision (Default)**: 68%
- **Recall (Default)**: 4%

### Key Findings
- Income and loan grade were strong indicators of default risk
- The model struggled with recall due to class imbalance

### Recommendations
- Apply stricter screening to high-risk loan grades (D, E)
- Consider risk-based pricing for borrowers with low income or short employment duration

---

## Technical Details
- Features one-hot encoded
- Model trained using sklearn's LogisticRegression (L2 penalty)
- Evaluated with confusion matrix, classification report, F1 score

---

## Deliverables
- 📄 `Loan_Default_First_Delivery_FULL_FIXED.pptx`
- 📄 `Loan_Default_Delivery_2_Complete.pptx`

---

## GitHub Repo
All project files including data notebooks, visualizations, and presentation decks are available in this repository.



## Author
**Ibrahim Denis Fofanah**  
if57774n@pace.edu  
MS in Data Science, Seidenberg School of CSIS, Pace University
