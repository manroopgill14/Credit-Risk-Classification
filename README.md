# Credit-Risk-Classification
Module 20

## Overview of the Analysis


The purpose of this analysis was to analyze lending data to train and evalue the model based on loan risk using logistic regression. We needed to predict whether a loan request was "healthy" or "high risk" which we obtained from the "loan_status" column of the dataset. Differentiation between a healthy loan vs a high risk loan was dependent on a number of factors including the loan size, interest rate, income, debt to income, the number of accounts, derogatory marks and total debt.

Stages of machine learning process in order to complete analysis process:
1. Read in resources file and split the data into training and testing sets. Created labels (y) and features (x).
2. Creating LogisticRegression model with the training date to initialize and fit the model.
3. Retrieve predictions made using the testing data.
4. Analyze the models performance by generating a confusion matric and classification report.


## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Healthy Loans (0):
  * Accuracy: the accuracy of healthy loans was 100% showing that the model predicted correctly.
  * Precision : was 100%, showing that the model was correct when predicting healthy loans.
  * Recall: 99%


* High-Risk Loans (1):
  * Accuracy: 88%, showing that the model predicted 88% correctly.
  * Precision: 85%, showing that the model was correct predicting high risk loans 85% of the time.
  * Recall: 91%

## Summary

This model performed pretty well when predicting healthy loans and high-risk loans. Healthy loans performed better than high-risk loans with an accuracy of 100% vs 88%, respectively. I would reccomend this model for when identifying healthy loans, but would not necessarily recommend the model for high-risk loans as the accuracy and precision metrics were not great. 
