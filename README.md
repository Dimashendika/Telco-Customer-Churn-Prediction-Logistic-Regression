# Telco Customer Churn Prediction Using Logistic Regression

This project uses **Logistic Regression** to predict customer churn for a telecom company. By analyzing customer demographics, service preferences, and billing methods, the model helps identify key drivers of churn and supports strategic retention efforts.

##  Dataset
- Source: [Telco Customer Churn – Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
- Format: CSV
- Size: 7,043 rows and 21 features

##  Tools & Libraries
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn (Logistic Regression)

##  Objective
- Predict which customers are likely to churn
- Understand factors contributing to customer retention or loss
- Provide actionable, interpretable insights for business teams

##  Methodology
1. Data Cleaning & Handling Missing Values
2. Exploratory Data Analysis (EDA)
3. Feature Engineering & Encoding
4. Model Training using Logistic Regression
5. Model Evaluation (Accuracy, ROC-AUC)
6. Insight Extraction from Model Coefficients

##  Model Performance
- **Accuracy**: 80%
- **ROC-AUC Score**: 0.84  
This indicates reliable performance and good separation between churn and non-churn classes.

##  Key Insights

-  **Tenure** is the most influential factor — customers who stay longer are far less likely to churn.
-  **Higher Monthly Charges** surprisingly correlate with **lower churn**, possibly due to bundled premium services.
-  **Two-year contracts**, **online security**, and **tech support** services significantly **reduce churn**.
-  Customers using **fiber optic internet**, **electronic checks**, or **streaming services** are more likely to churn.

##  Business Recommendations

1. **Engage new customers early** with onboarding and targeted offers.
2. **Promote longer-term contracts** through incentives (e.g., loyalty rewards, discounts).
3. **Improve experience** with high-risk services like streaming and fiber internet.
4. **Encourage stable billing options** over electronic check methods.
5. **Upsell value-added features** such as tech support and online security to at-risk users.
