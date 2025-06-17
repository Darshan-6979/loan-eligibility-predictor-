# 🏦 Loan Eligibility Predictor

This project builds a machine learning model to predict whether a loan application should be approved based on various applicant features. It uses Logistic Regression and provides performance evaluation using accuracy, confusion matrix, and classification report.

---

## 📊 Overview

- 📂 **Dataset**: Loan Prediction Dataset from [Kaggle](https://www.kaggle.com/datasets/ninzaami/loan-predication)
- 🧹 **Preprocessing**: Filled missing values, label encoding for categoricals
- 🧠 **Model**: Logistic Regression
- 📈 **Accuracy**: ~78.86% on test set

---

## 🧠 Features Used

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

---

## 🔍 Sample Output

```python
Accuracy: 78.86%

Confusion Matrix:
[[ 18  17]
 [  9  82]]

Classification Report:
              precision    recall  f1-score   support
           0       0.67      0.51      0.58        35
           1       0.83      0.90      0.86        91
