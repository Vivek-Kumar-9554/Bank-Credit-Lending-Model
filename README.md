# Credit Risk Analysis

## Overview
This repository contains code for conducting a credit risk analysis using various machine learning algorithms. The analysis includes data preprocessing, exploratory data analysis, feature engineering, and model training and evaluation.

## Dataset
The dataset used in this analysis can be found [here](https://bit.ly/35AyjFR). It includes information about individuals and their credit risk status.

## Libraries Used
- Pandas: Library for data manipulation and analysis
- NumPy: Library for performing scientific computations
- Matplotlib: Library for creating basic visualizations
- Seaborn: Library for creating rich data visualizations
- Scikit-Learn: Library for machine learning models
- Imbalanced-Learn: Library for handling imbalanced datasets

## Data Preprocessing
- Handling missing values in 'Saving accounts' and 'Checking account' columns
- Standardizing variable names for readability
- Binning of 'duration', 'age', and 'credit_amount' variables
- One-hot encoding of categorical variables

## Exploratory Data Analysis (EDA)
- Univariate analysis of key variables
- Bivariate analysis to understand the relationship between target variable 'risk' and other variables
- Heatmap to visualize features with linear relationships

## Model Training
- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- Gradient Boosting Classifier

## Model Evaluation
- Accuracy Score
- Confusion Matrix
- Classification Report
- ROC-AUC Score

## Handling Imbalanced Data
- Using SMOTE (Synthetic Minority Over-sampling Technique) to balance the target variable 'risk'

## Credits
This analysis was conducted by Vivek Kumar and is available on GitHub at [GitHub Repository Link](https://github.com/Vivek-Kumar-9554/Bank-Credit-Lending-Model).

Feel free to contribute, report issues, or provide feedback.

---

**Note:** This README provides an overview of the project and its components. Please refer to the Jupyter Notebook files in this repository for detailed code and analysis.
