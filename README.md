# International-education-affordability-GBoost-classifier
A machine learning project using Gradient Boosting to classify international university programs as affordable or expensive based on tuition, living expenses, and other cost factors. Includes model comparison, tuning, and feature interpretability.




# International Education Affordability Classifier using Gradient Boosting

This project focuses on developing a machine learning classifier that predicts whether a university program abroad is affordable or expensive. The model is based on features such as tuition fees, rent, living index, visa and insurance costs, and overall duration of the program. Gradient Boosting is used as the primary algorithm for classification.

## Project Objectives

- Develop a binary classifier using Gradient Boosting
- Evaluate and compare performance with Logistic Regression, K-Nearest Neighbors, and Random Forest
- Apply hyperparameter tuning using RandomizedSearchCV and GridSearchCV
- Analyze and interpret feature importance using SHAP and Partial Dependence Plots
- Provide a list of universities categorized as affordable or expensive based on predictions

## Features Used

- Country, City, University, Program, Level  
- Tuition (USD), Rent (USD), Visa Fee (USD), Insurance (USD)  
- Living Cost Index, Exchange Rate, Program Duration

## Dataset Preparation

The dataset includes various cost-related attributes of international education programs. Missing values were handled through imputation, and categorical features were encoded using label encoding. The target label was derived based on the median of the total calculated cost, dividing the entries into two classes: "Affordable" and "Expensive."

## Model Development

- Train-test split was performed with stratification to maintain class balance  
- Multiple classifiers were evaluated, with Gradient Boosting performing best  
- SHAP and Partial Dependence Plots were used to interpret model decisions and identify key features

## Evaluation Metrics

- Accuracy  
- Precision  
- Recall  
- F1-Score  
- Confusion Matrix  
- ROC Curve  
- Feature Importance Visualizations

## Usage

Clone the repo and execute .py file in notebook or any other compiler.
