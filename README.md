# HR Attrition Dashboard & Predictive Model

## Overview
This project combines a Power BI dashboard for visualizing HR attrition data with a machine learning model to predict employee attrition. The predictive model uses logistic regression to forecast the likelihood of an employee leaving the company.

## Features
1. Interactive Power BI Dashboard
2. Logistic Regression Predictive Model
3. Data Preprocessing Scripts
4. Model Evaluation Metrics

## Dashboard Components
- Employee attrition rate over time
- Attrition by department, job role, and age group
- Salary impact on attrition
- Work-life balance correlation
- Top factors contributing to attrition

## Machine Learning Model
- Algorithm: Logistic Regression
- Features: Age, Tenure, Salary, Job Satisfaction, etc.
- Output: Probability of attrition for each employee

## Setup and Installation
1. Clone the repository
2. Install required packages
3. Run data preprocessing
4. Train the model
5. Open the Power BI dashboard file in Power BI Desktop

## Usage
- Use the Power BI dashboard for visual insights
- Run the predictive model on new data for attrition forecasts
- Adjust model parameters in `train_model.py` for optimization

## Model Performance
- AUC 73 %

## Future Improvements
- Incorporate more advanced ML algorithms (Random Forest, XGBoost)
- Add real-time data updating for the dashboard
- Develop a web interface for the predictive model

