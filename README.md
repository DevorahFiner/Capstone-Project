# Capstone-Project
# Bank Churn Prediction

## Project Overview
This project focuses on predicting customer churn in the banking sector using machine learning techniques. By analyzing customer demographics, transaction history, and credit utilization, the model identifies customers at risk of leaving. The insights from this project can help financial institutions implement targeted retention strategies.

## Key Features
- **Exploratory Data Analysis (EDA):** Statistical analysis and visualizations to uncover patterns.
- **Feature Engineering:** Creating and selecting key features for model performance.
- **Model Development:** Training multiple models, including Logistic Regression, Decision Tree, Random Forest, SVM, Naive Bayes, AdaBoost, and XGBoost.
- **Hyperparameter Optimization:** Using GridSearchCV to fine-tune the XGBoost model.
- **Class Imbalance Handling:** Using SMOTE to balance the dataset.

## Dataset
The dataset consists of customer information such as:
- Demographics (Age, Gender, Marital Status, Income Level, etc.)
- Credit utilization (Credit Limit, Average Utilization Ratio)
- Transaction history (Total Transactions, Total Transaction Amount)
- Customer churn indicator (Existing vs. Attrited Customers)

## Technologies Used
- **Python**
- **Pandas, NumPy** (Data manipulation and preprocessing)
- **Matplotlib, Seaborn** (Data visualization)
- **Scikit-Learn** (Machine learning models and preprocessing)
- **XGBoost** (Final predictive model)
- **SMOTE** (Handling class imbalance)
- **GridSearchCV** (Hyperparameter tuning)

## Model Performance
The XGBoost model was the best-performing model with the following metrics:
- **Accuracy:** 98.44%
- **F1 Score:** 0.9847
- **ROC AUC Score:** 0.9989
