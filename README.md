# SmartCredit Loan System

**Machine Learning-Powered Intelligent Loan Approval System**

---

## Project Overview

SecureTrust Bank, a mid-sized financial company in India, processes hundreds of personal and home loan applications daily. Traditional manual verification is time-consuming, inconsistent, and prone to human bias.

SmartCredit Loan System is an end-to-end Machine Learning solution that predicts whether a loan should be Approved or Rejected based on the applicant’s financial, credit, and personal information. The system aims to reduce risk, speed up processing, and minimize bias in lending decisions.

---

## Objectives

- Build a robust ML model to automate loan approval prediction
- Identify the key factors influencing loan approval
- Reduce financial losses from bad loans
- Improve fairness and consistency in the approval process

---

## Dataset

- Total Records: 1,000 loan applications
- Features: 19 attributes including Applicant Income, Credit Score, DTI Ratio, Employment Status, Loan Amount, Property Area, etc.
- Target Variable: Loan_Approved (1 = Approved, 0 = Rejected)

---

## Key Findings

- Credit Score and Debt-to-Income (DTI) Ratio are the strongest predictors of loan approval.
- Higher credit scores significantly increase the chance of approval.
- High DTI ratio is the biggest reason for rejection.
- Urban applicants and government employees show slightly better approval rates.
- Feature engineering improved model performance.

---

## Models Used

| Model                  | Accuracy | Precision | Recall  | F1-Score |
|------------------------|----------|-----------|---------|----------|
| Logistic Regression    | 88.0%    | 78.5%     | 83.6%   | 81.0%    |
| Naive Bayes            | 86.0%    | 81.1%     | 70.5%   | 75.4%    |
| KNN                    | 78.5%    | 67.3%     | 57.4%   | 61.9%    |

**Best Model**: 
Best Model on the basis of Precision => Naive Bayes
Logistic Regression (after feature engineering)

---

## Features Implemented

- Data cleaning and missing value handling
- Exploratory Data Analysis (EDA)
- Feature Engineering (squared features and log transformation)
- Data scaling and train-test split
- Multiple ML model training and evaluation
- Model comparison and performance analysis

---

## Recommendations

- Deploy the model as a decision support tool for loan officers.
- Pay special attention to applicants with high DTI ratio and low credit scores.
- Use the system to provide faster responses to customers.
- Retrain the model periodically with new loan data.

---

## Limitations

- The model is trained on historical data and may not capture sudden economic changes.
- Some personal or external factors are not included in the dataset.
- The system should assist, not completely replace, human judgment in final decisions.

---

## Conclusion

The SmartCredit Loan System successfully demonstrates how Machine Learning can solve real business problems in the banking sector. By accurately predicting loan approvals, this project helps reduce financial risk, minimize bias, and improve the overall lending process.

---

## Technologies Used

- Python
- Pandas, NumPy, Seaborn, Matplotlib
- Scikit-learn

---

## Project Structure
```text
SmartCredit-Loan-System/
├── loan_approval_data.csv
├── SmartCredit.ipynb
├── README.md
└── summary.pdf

```
