# ML_Projects
# Project 1: AllLife Bank Personal Loan Campaign Prediction 
Ganesh Avula

This repository houses the code and analysis for a machine learning project focused on predicting personal loan purchases by AllLife Bank's liability customers.

## Project Overview

AllLife Bank aims to expand its personal loan customer base by pinpointing potential loan purchasers among their existing liability customers. This project strives to develop a robust model capable of identifying these high-propensity customers.

## Data Description

The dataset encompasses information on AllLife Bank's existing customers, including demographics, financial habits, and past loan behavior.

**Features:**

* **Numerical:**
    * Age (in years)
    * Experience (years of professional experience)
    * Income (annual income in thousand dollars)
    * Family Size
    * Average Credit Card Spending (in thousand dollars)
    * Mortgage Value (in thousand dollars)
* **Categorical:**
    * Education Level
    * Previous Loan Acceptance (Yes/No)
    * Securities Account (Yes/No)
    * CD Account (Yes/No)
    * Online Banking Usage (Yes/No)
    * External Credit Card Usage (Yes/No)

**Target Variable:** Personal Loan Purchase (Yes/No)

**A detailed data dictionary with comprehensive descriptions of each feature is provided within the code.**

## Project Objectives

1. **Prediction:** Develop a machine learning model to accurately predict whether a liability customer will purchase a personal loan.
2. **Understanding:** Identify the key customer attributes that most significantly influence loan purchases.
3. **Targeting:** Recommend customer segments most suitable for targeted marketing campaigns for personal loans.

## Getting Started

This repository comes equipped with scripts for data exploration, model building, evaluation, and visualization.

**Prerequisites:** Python libraries including pandas, scikit-learn, matplotlib, etc. (Specific requirements are listed in a `requirements.txt` file for easy installation.)

**Instructions:**

1. Clone this repository using Git.
2. Install the requisite Python libraries using `pip install -r requirements.txt`.
3. Execute the Jupyter Notebooks or Python scripts in the designated order (e.g., start with `data_exploration.ipynb` and follow with `model_building.py`).

## Project Files

* `data/`: Folder containing the data files used in the project.
* `notebooks/`: Folder housing Jupyter notebooks dedicated to data exploration, analysis, and visualization.
* `src/`: Folder containing Python scripts for data processing, model building, and evaluation.
* `requirements.txt`: File specifying the required Python libraries.
* `README.md`: This file (you are here!).


