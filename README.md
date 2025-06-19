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
- **ROC-AUC Score**: 0.83  
This indicates reliable performance and good separation between churn and non-churn classes.

###  Key Takeaways:
- **Tenure**, **long-term contracts**, and **value-added services** (like Online Security and Tech Support) significantly **reduce churn**.
- **Fiber optic internet** and **streaming services** are associated with **higher churn**, possibly due to pricing or service quality expectations.
- **MonthlyCharges**, although counterintuitive, appeared as a churn-reducing factor — suggesting that **premium customers may be more loyal**, highlighting the need for **customer segmentation**.

###  Business Implications:
- Focus retention strategies on **new customers**, promoting **long-term contracts** and **added-value services** early.
- Review and improve the **experience of fiber optic customers** — especially those using streaming services.
- Identify and reward **high-value customers** through **personalized loyalty programs** to maintain engagement.
