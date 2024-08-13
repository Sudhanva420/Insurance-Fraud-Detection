Fraud Detection Using Machine Learning
This project involves the detection of fraudulent transactions in financial data using various machine learning techniques. The project covers data preprocessing, exploratory data analysis (EDA), model building, and evaluation.

Project Overview
Financial fraud is a significant problem that leads to substantial losses. This project aims to build a robust machine learning model that can identify fraudulent transactions with high accuracy.

Dataset
The dataset contains millions of transaction records with the following features:

step: Time step at which the transaction was made.
type: Type of transaction (e.g., 'CASH_OUT', 'TRANSFER').
amount: The amount of money involved in the transaction.
nameOrig: ID of the account originating the transaction.
oldbalanceOrg: Initial balance before the transaction.
newbalanceOrig: Balance after the transaction.
nameDest: ID of the account receiving the transaction.
oldbalanceDest: Initial balance of the recipient account before the transaction.
newbalanceDest: Balance of the recipient account after the transaction.
isFraud: Label indicating whether the transaction is fraudulent (1) or not (0).
Key Steps
1. Data Preprocessing
Data Loading: Load the dataset and check for missing values.
Type Casting: Optimize data types to reduce memory usage.
Feature Engineering: Generate new features and clean existing data.
2. Exploratory Data Analysis (EDA)
Summary Statistics: Generate min and max values for key features.
Data Visualization: Visualize the distribution of transactions and identify patterns related to fraud.
3. Model Building
Machine Learning Models: Implement various models, including Random Forest, Decision Trees, and Neural Networks.
Model Evaluation: Assess models using metrics such as accuracy, precision, recall, and F1-score.
4. Results
Performance Metrics: Present and compare the performance of different models.
Dependencies
Python 3.x
Libraries: numpy, pandas, matplotlib, seaborn, scipy, tensorflow
