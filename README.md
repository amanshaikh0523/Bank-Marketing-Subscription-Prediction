# 📌 Bank Marketing Subscription Prediction

## 📖 Project Overview

This project develops an end-to-end machine learning solution to predict whether a customer will subscribe to a bank term deposit based on demographic, financial, and marketing campaign data.

The objective is to help financial institutions identify potential customers and improve the effectiveness of marketing campaigns through data-driven decision making.

---

## 🎯 Problem Statement

Banks conduct direct marketing campaigns to promote term deposits. Predicting which customers are likely to subscribe can reduce marketing costs and improve campaign success.

This project builds a classification model to predict customer subscription using historical campaign data.

---

## 📂 Dataset

- Source: UCI Bank Marketing Dataset
- Records: 4,521
- Target Variable:
  - **y**
    - 1 → Customer subscribed
    - 0 → Customer did not subscribe

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Imbalanced-learn (SMOTE)
- Joblib

---

## 🔍 Project Workflow

1. Data Loading
2. Exploratory Data Analysis (EDA)
3. Data Preprocessing
4. One-Hot Encoding
5. Train-Test Split
6. Feature Scaling
7. Class Imbalance Handling (SMOTE)
8. Model Training
9. Hyperparameter Tuning using GridSearchCV
10. Cross Validation
11. Model Evaluation
12. Feature Importance Analysis
13. Model Saving

---

## 🤖 Machine Learning Models Evaluated

- Logistic Regression
- Random Forest
- XGBoost

XGBoost was selected as the final model based on its overall classification performance.

---

## 📈 Key Features

- Comprehensive Exploratory Data Analysis
- One-Hot Encoding for categorical variables
- Feature Scaling using StandardScaler
- SMOTE for handling class imbalance
- Hyperparameter tuning using GridSearchCV
- Cross-validation for robust evaluation
- Feature Importance Analysis using XGBoost

---

## 📁 Project Structure

```text
Bank-Marketing-Subscription-Prediction/
│
├── Bank Marketing Prediction.ipynb
├── bank.csv
├── bank_marketing_xgb.pkl
├── requirements.txt
├── README.md
└── .gitignore
```

---

## 🚀 Future Improvements

- Deploy the model using Streamlit
- Add real-time prediction interface
- Perform advanced feature engineering
- Compare with additional ensemble models

---

## 👨‍💻 Author

**Aman Shaikh**
