# Loan Prediction Analysis

## Project Overview
Dream Housing Finance Company wants to automate the loan eligibility process based on customer details provided in the online application form. This project predicts whether a loan will be approved based on factors like Gender, Marital Status, Education, Income, Credit History, and more. The task is a supervised classification problem.

## Dataset Information
The dataset consists of the following attributes:

| Variable | Description |
|----------|--------------|
| Loan_ID | Unique Loan ID |
| Gender | Male/Female |
| Married | Applicant married (Y/N) |
| Dependents | Number of dependents |
| Education | Graduate/Under Graduate |
| Self_Employed | Self employed (Y/N) |
| ApplicantIncome | Applicant income |
| CoapplicantIncome | Coapplicant income |
| LoanAmount | Loan amount in thousands |
| Loan_Amount_Term | Term of loan in months |
| Credit_History | Credit history meets guidelines |
| Property_Area | Urban/Semi Urban/Rural |
| Loan_Status | Loan approved (Y/N) |

## Project Workflow
1. **Data Preprocessing**
   - Cleaned missing data using mean/mode imputation.
   - Categorical variables transformed using Label Encoding.
   - Handled outliers and performed feature scaling where necessary.

2. **Exploratory Data Analysis (EDA)**
   - Visualized trends and patterns in the data using Seaborn.
   - Analyzed relationships between features such as income, loan amount, credit history, and loan approval status.

3. **Model Building**
   - Split the data into training and testing sets.
   - Trained multiple classification models (e.g., Logistic Regression, Decision Tree, etc.).
   - Evaluated models using accuracy, confusion matrix, and other performance metrics.

4. **Hyperparameter Tuning**
   - Optimized model parameters using GridSearchCV or RandomizedSearchCV for better accuracy.

5. **Evaluation**
   - Assessed model performance with metrics like accuracy, precision, recall, and F1-score.
   - Confusion matrix to visualize the number of correct and incorrect predictions.

## Technology Stack
- **Languages**: Python
- **Libraries**: Pandas, Seaborn, Scikit-learn, NumPy, Matplotlib
- **Environment**: Jupyter Notebook
