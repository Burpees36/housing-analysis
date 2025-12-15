# Heart Disease Risk Analysis
## Project Summary

This project analyzes a historical heart disease dataset to identify clinically significant risk factors and evaluate predictive models for heart disease. The analysis focuses on statistical rigor, interpretability, and model validation, comparing logistic regression models with random forest approaches.

A complete, reproducible statistical report is provided as a rendered HTML document.

## Objectives

Identify variables significantly associated with heart disease

Build and compare multiple predictive models

Validate model assumptions and goodness-of-fit

Evaluate classification and regression performance

Communicate results in an interpretable, real-world context

## Data Overview

Observations: 303

Variables: 14 clinical predictors + binary target

Target: Presence of heart disease (yes/no)

Key predictors include age, chest pain type, resting blood pressure, maximum heart rate, exercise-induced angina, cholesterol, ECG results, and number of major vessels.

## Models & Methods

Logistic Regression (baseline model)

Logistic Regression with interaction terms

Random Forest Classification

Random Forest Regression

Model validation and evaluation included:

Wald tests

Hosmer–Lemeshow goodness-of-fit

Confusion matrices

ROC curves and AUC

RMSE (regression model)

## Key Results

Logistic regression models achieved an AUC of approximately 0.80

Chest pain type, maximum heart rate, resting blood pressure, and exercise-induced angina were statistically significant predictors

The interaction-based logistic regression model provided the best balance of performance and interpretability

Random forest classification showed strong training performance but weaker generalization on test data, indicating potential overfitting

## Conclusion

An interaction-based logistic regression model was recommended as the final model due to its strong predictive performance, statistical validity, and interpretability. The analysis demonstrates how statistically grounded models can be effectively applied to healthcare risk prediction while maintaining transparency and clinical relevance.

## Full Analysis Report

👉 Interactive HTML report:
https://Burpees36.github.io/heart-disease-risk-modeling/

## Tools Used

R

Logistic Regression

Random Forest

Statistical Hypothesis Testing

ROC & Confusion Matrix Analysis
