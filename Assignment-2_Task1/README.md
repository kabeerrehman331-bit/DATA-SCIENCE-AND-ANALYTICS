# 📈 Bank Marketing Term Deposit Subscription Prediction

A Machine Learning project that predicts whether a bank customer will subscribe to a **term deposit** based on demographic information and previous marketing campaign data. The project also uses **SHAP (SHapley Additive exPlanations)** to explain model predictions and identify the most influential features.

---

## 📌 Project Overview

This project focuses on solving a **binary classification** problem using the **Bank Marketing Dataset** from the UCI Machine Learning Repository.

The objective is to predict whether a customer will subscribe to a term deposit after being contacted through a marketing campaign.

**Target Variable**

- **1 (Yes):** Customer subscribes to a term deposit
- **0 (No):** Customer does not subscribe

---

## 📂 Dataset

**Source:** UCI Machine Learning Repository

The dataset contains **4,521 customer records** with **17 attributes**, including:

- Age
- Job
- Marital Status
- Education
- Account Balance
- Housing Loan
- Personal Loan
- Contact Type
- Contact Month
- Campaign Information
- Previous Marketing Outcome
- Target Variable (y)

---

## 🚀 Features

- Data Loading and Exploration
- Data Cleaning
- Missing Value Analysis
- Exploratory Data Analysis (EDA)
- Label Encoding of Categorical Features
- Train-Test Split
- Model Training
- Model Evaluation
- Feature Importance Analysis
- SHAP Explainability
- Individual Prediction Explanations

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- SHAP

---

## 📦 Required Libraries

Install dependencies using:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn shap
```

---

## 📊 Machine Learning Models

The project compares the performance of:

- Logistic Regression
- Random Forest Classifier

The best-performing model is selected based on evaluation metrics.

---

## 📈 Evaluation Metrics

The models are evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC Curve
- ROC-AUC Score
- Confusion Matrix
- Classification Report

---

## 🔍 Explainable AI

To improve model interpretability, **SHAP (SHapley Additive Explanations)** is used.

SHAP helps explain:

- Global feature importance
- Individual predictions
- Positive and negative feature contributions
- Model decision process

Visualizations include:

- SHAP Summary Plot
- SHAP Bar Plot
- SHAP Force Plot
- Individual Prediction Explanations

---

## 📁 Project Structure

```
├── bank.csv
├── Assignment2_Task1.ipynb
├── README.md
└── requirements.txt
```

---

## ▶️ How to Run

1. Clone the repository

```bash
git clone https://github.com/yourusername/Bank-Term-Deposit-Prediction.git
```

2. Navigate to the project folder

```bash
cd Bank-Term-Deposit-Prediction
```

3. Install dependencies

```bash
pip install -r requirements.txt
```

4. Launch Jupyter Notebook

```bash
jupyter notebook
```

5. Open:

```
Assignment2_Task1.ipynb
```

6. Run all notebook cells.

---

## 📊 Workflow

```
Dataset
    │
    ▼
Data Exploration
    │
    ▼
Preprocessing
    │
    ▼
Feature Encoding
    │
    ▼
Train/Test Split
    │
    ▼
Model Training
    │
    ▼
Performance Evaluation
    │
    ▼
SHAP Explainability
```

---

## 📈 Expected Outputs

The notebook generates:

- Dataset overview
- Missing value analysis
- Data visualizations
- Trained classification models
- Model performance metrics
- Confusion matrix
- ROC Curve
- SHAP Summary Plot
- SHAP Force Plot
- Feature importance analysis
- Explanation of individual customer predictions




---
