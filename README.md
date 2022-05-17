# Fraud_Detection

This project aims to design a model to detect anomalies in credit card transaction data. The data is sourced from Kaggle.

Anomaly detection model training faces a problem that anomalies in orignal dataset usually takes up little proportion, resulting in insufficient positive data for the model to learn and unsatisfying model performance. In this project, I used undersampling and oversampling to deal with this problem and compared their outcomes.

In this project, I tried logistic regression, knn, decision tree, and auto-encoder, totally four algorithms, and compared their performance in order to build the best detection model out of them. Recall, F-score, precision-recall curve and AUC were applied to evaluate model performance.
