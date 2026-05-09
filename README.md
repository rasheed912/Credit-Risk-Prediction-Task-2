# Credit Risk Prediction Project

## Project Objective

The objective of this project is to predict whether a loan applicant is likely to default on a loan using machine learning techniques.

Financial institutions face risks when approving loans because some applicants may fail to repay them. This project helps identify high-risk applicants by analyzing customer and financial information such as income, education, loan amount, and credit history.

The project uses classification algorithms to build a predictive model for loan approval and credit risk analysis.

---

# Dataset

Dataset Used: Loan Prediction Dataset (Kaggle)

The dataset contains information about loan applicants, including:

- Applicant income
- Co-applicant income
- Loan amount
- Education level
- Credit history
- Property area
- Marital status
- Loan approval status

Target Variable:# Credit Risk Prediction Project

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

- Loan_Status
  - Y = Approved
  - N = Rejected / High Risk

---

# Project Workflow

## 1. Data Understanding

- Loaded and explored the dataset
- Examined data types and feature descriptions
- Checked dataset dimensions and summary statistics

---

## 2. Data Cleaning and Preparation

Performed preprocessing steps including:

- Handling missing values
- Filling numerical missing values using mean
- Filling categorical missing values using mode
- Encoding categorical variables using Label Encoding

---

## 3. Exploratory Data Analysis (EDA)

Visualized important features using graphs and charts:

- Loan amount distribution
- Applicant income distribution
- Education vs loan status
- Credit history vs loan approval
- Correlation heatmap

EDA helped identify patterns and relationships affecting loan approval.

---

## 4. Model Building

Machine learning models used:

- Logistic Regression
- Decision Tree Classifier

Steps performed:

- Split dataset into training and testing sets
- Trained models using training data
- Predicted loan status on testing data

---

## 5. Model Evaluation

The models were evaluated using:

- Accuracy Score
- Confusion Matrix
- Classification Report

These metrics helped measure the performance of the classification models.

---

# Results and Insights

## Key Insights

- Credit history is one of the strongest factors affecting loan approval.
- Applicants with higher income generally have better approval chances.
- Graduates showed slightly higher loan approval rates.
- Logistic Regression performed effectively for binary classification.

## Model Performance

- The model achieved good prediction accuracy on test data.
- Confusion matrix analysis showed the model correctly classified most applicants.

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

This project demonstrates the complete machine learning workflow for credit risk prediction, including:

- Data cleaning
- Exploratory Data Analysis
- Feature preprocessing
- Classification modeling
- Model evaluation

The predictive system can help financial institutions reduce risk and make better loan approval decisions.

---

# Future Improvements

Possible enhancements include:

- Using advanced models such as Random Forest or XGBoost
- Hyperparameter tuning
- Feature engineering
- Cross-validation
- ROC-AUC analysis
- Handling class imbalance

---

