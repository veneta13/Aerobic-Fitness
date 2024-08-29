# Aerobic Fitness Prediction

## Overview 🏃🏻
The goal of the project is to develop a predictive model for aerobic fitness, measured by the ability to consume oxygen, based on exercise tests. The dataset includes various measurements taken from men involved in a physical fitness course.

## Models
We build several linear regression models to predict Oxygen based on different combinations of variables.

Models are evaluated based on the coefficient of determination. The following regression assumptions are also tested:
- Breusch-Pagan Test: Assesses homoscedasticity
- Durbin-Watson Test: Checks for autocorrelation in residuals.
- Variance Inflation Factors (VIF): Evaluates multicollinearity among predictors.
- Shapiro Test: checks if the residuals are normally distributed
