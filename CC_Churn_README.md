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

**Prerequisites:** Python libraries like pandas, scikit-learn, matplotlib, etc. (Specific requirements listed in a `requirements.txt` file)

**Instructions:**

1. Clone this repository.
2. Install required libraries (`pip install -r requirements.txt`).
3. Run the Jupyter Notebooks or Python scripts in the specified order (e.g., data exploration followed by model building).

### Project Files

* `data/`: Folder containing the data files for the project.
* `notebooks/`: Folder containing Jupyter notebooks for data exploration, analysis, and visualization.
* `src/`: Folder containing Python scripts for data processing, model building, and evaluation.
* `requirements.txt`: File containing a list of required Python libraries.
* `README.md`: This file (you are here!).



