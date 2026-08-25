# Credit-Card-Fraud-Detection
Fraud detection on imbalanced credit card transaction data using SVM classifiers. 


Detects fraudulent credit card transactions using SVM on a highly imbalanced dataset (284,807 transactions, only 492 frauds).

What it does
Performs EDA and correlation analysis to find the top 10 most predictive features
Handles class imbalance via under sampling
Trains and compares a standard SVM vs. a class-weighted SVM
Evaluates using confusion matrices and a custom recall-weighted metric
Tech Stack

Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn

Dataset
Credit Card Fraud Detection (Kaggle) — not included here due to size; download and place creditcard.csv in the project root.
