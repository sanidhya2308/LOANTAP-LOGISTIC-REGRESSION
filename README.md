# LOANTAP-LOGISTIC-REGRESSION
LoanTap is a fintech lending platform that provides customized loan products for millennials and salaried professionals, including:

• Personal Loans

• EMI-Free Loans

• Personal Overdraft

• Advance Salary Loans

A key challenge for such platforms is determining whether a borrower is likely to repay a loan or default, based on financial and demographic attributes.

🎯 Problem Statement

The objective of this project was to build a machine learning model that can:

✔ Predict whether a loan will be Fully Paid or Charged Off (Default)

✔ Identify key factors driving loan defaults

✔ Generate business insights for better underwriting decisions

📊 Dataset Overview

• 396,030 loan records

• 27 borrower attributes

Important features included:

Loan Amount | Interest Rate | Installment | Annual Income | DTI Ratio | Credit History | Revolving Balance | Employment Length | Home Ownership

Target Variable:

➡ Loan Status

• Fully Paid

• Charged Off

Machine Learning: Scikit-Learn, Logistic Regression

Imbalance Handling: SMOTE

Evaluation Metrics:

Accuracy | Precision | Recall | F1 Score | ROC-AUC | Precision-Recall Curve

🔎 Key EDA Insights

📌 Loan Term Distribution

• 36 months: 76%

• 60 months: 24%

📌 Loan Grades

• Most common: Grade B & C

📌 Home Ownership

• Mortgage: 50%

• Rent: 40%

📌 Loan Purpose

• Debt consolidation: 59%

• Credit card repayment: 21%

📌 Loan Status

• Fully Paid: 80%

• Charged Off: 20%

This revealed a class imbalance problem, addressed during model training.

🧹 Data Preprocessing

• Handling missing values

• Removing duplicates

• Feature engineering

• Encoding categorical variables

• Feature scaling

• Outlier detection using IQR method

• Quantile-based outlier capping

⚙ Model Development

A Logistic Regression classifier was built to predict loan status.

To handle class imbalance:

1️⃣ Class Weight Adjustment

2️⃣ SMOTE (Synthetic Minority Oversampling Technique)

Models were evaluated using ROC-AUC and Precision-Recall curves.

📈 Key Insights

Higher default probability was associated with:

🔴 High loan amounts

🔴 High interest rates

🔴 High DTI ratios

🔴 High credit utilization

Lower risk borrowers typically had:

🟢 Higher annual income

🟢 Lower DTI ratios

🟢 Better credit usage behavior

💡 Business Recommendations

✔ Prioritize DTI ratio and credit utilization in credit scoring

✔ Apply stricter checks on high-interest loans

✔ Introduce risk-based pricing models

✔ Implement ML-driven automated loan approval systems

📚 Skills Demonstrated

• Handling Class Imbalance (SMOTE)

• Model Evaluation & Business Insights

📢 Final Thoughts

Credit risk modeling is one of the most impactful applications of data science in fintech. This project strengthened my understanding of financial risk analytics and classification modeling while translating data insights into real business decisions

#DataScience #MachineLearning #LogisticRegression #FinTech #CreditRisk #Python #EDA #SMOTE #Analytics #GitHubProjects #Scaler
