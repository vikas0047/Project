# Churn Prediction

This repository contains a comprehensive analysis and model implementation for predicting customer churn using a dataset from a company. The goal of this project is to identify customers who are likely to leave the service, allowing the company to take preventive measures.

## Overview

Churn prediction is crucial for businesses as retaining existing customers is often more cost-effective than acquiring new ones. This project involves data preprocessing, exploratory data analysis (EDA), and the implementation of various machine learning models to predict churn.

## Dataset

The dataset used in this project includes various features related to customer demographics, account information, and service usage. It also includes a binary target variable indicating whether a customer has churned.

## Key Features

Categorical Variables: The dataset included two categorical variables that were transformed using OneHotEncoder for better compatibility with machine learning models.
Exploratory Data Analysis (EDA)

## EDA was performed to understand the underlying patterns in the data, including:
1.Distribution of key features
2.Correlation analysis
3.Visualization of customer churn rates across different segments
4.Models Implemented

## Six classification models were implemented to predict customer churn:

1.K-Nearest Neighbors (KNN)
2.Logistic Regression
3.Decision Tree
4.Random Forest
4.Support Vector Machine (SVM)
5.Naive Bayes
6.Hyperparameter Tuning

For each model, hyperparameter tuning was performed to optimize performance. Techniques such as Grid Search were utilized to find the best set of parameters.

## Model Performance

The performance of each model was evaluated using appropriate metrics such as accuracy, precision, recall, and F1-score. Among all the models, Random Forest performed the best, offering the highest accuracy and robustness in predicting customer churn.

# How to Run the Project
1. Clone this repository:
    git clone https://github.com/AnkitaGoyal372/Churn-Prediction.git

