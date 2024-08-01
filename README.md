# Bike-Demand-Prediction-Using-Multiple-Linear-Regression

### Project Overview
In this project, we developed a multiple linear regression model to predict the demand for shared bikes for BoomBikes, a US-based bike-sharing provider. BoomBikes has experienced a significant drop in revenue due to the COVID-19 pandemic and aims to understand the factors influencing bike demand to improve business strategies post-lockdown. The project involved data preparation, model building, and evaluation using Python, pandas, NumPy, and scikit-learn.

### Problem Statement
BoomBikes offers bikes for short-term use, allowing users to borrow and return bikes at various docks. With the pandemic affecting revenue, BoomBikes wants to analyze the demand for shared bikes once the lockdown ends. The goal is to identify significant variables influencing demand and understand how these variables affect bike rentals.

### Data Preparation
The dataset includes variables such as weather conditions, seasons, and bike demand (casual, registered, and total rentals). Some variables were converted to categorical values for better analysis. The target variable for the model was the total number of bike rentals ('cnt').

### Model Building
We built the multiple linear regression model using the following steps:
1)Data Cleaning: Converted numeric labels to categorical values where necessary.
2)Feature Selection: Included relevant variables such as 'yr' (year), 'weathersit' (weather situation), and 'season'.
3)Model Training: Used the 'cnt' variable as the target and trained the model on the dataset.
4)Model Evaluation: Evaluated the model using the R-squared score on the test set.

### contents
1)Python Notebook: Contains the entire linear regression model, predictions, and evaluation.
2)Subjective Questions PDF: Answers to subjective questions related to linear regression, expanding on the project's learnings.

### Tools and Technologies
Python
pandas
NumPy
scikit-learn
Linear Regression
