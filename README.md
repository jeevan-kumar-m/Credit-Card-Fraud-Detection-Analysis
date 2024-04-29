## Credit Card Fraud Detection Analysis

This project focuses on analyzing a massive dataset of credit card transactions to build machine learning models capable of predicting customer churn, also known as credit card fraud. The goal is to develop an accurate model that can detect fraudulent transactions, helping credit card companies retain customers and minimize revenue loss.

## Project Overview

The project follows these steps:

1. **Data Cleaning and Preprocessing**: The initial step involves cleaning and preparing the dataset for analysis by handling missing values, converting data types, and removing duplicates. 

2. **Exploratory Data Analysis (EDA)**: Comprehensive EDA is performed to understand the data's characteristics, identify patterns and trends, and visualize the distribution of features and target variables.

3. **Feature Engineering**: Relevant features are selected, and necessary transformations are applied to prepare the data for model building.

4. **Model Building and Evaluation**: Various machine learning models, such as Logistic Regression, K-Nearest Neighbors, Random Forest, and Decision Tree Classifiers, are trained and evaluated on the dataset. The models' performance is assessed using metrics like accuracy, precision, recall, and F1-score.

5. **Model Selection and Deployment**: The best-performing model is selected and deployed for predicting potential credit card fraud.

## Dataset

The project utilizes a dataset containing 5.5 million records of credit card transactions, including features such as transaction date and time, credit card number, merchant details, transaction amount, cardholder information (name, gender, address), and a binary indicator specifying whether the transaction is fraudulent or legitimate.

## Results

Among the evaluated models, the Decision Tree Classifier achieved the highest accuracy, with a training accuracy of 1.0 and a testing accuracy of 0.9971.
