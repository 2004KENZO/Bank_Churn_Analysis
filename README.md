🏦 Bank Customer Churn Prediction
📘 Overview

This project focuses on predicting whether a bank customer is likely to churn (leave the bank) using demographic details and account activity data.
It demonstrates an end-to-end machine learning workflow, including data preprocessing, exploratory data analysis (EDA), model development, evaluation, and insights generation.

The objective is to help financial institutions identify customers at risk and design effective retention strategies.


README

🚀 Project Workflow
Step	Summary
1. Data Loading & Exploration	Imported a dataset of 10,000 customers obtained from Kaggle and examined feature distributions.
2. Data Cleaning & Preprocessing	Handled missing values, encoded categorical variables, and standardized numerical fields.
3. Exploratory Data Analysis (EDA)	Visualized churn patterns, geography-wise behavior, and feature correlations using Seaborn & Matplotlib.
4. Model Building	Developed Logistic Regression and Random Forest models to classify churn.
5. Model Evaluation	Assessed models using accuracy, precision, recall, F1-score, and ROC-AUC.
6. Business Insights & Visualization	Identified key churn indicators and built a Power BI dashboard for decision-making.
🧠 Machine Learning Models
Model	Accuracy	ROC-AUC	Recall (Churn=1)	Notes
Logistic Regression	81%	0.58	0.20	Baseline model for comparison
Random Forest	87%	0.72	0.48	Best performance; captures non-linear relationships effectively
📊 Key Insights

Geography: German customers had the highest churn rate.

Tenure: Shorter-tenure customers were more likely to leave.

Account Activity: Inactive users showed significantly higher churn risk.

Credit Score: Lower credit scores were associated with increased churn probability.

🧰 Tech Stack

Programming & Libraries:

Python (Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib)

Tools Used:

Google Colab

Power BI

Kaggle Dataset Platform

📈 Results

The Random Forest model achieved 87% accuracy and 0.72 ROC-AUC, making it the best-performing model.

Identified strong churn drivers that can assist banks in creating targeted retention strategies.

Designed a Power BI dashboard for intuitive visualization and business understanding.

📎 Dataset Information

Source: Kaggle – Bank Customer Churn Dataset

Records: 10,000

Target Variable: Exited

1 = Churned

0 = Retained

🙌 Credits

Project enhanced and documented with contributions from Hitesh Kumar.
