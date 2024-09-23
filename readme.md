# Credit Card Anomaly Detection
This project aims to develop robust machine learning models for identifying fraudulent credit card transactions in real time, protecting customers from financial losses.
## Table of Contents
* [Introduction](#Introduction)
* [Dataset](#Dataset)
* [Exploratory Data Analysis](#EDA)
* [Methodology](#Methodology)
* [Models Used](#ModelsUsed)
 

## Introduction
  Credit card fraud is a significant concern for both financial institutions and cardholders. Early detection of fraudulent transactions is crucial to prevent unauthorised charges and maintain customer trust.
## Dataset
1. **Source:** an anonymised dataset of credit card transactions made by European cardholders in two days September 2013 [Kaggle](#https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud ).
2. **Size:** 284,807 transactions
3. **Fraudulent Transactions:** 492 (highly imbalanced: 0.172% of all transactions)
4. **Features:**
+ V1, V2, ..., V28: Principal components obtained using PCA (transformed)
+ Time: Seconds elapsed between each transaction and the first in the dataset (untransformed)
+ Amount: Transaction amount (untransformed)
+ Class (Target Variable): 1 for fraud, 0 for legitimate transaction (untransformed)

## EDA
+ Univariate
+ Multivariate
+ Support Vector Machine

## Methodology
The project follows a typical machine learning pipeline, including:
1.	**Data Preprocessing:** Cleaned and transformed the dataset for model training.
2.	**Feature Engineering:** Created additional features to improve model performance.
3.	**Model Training:** Implemented anomaly detection algorithm .
4.	**Model Evaluation:** Evaluated models based on Accuracy score and Classification report


## Models Used: 
+ Isolation Forest Algorithm Model
+ Local Outlier Factor (LOF) Algorithm
+	Support Vector Machine (SVM)
[Model code](card.ipynb)







