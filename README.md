# 🏦 Home Loan Default Prediction

## 📌 Project Overview

This project focuses on predicting whether a customer is likely to default on a home loan using Machine Learning techniques. The objective is to help financial institutions identify high-risk applicants, reduce credit risk, and improve loan approval decisions.

---

## 🎯 Problem Statement

Banks face challenges in identifying customers who may default on loan repayments. Incorrect loan approvals can result in significant financial losses and increased credit risk.

The goal of this project is to build a Machine Learning model that predicts whether a customer will be a:

- Defaulter (1)
- Non-Defaulter (0)

using customer demographic, financial, and credit-related information.

---

## 🎯 Objectives

- Perform Exploratory Data Analysis (EDA) on loan application data.
- Identify factors influencing loan default behavior.
- Handle missing values and preprocess the data.
- Perform feature engineering and feature selection.
- Build and evaluate multiple Machine Learning models.
- Compare model performance using various evaluation metrics.
- Select the best-performing model for production deployment.

---

## 📂 Dataset Description

The project consists of 7 datasets containing customer application details, credit history, previous loan records, repayment behavior, credit card information, and cash loan details.

### Files Used

- application_train.csv
- bureau.csv
- bureau_balance.csv
- previous_application.csv
- POS_CASH_balance.csv
- credit_card_balance.csv
- installments_payments.csv

---

## 🛠️ Technologies Used

### Programming Language

- Python

### Libraries

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Imbalanced-Learn (SMOTE)

---

## 📊 Exploratory Data Analysis (EDA)

The following analyses were performed:

- Missing Value Analysis
- Target Variable Distribution
- Income Analysis
- Credit Amount Analysis
- Correlation Analysis
- Feature Relationship Analysis
- Customer Risk Analysis

---

## ⚙️ Data Preprocessing

- Missing Value Treatment
- Duplicate Record Check
- Label Encoding
- Feature Scaling
- SMOTE for Class Imbalance Handling

---

## 🔧 Feature Engineering

Created additional features such as:

- Income to Credit Ratio
- Annuity to Income Ratio
- Customer Age
- Credit History Aggregations

---

## 🤖 Machine Learning Models

The following classification algorithms were trained and evaluated:

1. Logistic Regression
2. Decision Tree Classifier
3. Random Forest Classifier
4. Naive Bayes Classifier

---

## 📈 Model Evaluation Metrics

Models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC Score

---

## 📋 Model Comparison

| Model | Accuracy | Precision | Recall | F1-Score | ROC-AUC |
|---------|---------|---------|---------|---------|---------|
| Logistic Regression | 0.919 | 0.481 | 0.021 | 0.040 | 0.735 |
| Decision Tree | 0.824 | 0.151 | 0.256 | 0.190 | 0.671 |
| Random Forest | 0.916 | 0.242 | 0.017 | 0.031 | 0.707 |
| Naive Bayes | 0.189 | 0.083 | 0.895 | 0.151 | 0.524 |

---

## 🏆 Best Model

### Logistic Regression

Reasons for Selection:

- Highest ROC-AUC Score
- Highest Overall Accuracy
- Good Generalization Performance
- Easy Interpretability
- Suitable for Binary Classification Problems

---

## 📌 Key Findings

- External credit score features were among the strongest predictors of loan default.
- Customer income and credit-related variables significantly influenced risk.
- Loan default behavior depends on multiple factors rather than a single feature.
- Class imbalance significantly impacted model performance and was addressed using SMOTE.

---

## ⚠️ Challenges Faced

- Large number of missing values
- Highly imbalanced target variable
- Multiple datasets requiring aggregation and merging
- High-dimensional feature space
- Model overfitting risk

---

## 💡 Suggestions

- Explore advanced ensemble methods such as XGBoost and LightGBM.
- Perform additional feature engineering.
- Update the model periodically with new customer data.
- Combine model predictions with business rules for better decision-making.
- Improve data quality by reducing missing values.

---

## ✅ Conclusion

A Machine Learning-based Home Loan Default Prediction system was successfully developed using customer demographic, financial, and credit-related information.

Multiple classification models were evaluated, and Logistic Regression demonstrated the best overall performance based on ROC-AUC and accuracy. The developed solution can help financial institutions reduce default risk and make more informed loan approval decisions.

---

## 👨‍💻 Author

Kajal More

Data Analyst | Machine Learning Enthusiast