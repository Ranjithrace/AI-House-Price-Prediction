# AI House Price Prediction System

**Building AI course project — Elements of AI**

## Summary

This project explores how machine learning can estimate residential property prices in Melbourne, Australia. It uses housing features such as location, number of rooms, building characteristics, and property details to train and evaluate linear regression models. The goal is to make property price estimates more understandable and data-driven.

## Background

Estimating a fair house price can be difficult because property values depend on many factors, including location, size, type, age, and condition.

I chose this project because I previously worked with the Melbourne housing dataset in my university machine learning lab. Through this work, I gained practical experience in data preprocessing, linear regression, optimization, and model evaluation.

The goal is to estimate property prices using historical housing information and understand which features contribute to predictions.

## How is it used?

The proposed system could help property buyers, sellers, students, and people interested in housing-market analysis.

Users would enter details such as property location, number of rooms, building type, and other characteristics. The system would preprocess the information, use a trained model, and return an estimated property price in Australian dollars.

The existing academic work focused on model development and evaluation. A user-facing application is a future extension.

## Data sources and AI methods

The project uses the Melbourne housing dataset, with **Price** as the prediction target.

My previous machine learning lab included:

- Missing-value handling and median imputation
- One-hot encoding of categorical data
- Feature scaling and multicollinearity analysis
- Ordinary least squares linear regression
- Nesterov accelerated gradient descent
- Comparison against scikit-learn's LinearRegression
- Evaluation using RMSE, MAE, and R²

The previous experiments produced approximately:

| Metric | Training result |
|---|---:|
| RMSE | 357,958 AUD |
| MAE | 226,039 AUD |
| R² | 0.689 |

The OLS and Nesterov methods produced very similar predictions. These results describe previous academic experiments, not a deployed application.

## Challenges

- Missing or inaccurate housing data can affect predictions.
- Prices change over time because of market conditions.
- A linear model may not capture complex relationships.
- Prediction errors can be substantial.
- Ethical and licensing considerations must be respected.
- Predictions should not replace professional property valuations.

## What next?

Future improvements could include:

- Publishing reproducible model training code
- Comparing linear regression with random forests and gradient boosting
- Evaluating models on unseen test data
- Developing a simple Streamlit web application
- Explaining important prediction features
- Including prediction uncertainty and newer housing-market data

## Acknowledgments

This project is based on learning from the University of Helsinki's Building AI course and my previous university machine learning coursework.

Scikit-learn was used as a baseline library. The Melbourne housing dataset source and its license will be verified before redistributing data.

**Project status:** AI project proposal supported by previous academic experiments; standalone application not yet deployed.
