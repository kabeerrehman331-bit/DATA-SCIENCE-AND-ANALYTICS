# Task 3: Customer Churn Prediction

## Conclusion

### Dataset Overview
- The dataset contained 10,000 rows and 18 columns
- After dropping RowNumber, CustomerId and Surname 
  we were left with 15 useful features
- No missing values were found in this dataset

### Data Preprocessing
- Gender was encoded using Label Encoding (Male=1, Female=0)
- Geography and Card Type were encoded using 
  One Hot Encoding to avoid ranking countries/card types
- All features were successfully prepared for model training

### Key Insights from EDA
- Customers who complained had a much higher churn rate
- Older customers (higher age) tend to churn more
- Customers with higher account balance are more likely to leave
- Satisfaction score alone did not strongly predict churn
- Active members are less likely to leave the bank

### Model Performance
| Model | Accuracy |
|-------|----------|
| Logistic Regression | XX% |
| Decision Tree | XX% |
| Random Forest | XX% |

- Random Forest was the best performing model overall
- Decision Tree was the easiest to interpret and explain

### Feature Importance
The top features that influence customer churn were:
1. Complain — strongest predictor of churn
2. Age — older customers leave more
3. Balance — higher balance customers churn more
4. IsActiveMember — inactive members churn more
5. NumOfProducts — customers with more products tend to stay

### Final Summary
- Customers who complain are the highest risk group
- The bank should focus on resolving complaints quickly
- Targeting inactive older customers with high balances 
  can help reduce churn significantly

Important — Replace the XX% values with your actual accuracy scores from your results! 😊
Then after this your Task 3 is complete and ready to upload to GitHub! 🎉You said: NOW WRTIE  README,ME FILENOW WRTIE  README,ME FILE8:51 AMClaude responded: Task 3 README.Task 3 README.md File
markdown# Task 3: Customer Churn Prediction (Bank Customers)

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
