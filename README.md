# Detection-of-Fraudulent-Transactions

## Introduction
Banking and financial institutions are facing severe challenges due to fraudulent transactions. 2015 alone saw a $21.84 billion fraud losses on on credit, debit and prepaid cards. An article published in Forbes predicts that this could grow by 45% by 2020. Traditional approach of using rules and authenticating transactions is no longer a viable method due to the plethora of payment channels and adept criminals. Machine learning enables to detect and recognize patterns on customer’s purchase history efficiently even on larger datasets. Using machine learning for fraud detection is no longer a trend, it’s a necessity.

In this project, we will be looking at implementing a logistic regression model for detecting fraudulent credit card transactions.

## Dataset
Dataset Link - https://www.kaggle.com/mlg-ulb/creditcardfraud

The datasets contains transactions made by credit cards in September 2013 by european cardholders. This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

It contains only numerical input variables which are the result of a PCA transformation. Unfortunately, due to confidentiality issues, authors cannot provide the original features and more background information about the data. Features V1, V2, ... V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-senstive learning. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise. 
