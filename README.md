# 💳 Viva Credit Card Defaulter Prediction

This project predicts whether a credit card customer is likely to default in the next month using logistic regression, helping VivaCredit make informed lending decisions.

## Problem Statement

VivaCredit, a Romanian credit card issuer, wants to identify key factors leading to customer default and build a predictive model to:

* Decide whom to issue a credit card to.
* Assign appropriate credit limits.
* Understand customer risk profiles for targeted offerings.

## Solution Approach

* **Model Used**: Logistic Regression
* **Class Imbalance Handling**: SMOTE (Synthetic Minority Oversampling)
* **Evaluation Metrics**: Accuracy, F1-score, ROC-AUC, Confusion Matrix

## Key Insights

* Features like **repayment status (PAY\_0, PAY\_2)** and **credit limit** were strong predictors.
* After applying SMOTE, the model performance improved significantly:

  * **Accuracy**: \~72%
  * **F1-score**: \~73%
  * **ROC-AUC**: \~0.72
* The model can distinguish reasonably well between defaulters and non-defaulters.
