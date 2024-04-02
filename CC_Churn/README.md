# ML_Projects
# Project 2: Credit Card Users Churn Prediction 
Ganesh Avula

This repository contains the code and analysis for a machine learning project predicting credit card user churn at Thera Bank.

### Project Overview

Thera Bank has observed a significant decrease in credit card usage, impacting their revenue stream. To counteract this trend, the bank aims to identify customers at risk of churning (canceling their credit cards) and tailor strategies to retain them. This project develops a classification model to predict customer churn and gain insights into relevant factors.

### Data Description

The dataset comprises information on Thera Bank's credit card users, including demographics, financial behavior, and credit card activity.

**Features:**

* **Numerical:** Customer Age, Dependent Count, Months on Book, Total Relationship Count, Months Inactive (past 12 months), Contacts (past 12 months), Credit Limit, Total Revolving Balance, Average Open-to-Buy (past 12 months), Total Transaction Amount (past 12 months), Total Transaction Count (past 12 months), Average Utilization Ratio.
* **Categorical:** Client Number (unique identifier), Attrition Flag (churned or existing customer), Gender, Education Level, Marital Status, Income Category, Card Category, Change in Transaction Amount (Q4 vs. Q1), Change in Transaction Count (Q4 vs. Q1).

**Target Variable:** Attrition Flag (churned or existing customer)

**A detailed data dictionary explaining each feature is provided within the code.**

### Project Objectives

1. **Prediction:** Develop a machine learning model to accurately predict whether a credit card user is likely to churn.
2. **Understanding:** Identify the key customer characteristics and credit card usage patterns that contribute to churn.
3. **Retention Strategies:** Recommend actionable insights for Thera Bank to improve customer service and card offerings, minimizing churn and maximizing user retention.

### Getting Started

This repository includes scripts for data exploration, model building, evaluation, and visualization.
Data Ingestion: The data set for this project can be downloaded at https://www.kaggle.com/code/kaushikmajumder/credit-card-customer-churn-prediction .
**Prerequisites:** Python libraries including pandas, scikit-learn, matplotlib, etc. 

## Project Files

* `csv/`: Folder containing the data files used in the project.
* `notebooks/`: Folder housing Jupyter notebooks dedicated to data exploration, analysis, and visualization..
* `README.md`: Project desription, objectives, instructions.






