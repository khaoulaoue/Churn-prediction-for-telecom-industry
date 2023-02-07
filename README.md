##  Churn-prediction-for-telecom-industry
# Introduction
In the telecommunications industry, churn refers to the loss of customers, either due to the customer switching to a competitor or due to the customer canceling their service altogether. Predicting customer churn is important for companies in the telecommunications industry as it allows them to take proactive steps to reduce customer churn and improve customer retention.
# Project Overview
The project involves the following steps:
# Exploratory Data Analysis (EDA):
To visualize the relationships between different features and perform univariate analysis and bivariate analysis, to identify missing values and handle them accordingly and identify the correlation between the features and the target variable (churn).
# Model Building:

Using XGBoost with Synthetic Minority Over-sampling Technique (SMOTE) to balance the dataset and StratifiedKFold for cross-validation (create a pipeline), building another model using Random Forest. The algorithms were trained on a dataset of telco customer data from kaggle, and the accuracy of the predictions was evaluated using a variety of metrics, including precision, recall, F1 score and AUC. The best model is saved to be used in the Flask app.

# Flask App:

Building the backend of the web application using Flask and HTML frontend and deploying the model to the app.
# Requirements
Python 3.x
Libraries: pandas, numpy, matplotlib, seaborn, xgboost, imblearn, sklearn, flask
Use the web interface to input new customer information and predict the likelihood of churn.

# Conclusion
This project provides a comprehensive solution for predicting customer churn in the telecom industry. The models built in this project can help the telecom company to understand which customers are more likely to leave their services, and take necessary actions to retain them. The Flask app provides an easy-to-use web interface to input new customer information and get predictions.


