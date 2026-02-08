# Lab2
This repository  is for Lab2.

This dataset simulates cardiovascular health checkup records for patients and is designed for machine learning models that predict heart disease risk

Each row represents a patient and includes clinical, lifestyle, and behavioral factors known to influence cardiovascular health. The dataset models realistic medical relationships where high blood pressure, high cholesterol, smoking, stress, and low physical activity increase heart disease risk

(1) Is this a regression, classification, or clustering problem?

This dataset supports both regression and classification, but it is primarily a supervised learning problem
Regression → when predicting the heart_disease_risk_score (a continuous numeric value)
Classification → when predicting the risk_category (Low, Medium, High)

(2) Is there a target variable?

Yes there is a target variable, depending on the task:
For regression:
Target variable: heart_disease_risk_score
For classification:
Target variable: risk_category
All other columns (age, BMI, blood pressure, cholesterol, smoking status, etc.) act as input features

(3) What is the model expected to learn or predict?

The model is expected to learn the relationship between patient characteristics and cardiovascular risk
Specifically, it learns how factors such as: Age, BMI, Blood pressure, Cholesterol level, Smoking status, Physical activity, Stress level
affect heart disease outcomes, and then Predict a numerical risk score (regression), or Classify patients into risk groups (Low, Medium, High)
