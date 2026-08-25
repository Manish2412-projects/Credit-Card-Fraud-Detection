# Credit-Card-Fraud-Detection
Fraud detection on imbalanced credit card transaction data using SVM classifiers. 


Overview

Credit card fraud detection is a classic imbalanced classification problem — out of 284,807 transactions in this dataset, only 492 (0.17%) are fraudulent. This project explores how to handle that imbalance and build a model that actually catches fraud, rather than one that just predicts "no fraud" every time and still scores 99.8% accuracy.

What it does:
Performs EDA and correlation analysis to find the top 10 most predictive features.
Handles class imbalance via under sampling.
Trains and compares a standard SVM vs. a class-weighted SVM.
Evaluates using confusion matrices and a custom recall-weighted metric.

Dataset
Source: Credit Card Fraud Detection dataset (Kaggle)
284,807 transactions, 492 labeled as fraud

Tech Stack:
Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn.
