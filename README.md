# Credit Risk Prediction Project

## Project Objective

The objective of this project is to predict whether a loan applicant will successfully repay a loan or default using machine learning techniques.

Financial institutions face risk when approving loans, so this project helps in identifying high-risk applicants using financial, behavioral, and credit-related features such as income, credit score, debt ratio, and loan details.

This is a **binary classification problem**, where the target variable is:

- `loan_paid_back`
  - 1 → Loan Paid Back (Low Risk)
  - 0 → Loan Default (High Risk)

---

# Dataset Description

The dataset contains **20,000 records** with financial and personal credit information of loan applicants.

## Features Used

### Demographic Features
- age
- gender
- marital_status
- education_level
- employment_status

### Income & Financial Features
- annual_income
- monthly_income
- debt_to_income_ratio
- total_credit_limit
- current_balance

### Credit Behavior Features
- credit_score
- delinquency_history
- public_records
- num_of_delinquencies
- num_of_open_accounts

### Loan Details
- loan_amount
- interest_rate
- loan_term
- installment
- loan_purpose
- grade_subgrade

### Target Variable
- loan_paid_back (Target)

---

# Project Workflow

## 1. Data Understanding

- Loaded dataset with 20,000 records
- Checked data types and feature distributions
- Identified target variable (`loan_paid_back`)

---

## 2. Data Cleaning and Preparation

Performed preprocessing steps:

- Checked missing values
- Handled missing data (if any) using mean/mode strategies
- Verified data types (all numeric encoded features)
- Ensured dataset consistency

---

## 3. Exploratory Data Analysis (EDA)

Visual analysis was performed on key features:

- Credit score distribution
- Loan amount distribution
- Annual and monthly income patterns
- Debt-to-income ratio vs repayment behavior
- Education level vs loan repayment
- Employment status impact on loan repayment

### Key Insight from EDA:

- Higher credit score increases chances of loan repayment
- High debt-to-income ratio increases default risk
- Stable employment improves repayment probability

---

## 4. Model Building

Machine learning classification models used:

- Logistic Regression
- Decision Tree Classifier

### Steps:

- Defined feature set (X) and target (y)
- Split dataset into training and testing sets
- Trained models on training data
- Predicted loan repayment on test data

---

## 5. Model Evaluation

Models were evaluated using:

### Metrics:
- Accuracy Score
- Confusion Matrix
- Classification Report

### Confusion Matrix:

Used to measure:
- True Positives (Correct repayment prediction)
- True Negatives (Correct default prediction)
- False Positives
- False Negatives

---

# Results and Insights

## Key Insights

- Credit score is the most important factor in predicting loan repayment
- Debt-to-income ratio strongly influences default probability
- Higher income reduces financial risk
- More delinquencies lead to higher default chances
- Stable employment improves repayment behavior

---

## Model Performance

- Logistic Regression performed well for binary classification
- Decision Tree captured complex patterns in financial behavior
- Overall accuracy was good on test data
- Confusion matrix showed balanced classification performance

---

# Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

# Conclusion

This project successfully builds a machine learning system for credit risk prediction using real financial data.

It includes:

- Data preprocessing and cleaning
- Exploratory Data Analysis (EDA)
- Feature selection and encoding
- Classification model training
- Model evaluation using accuracy and confusion matrix

### Final Outcome:

The system can help financial institutions:
- Identify high-risk loan applicants
- Reduce loan default rates
- Improve decision-making in loan approvals

---

# Future Improvements

- Use advanced models (Random Forest, XGBoost)
- Perform hyperparameter tuning
- Apply feature selection techniques
- Handle class imbalance using SMOTE
- Evaluate using ROC-AUC score
