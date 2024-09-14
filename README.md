# credit-card-fraud-detection
Credit Card Fraud Detection
This project uses machine learning techniques to detect fraudulent credit card transactions. The goal is to build a model that can identify potential fraud from a dataset containing transaction details.

Dataset
Source: Kaggle Credit Card Fraud Detection Dataset
The dataset contains 284,807 transactions, with 492 cases of fraud (0.17%).
Features
Time: Seconds elapsed between this transaction and the first transaction.
V1 - V28: Principal component analysis (PCA)-transformed features to protect sensitive information.
Amount: Transaction amount.
Class: 1 for fraudulent transactions, 0 for non-fraudulent.
Approach
Data Preprocessing:

Handle class imbalance using techniques like under-sampling or SMOTE.
Standardize features for model training.
Models Used:

Logistic Regression
Random Forest
XGBoost
Evaluation Metrics:

Accuracy, Precision, Recall, F1-Score, and AUC-ROC.
Results
Achieved high precision and recall using a Random Forest model.
AUC-ROC score: 0.98.
