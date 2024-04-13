# Project 23 / 60 --- Building a Logistic Regression Model from Scratch

## Business Objective

Predicting a qualitative response for observation can be referred to as classifying that observation since it involves assigning the observation to a category or class. 

Classification forms the basis for Logistic Regression. 
Logistic Regression is a supervised algorithm used to predict a dependent variable that is categorical or discrete. 
Logistic regression models the data using the sigmoid function.

I built the model the forecasted customers who churned and this who didn't.

Churned Customers are those who have decided to end their relationship with their existing company. 

In this case study, I worked on a churn dataset.

XYZ is a service-providing company that provides customers with a one-year subscription plan for their product. The company wants to know if the customers will renew the subscription for the coming year or not.
 
## Data Description 
This data provides information about a video streaming service company, where they want to predict if the customer will churn or not. The CSV consists of around 2000 rows and 16 columns.
 
## Aim
Build a logistics regression learning model on the given dataset to determine whether the customer will churn or not.
 
## Tech stack 
Language - Python
Libraries - numpy, pandas, matplotlib, seaborn, sklearn, pickle, imblearn, statsmodel
 
## Approach 
- Importing the required libraries and reading the dataset.
- Inspecting and cleaning up the data
- Perform data encoding on categorical variables
- Exploratory Data Analysis (EDA)
- Data Visualization
- Feature Engineering
- Dropping of unwanted columns
- Model Building
- Using the statsmodel library
- Model Building
- Performing train test split
- Logistic Regression Model
- Model Validation (predictions)
- Accuracy score
- Confusion matrix
- ROC and AUC
- Recall score
- Precision score
- F1-score
- Handling the unbalanced data with balanced weights
- Handling the unbalanced data with random weights
- Adjusting imbalanced data
- Using SMOTE
- Feature Selection
- Barrier threshold selection
- RFE method

Saved the model in the form of a pickle file
