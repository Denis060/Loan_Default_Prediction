# Loan_Default_Prediction - first delivery (Data & EDA)

## Project Overview
Lending institutions face significant risk when customers default on loans.  
This project aims to explore historical loan data to identify early risk signals and lay the foundation for a predictive model.

---

## Business Problem
How can lenders better identify risky borrowers before loan approval?

---

## Dataset Details
- **Source:** [Kaggle – Loan Default Dataset]([https://www.kaggle.com/](https://www.kaggle.com/datasets/prakashraushan/loan-dataset))
- **Sample Size:** 32,586 rows  
- **Each Row Represents:** A customer loan application  
- **Time Period:** Not provided – assumed to be recent data  
- **Target Variable:** `Current_loan_status` (1 = Default, 0 = No Default)

---

## Data Preparation
- Removed outliers (loan requests over $3.5M capped at 95th percentile)
- Handled missing values using logical assumptions or median imputation
- Cleaned currency symbols and mapped categorical values

---

## Exploratory Data Analysis
Five key visualizations were created to support risk analysis:

1. **Loan Amount Distribution**  
2. **Credit History vs Default**  
3. **Loan Grade vs Default Rate**  
4. *(Coming soon)* Income vs Default  
5. *(Coming soon)* Loan Intent vs Default

---

## Key Takeaways
- Most loans fall between $5K and $15K  
- Lower loan grades (C, D, E) have much higher default rates  
- Short credit history has limited but noticeable influence

---

## First Deliverable Presentation
📂 `/reports/Loan_Default_First_Deliverable`  
This deck summarizes the data and EDA insights for a non-technical audience.

---

## Next Steps
- Feature engineering (e.g., income brackets, encoded categories)
- Build predictive model (e.g., Logistic Regression)
- Evaluate model performance and present business recommendations

---

## Author
**Ibrahim Denis Fofanah**  
📧 ifofanah@pace.edu  
MS in Data Science, Seidenberg School of CSIS, Pace University
