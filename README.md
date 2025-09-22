# Loan Prediction using Machine Learning

This project predicts whether a loan will be approved or not based on applicant information using machine learning models.

---

## Dataset

The dataset contains the following columns:

- Loan_ID
- Gender
- Married
- Dependents
- Education
- Self_Employed
- ApplicantIncome
- CoapplicantIncome
- LoanAmount
- Loan_Amount_Term
- Credit_History
- Property_Area
- Loan_Status (target)

---

## Features & Preprocessing

- Missing values handled (mode for categorical, median for numerical)
- Replaced "3+" in Dependents with 3
- Feature engineering: TotalIncome, EMI, LoanToIncomeRatio
- Categorical encoding using One-Hot Encoding
- Scaling numeric features for Logistic Regression

---

## Models Used

- Logistic Regression  
- Decision Tree Classifier  
- Random Forest Classifier  
- XGBoost Classifier  

**Evaluation:** Accuracy, Confusion Matrix, Classification Report, ROC AUC

---
