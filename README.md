
# Credit Card Fraud Detection

## Overview

This repository contains a machine learning project focused on detecting fraudulent credit card transactions. The primary goal of the project is to develop a model that can accurately distinguish between legitimate and fraudulent transactions using historical transaction data.

## Dataset

The dataset used for this project is the publicly available Kaggle Credit Card Fraud Detection Dataset. It contains transactions made by European cardholders in September 2013, with 492 frauds out of 284,807 transactions (0.172%). Due to the confidentiality of the original features, PCA was used to transform the input variables.

- Features: The dataset includes 30 features labeled from V1 to V28 (anonymized using PCA), and two other features: Time and Amount.
- Target: The target column Class represents if a transaction is fraudulent (1) or legitimate (0).

## Models

The following machine learning models have been implemented in this project:
- Logistic Regression
- Random Forest
- Support Vector Machine

## Evaluation Metrics

Since the dataset is highly imbalanced, standard accuracy may not be the best metric. Instead, we focus on:
- Precision: Measures the percentage of predicted frau transactions that were actually fraudulent.
- Recall: Measures the percentage of actual fraudulent transactions that were correctly predicted.
- F1-Score: Harmonic mean of precision and recall.

## Results
![Screenshot 2024-10-16 115625](https://github.com/user-attachments/assets/0ef3f9c2-5c5e-4055-9d79-7599e36fabcd)

