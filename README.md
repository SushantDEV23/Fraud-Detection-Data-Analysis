Fraud Detection Dataset
Welcome to the Fraud Detection Dataset repository! This repository contains a curated dataset for fraud detection purposes. The dataset includes various features and labels indicating fraudulent activities across different transaction types. The primary aim of this dataset is to facilitate research, benchmarking machine learning models, and developing fraud detection algorithms.

Dataset Description
The dataset consists of transaction data across different transaction types:

CASH-IN: Transactions involving cash deposits into accounts.
CASH-OUT: Transactions involving cash withdrawals from accounts.
DEBIT: Transactions involving debit card usage.
PAYMENT: Regular payment transactions.
TRANSFER: Transactions involving money transfers between accounts.
Each transaction record includes various features relevant to the transaction and is labeled with an indication of whether the transaction is fraudulent or not. The isFraud column identifies transactions conducted by fraudulent agents aiming to deplete customer accounts through transfers and cash-outs.

Usage
Logistic Regression Model
In this repository, we have applied a logistic regression model to the fraud detection dataset. Logistic regression is a commonly used algorithm for binary classification tasks, making it suitable for identifying fraudulent transactions.

Files
fraud_detection_dataset.csv: The dataset containing transaction records and labels.
logistic_regression_fraud_detection.ipynb: Jupyter Notebook containing the code for applying logistic regression on the dataset.
Getting Started
To get started with using this dataset and the logistic regression model, follow these steps:
