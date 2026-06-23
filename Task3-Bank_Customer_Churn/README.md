# Task 3: Customer Churn Prediction (Bank Customers)

## Objective
Identify and predict which bank customers are likely to 
leave the bank using classification machine learning models.

## Dataset
- **Source:** Kaggle Churn Modelling Dataset
- **Rows:** 10,000
- **Columns:** 18
- **Target Variable:** Exited (1=Left the bank, 0=Stayed)

## Features Used
| Feature | Description |
|---------|-------------|
| CreditScore | Customer credit score |
| Geography | Country of the customer |
| Gender | Male or Female |
| Age | Age of the customer |
| Tenure | Years with the bank |
| Balance | Account balance |
| NumOfProducts | Number of bank products used |
| HasCrCard | Has credit card or not |
| IsActiveMember | Active member or not |
| EstimatedSalary | Estimated salary |
| Complain | Has complained or not |
| Satisfaction Score | Customer satisfaction rating |
| Card Type | Type of card held |
| Point Earned | Loyalty points earned |

## Approach
1. Loaded and inspected the dataset
2. Dropped irrelevant columns (RowNumber, CustomerId, Surname)
3. Checked and confirmed no missing values
4. Encoded categorical columns:
   - Label Encoding for Gender and Card Type
   - One Hot Encoding for Geography
5. Performed Exploratory Data Analysis with 6 charts
6. Trained and compared 3 classification models
7. Evaluated using accuracy, confusion matrix and 
   classification report
8. Analyzed feature importance to identify key churn drivers

## Libraries Used
- Pandas
- Numpy
- Matplotlib
- Seaborn
- Scikit-learn

## Models Used & Results
| Model | Accuracy |
|-------|----------|
| Logistic Regression | 99.9% |
| Decision Tree | 99.8% |
| Random Forest | 99.9% |

## Key Insights
- Customers who complained had the highest churn rate
- Older customers are more likely to leave the bank
- Customers with higher account balance churn more
- Inactive members are at higher risk of leaving
- Complaint history was the strongest predictor of churn

## Visualizations
- Churn Count Plot
- Age vs Churn Box Plot
- Satisfaction Score vs Churn
- Balance vs Churn Box Plot
- Complaints vs Churn
- Model Accuracy Comparison Chart
- Confusion Matrix
