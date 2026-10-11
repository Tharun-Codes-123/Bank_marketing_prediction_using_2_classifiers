# Bank Marketing Prediction

## Project Overview

This project uses machine learning to predict whether a customer will subscribe to a bank term deposit based on demographic information, financial characteristics, and marketing campaign interactions. The goal is to analyze customer data, identify relevant patterns, and compare classification models to determine which performs better on the test dataset.

## Objectives

- Explore and understand the bank marketing dataset.
- Analyze numerical and categorical features using data visualization.
- Identify missing values, duplicate records, unknown categories, and potential outliers.
- Preprocess categorical variables using one-hot encoding.
- Standardize features for Logistic Regression.
- Train and evaluate Logistic Regression and Decision Tree classifiers.
- Compare model performance using classification metrics and confusion matrices.

## Technologies Used

- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Workflow

1. **Data Exploration:** Examined dataset structure, data types, missing values, duplicates, and categorical value distributions.
2. **Exploratory Data Analysis (EDA):** Used boxplots and countplots to investigate feature distributions and relationships with term deposit subscriptions.
3. **Data Preprocessing:** Applied one-hot encoding to selected categorical features and separated the target variable.
4. **Train-Test Split:** Split the dataset into training and testing sets using stratified sampling.
5. **Feature Scaling:** Standardized features for Logistic Regression.
6. **Model Training:** Built Logistic Regression and Decision Tree classification models.
7. **Evaluation:** Compared accuracy, precision, recall, F1-score, and confusion matrices.

## Models Implemented

- Logistic Regression
- Decision Tree Classifier

## Key Takeaway

This project demonstrates an end-to-end tabular classification workflow, from data exploration and preprocessing to model training and evaluation. The two classifiers are compared using multiple evaluation metrics, with Logistic Regression identified as the better-performing model in the notebook's final analysis.

## Future Improvements

- Perform hyperparameter tuning using cross-validation.
- Analyze feature importance and model interpretability.
- Experiment with Random Forest and Gradient Boosting classifiers.
- Investigate class-specific precision and recall to improve prediction quality.
