
# Churn Prediction Analysis (GCP)

- Built a DB ( Big Query )
- Connect to DB with python ( Colab notebook to Big query )
- Build a churn model (PyCaret)
- Export Data to BigQuery
- Build a dashboard ( Looker Studio ) 

## Problem Statement :

We are having issues with keeping employees so we would like a data analyst to help to proactively find employees that are at risk.

## Approach : 

Select pilot program with new employees
adn build an Auto ML model trained on previous data that can predict a new employee will leave.
- Deliverable: Report/Dashboard

## Analysis Questions :

- What is Causing Employees to Leave?
- Who is Predicted to Leave? (highest probability to leave)
- Are Employees Satisfied?
- What Departments Have the Most Churn?

## Project Questions : 

What Does Success Look Like? 
- Highly accurate Predictions Model
What Does Failure Look Like?
- Innacurate Model 
What Trends are Important?
- Features are Causing Churn 
What Actions Affect the Trend?
- Recommendations based on our Analysis

## Machine Learning Workflow : 

- Train : Train Machine Learning Model on 70% of our existing 15,000 employees

- Test : Test and Tune the ML Model for Accuracy on the remaining 30%

- Predict : Use the Optimized ML Model to predict which employees in our pilot will Churn

### Dashboard ( insert the picture after the analysis is done )