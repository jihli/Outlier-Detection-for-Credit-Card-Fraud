# Outlier-Detection-for-Credit-Card-Fraud

Part 1 Import Data and Package Setup

Part 2 Data exploration and EDA

Part 3 Data Transformation

Part 4 Makeup of Train/Validation/Test Data

Part 5 Using Validation dataset to find the best threshold (Employ probability_Based model)

Part 6 Predict outliers on test data

Part 7 IsolationForest Model

---------------------------------------------------------------------------------------------
About the dataset:

Data source links: https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

It is important that credit card companies are able to recognize fraudulent credit card transactions so that customers are not charged for items that they did not purchase.

The dataset contains transactions made by credit cards in September 2013 by European cardholders.

This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

It contains only numerical input variables which are the result of a PCA transformation. Unfortunately, due to confidentiality issues, we cannot provide the original features and more background information about the data. Features V1, V2, … V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-sensitive learning. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.

