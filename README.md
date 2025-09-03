# Ola-driver-churn
This project aims to predict driver churn at Ola Cabs using historical driver data.

## Problem Statement
Ola faces high driver churn, negatively impacting both driver morale and acquisition costs. This project seeks to identify key factors influencing driver departures by analyzing their demographics, performance metrics, and tenure information. We aim to build a model predicting driver attrition to facilitate proactive retention strategies.

## Dataset
The project utilizes a dataset named ola_driver.csv containing monthly driver information for 2019 and 2020. It includes attributes like:

Demographics: City, Age, Gender (encoded as Male: 0, Female: 1) Tenure: Joining Date, Last Working Date Performance: Quarterly Rating, Monthly Business Value, Grade, Income Additional: Education Level, Joining Designation

## Project Structure
The project consists of Python scripts:

Perform initial data exploration, checking structure and characteristics. Handle missing values using KNN imputation and prepares data for analysis. Aggregate driver data and creates new features like income and rating increase indicators. Perform feature engineering, including one-hot encoding for categorical variables. Addresse class imbalance in the target variable (driver churn). Implement ensemble learning models (Bagging, Boosting) with hyperparameter tuning. Evaluate model performance using classification reports and ROC AUC curves. Analyze results and provides actionable insights for driver retention strategies.
