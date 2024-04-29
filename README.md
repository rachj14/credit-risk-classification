# Credit Risk Analysis Report

## Overview: 
- The purpose of this analysis is to assess how accurate the machine learning model built can identify and predict the credit worthiness of borrowers. 
- The model was built using dataset of historical lending activity from a lending services company, which included borrower's financial information of: their loan size, interest rate, income, debt to income, number of accounts and total debt amount.
- The variable that was trying to be predicted was the 'loan status', whereby value of '0' referred to a healthy loan, and '1' referred to the loan was at risk of defaulting.
- As part of the machine learning process, the data was split into testing and training data, and then used to fit a logistic regression method. The predictions were then saved and evaluated by generating a confusion matrix and a classification report.

## Results:
- Accuracy score: 0.99 - Measures the overall correctness of the model across all classes. 
- Precision score: 0.87 - A high precision indicates that the model is good at not misclassifying negative instances (risk loans) as positive (healthy loans).
- Recall score: 0.89 - A high recall indicates that the model is good at identifying positive instances (healthy loans), even if it means more false positives (risk loans predicted as healthy loans).

## Summary:
