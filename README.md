# Credit Risk Score Prediction | Regularized Regression

## Project Overview

This project focuses on predicting credit risk scores using regularized regression techniques. It involves analyzing 1,000 observations to examine financial, operational, and categorical factors associated with credit risk scores and developing regression models to evaluate their predictive performance.

## Objectives

- Explore factors associated with credit risk scores.
- Perform data preprocessing and exploratory data analysis.
- Develop and compare regularized regression models.
- Apply cross-validation and hyperparameter tuning.
- Select the best-performing model based on evaluation metrics.

## Methodology

### 1. Data Preprocessing
- Inspected and prepared the dataset for analysis.
- Cleaned and transformed relevant variables.
- Prepared numerical and categorical features for regression modeling.

### 2. Exploratory Data Analysis (EDA)
- Examined the distribution of credit risk scores.
- Explored relationships between financial, operational, and categorical variables.
- Identified relevant patterns and characteristics in the dataset.

### 3. Regression Model Development

Developed and compared three regularized regression algorithms:

1. Ridge Regression
2. Lasso Regression
3. Elastic Net Regression

### 4. Model Validation and Hyperparameter Tuning
- Applied 5-fold cross-validation.
- Tuned model hyperparameters to evaluate and improve predictive performance.
- Compared models using cross-validation results.

### 5. Model Evaluation and Selection

Evaluated the final models using:
- R² (Coefficient of Determination)
- Root Mean Squared Error (RMSE)
- Mean Absolute Error (MAE)

**Selected Model: Lasso Regression**

Lasso Regression was selected as the final model based on the evaluation results.

## Key Results

| Evaluation Metric | Result |
|---|---:|
| Observations | 1,000 |
| Regression Models Compared | 3 |
| Cross-Validation | 5-Fold |
| Best Model | Lasso Regression |
| Testing R² | 0.8680 |
| Testing RMSE | 9.5013 |
| Testing MAE | 7.6059 |

The selected Lasso Regression model achieved an R² of 0.8680, explaining approximately 86.80% of the variation in credit risk scores within the testing dataset.

## Tools and Libraries

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Project Scope

This project covers exploratory data analysis, data preprocessing, regularized regression modeling, 5-fold cross-validation, hyperparameter tuning, model comparison, and final model evaluation.

## Author

**Ralph Victor Ilarde**  
BS Information Systems – Business Analytics  
West Visayas State University
