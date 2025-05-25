# Bank Marketing Analysis: Regression & Classification Models
This repository contains a comprehensive analysis of the Bank Marketing dataset using both regression and classification models. The primary objective is to predict customer behavior in response to marketing campaigns conducted by a Portuguese banking institution.
The dataset, provided by the UCI Machine Learning Repository, contains information about direct marketing campaigns (phone calls) and whether clients subscribed to a term deposit. Two separate notebooks were developed to tackle different problem formulations:
- Regression Task: Predict the number of days the client will take to respond.
- Classification Task: Predict whether the client will subscribe to a term deposit (yes/no).
1. Bank_Marketing_Regression_Model.ipynb
   
- Goal: Predict the Oonsumer Price Index.
- Models Used: XGB Regressor.
- Evaluation Metrics:
  - R² Score
  - Mean Squared Error (MSE)
  - Mean Absolute Error (MAE)
- Highlights:
  - Data preprocessing and feature engineering
  - Model comparison and cross-validation
  - Visualization of prediction errors

2. Bank_Marketing_Classification_Models.ipynb

- Goal: Classify if a client will subscribe to a term deposit (yes/no)
- Models Used:
  - XGB classifier
  - Random Forest Classifier
- Evaluation Metrics:
Accuracy
  - Precision, Recall, F1-Score
  - Confusion Matrix
  - ROC-AUC Curve
- Highlights:
  - Label encoding and SMOTE for handling imbalanced classes
  - Hyperparameter tuning
  - Model comparison using various performance metrics


