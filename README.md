# Customer-Churn-Prediction-using-Machine-Learning
Project Overview

This project focuses on predicting customer churn using machine learning techniques. The dataset used is the Telco Customer Churn Dataset, which contains customer details such as tenure, services availed, contract type, and monthly charges. The goal is to analyze patterns and build a predictive model to identify customers who are likely to churn.

Dataset

The dataset consists of 7043 records with 21 features, including categorical and numerical variables. The target variable is "Churn", which indicates whether a customer has left the service or not.

Steps Covered in This Project:
Data Preprocessing

Handling missing values
Dropping irrelevant columns (customerID)
Converting categorical values into numerical using Label Encoding
Feature selection using SelectKBest
Exploratory Data Analysis (EDA)

Distribution of customer churn
Impact of different features on churn using visualizations (bar charts, histograms, pie charts, boxplots)
Correlation heatmap
Feature Engineering

Selecting the top 10 most correlated features with churn
Handling class imbalance using SMOTEENN (if required)
Model Building & Evaluation

Splitting data into training (80%) and testing (20%)
Implementing Random Forest Classifier
Evaluating model performance using
Accuracy
Precision
Recall
F1-score
Classification Report
Results
The initial model without hyperparameter tuning achieves an accuracy of 79%.
Further improvements can be made using hyperparameter tuning and ensemble learning methods.
