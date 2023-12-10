# Credit Card Fraud Detection Project

## Overview
This project is focused on detecting fraudulent credit card transactions using machine learning algorithms. By analyzing transaction data, the goal is to identify patterns and characteristics that are indicative of fraud.

## Dataset
The dataset used in this project is sourced from Kaggle, specifically the "Fraud Detection" dataset available at [this link](https://www.kaggle.com/datasets/kartik2112/fraud-detection/code). It contains transactions made by credit cards in September 2013 by European cardholders.

## Features
The dataset contains transactions over a two-day period, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, with the positive class (frauds) accounting for 0.172% of all transactions. It contains only numerical input variables which are the result of a PCA transformation.

## Requirements
- Python 3.x
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib
- Seaborn

## Model and Approach
I experimented with Logistic Regression and KNN for this project. KNN failed to produce significant results, so I focused on Logistic Regression. For handling the class imbalance, I explored three methods: undersampling, weighted oversampling, and SMOTE (Synthetic Minority Over-sampling Technique).

## Evaluation Metrics
Used the following metrics to evaluate the model:
- Accuracy
- Precision
- Recall
- F1-score

## Contributions
My AI Studio Team: Eric, Saanavi, and Vanessa. We collaborated on visualizations, and they worked on different models. The rest of the project is my work.

