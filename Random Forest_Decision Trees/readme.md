Loan Prediction Model

This project utilizes a machine learning model to predict whether a customer is likely to receive a personal loan based on their financial and personal data. The project includes data preprocessing, model training (using Random Forest and Decision Trees), evaluation, and deployment.

Overview

The goal of this project is to develop a machine learning model that can predict whether a customer will accept a personal loan offer. This is useful for financial institutions to tailor their marketing and loan offers more effectively.
The dataset contains customer demographics, account balances, and transaction history, with a target column Personal.Loan, which indicates whether the customer accepted the loan offer (1) or not (0).

Features

Data cleaning and preprocessing (handling missing/invalid values, transforming features).
Exploratory Data Analysis (EDA) using histograms and scatter plots.
Training models using Random Forest and Decision Tree classifiers.
Model evaluation using accuracy, precision, recall, and F1-score.
Deployment of the model as a web application for real-time predictions.
API for integration with external applications.
Technologies Used
Python (for data preprocessing, model training)
Pandas
NumPy
Scikit-learn
Matplotlib / Seaborn (for data visualization)

Model Performance

Random Forest Classifier
Accuracy: 99%
Precision: 98%
Recall: 88%
F1-score: 93%
Decision Tree Classifier
Accuracy: 98%
Precision: 91%
Recall: 87%
F1-score: 89%
The Random Forest model generally outperformed the Decision Tree classifier, especially in terms of recall and F1-score, making it the preferred choice for deployment.
