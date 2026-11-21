# Heart Disease Prediction

A Machine Learning project that predicts the presence of heart disease in patients based on diagnostic medical metrics.

## Overview
- **Algorithm:** Logistic Regression
- **Task:** Binary Classification
  - `0` = No Heart Disease (Healthy)
  - `1` = Heart Disease Present
- **Accuracy:** ~85% on training data, ~80% on test data

## Key Features Used
The model evaluates 13 clinical attributes:
- **Demographics:** Age, Sex
- **Symptoms & Tests:** Chest pain type, Resting blood pressure, Serum cholesterol, Fasting blood sugar
- **Cardiac Indicators:** Resting ECG, Maximum heart rate achieved, Exercise-induced angina, ST depression (`oldpeak`), ST slope, Major blood vessels (`ca`), Thalassemia status (`thal`)
