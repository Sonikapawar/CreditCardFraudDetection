# Credit-Card-Fraud-Detection

## Problem Statement

The Credit Card Fraud Detection Problem includes modeling past credit card transactions with the knowledge of the ones that turned out to be fraud. This model is then used to identify whether a new transaction is fraudulent or not. Our aim here is to detect 100% of the fraudulent transactions while minimizing the incorrect fraud classifications.
Fraud Detection model based on anonymized credit card transaction
<img src="https://github.com/sagnikghoshcr7/images/blob/master/Credit%20Card%20Fraud%20Detection.jpg" width="400" height="250">

## Available data

The datasets contains transactions made by credit cards in September 2013 by european cardholders.
This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

## Imbalanced data

This is a surprisingly common problem in machine learning (specifically in classification), which results in inappropriate ratio of observations in each class. This highly impacts the accuracy of the model.
Imbalanced classes appear in many domains, including Fraud detection, Spam filtering, subscription churn, etc.
There are various techniques for handling imbalanced data.

## Getting started

1. get the code from the repository
```
git clone https://github.com/Sonikapawar/CreditCardFraudDetection.git 
```
2. [download the dataset](https://kh3-ls-storage.s3.us-east-1.amazonaws.com/Updated Project guide data set/creditcard.csv) that will be used to train a transaction classifier. Unzip it and put the content (creditcard.csv) under main folder (Credit-Card-Fraud-Detection)

3. install required python packages if previously not installed

4. Finally run on Jupyter Notebook
