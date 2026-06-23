# Task 2: Credit Risk Prediction

## Objective
Predict whether a loan applicant will get approved or not.

## Dataset
- Source: Kaggle Loan Prediction Dataset
- Rows: 5000
- Columns: 10
- Target: LoanApproved (1=Approved, 0=Rejected)

## Approach
1. Loaded and inspected the dataset
2. Handled missing values using median and mode
3. Encoded categorical columns using get_dummies
4. Trained Logistic Regression model
5. Evaluated using accuracy and confusion matrix

## Model Result
|        Model        | Accuracy |
|---------------------|----------|
| Logistic Regression |  85.7%   |

## Results & Insights
- Logistic Regression achieved 85.7% accuracy
- Credit Score was the strongest predictor of loan approval
- Unemployed applicants had lower approval rates
- Missing values were less than 4% and handled successfully

## Libraries Used
- Pandas, Numpy
- Matplotlib, Seaborn
- Scikit-learn
