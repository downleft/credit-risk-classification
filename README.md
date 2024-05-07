# credit-risk-classification
Module 20 Challenge for Data Analytics Boot Camp

# Module 12 Report

## Overview of the Analysis
The purpose of this analysis is to evaluate the effectiveness of a logistic regression machine learning model for identifying the creditworthiness of borrowers by using a dataset with borrower's current debts and income information to predict whether a loan is healthy or high-risk, and comparing this against a known value as to whether or not the loan is high-risk.  This dataset was split into training and testing sets in order to use a Logistic Regression model, and afterwards a confusion matrix was created to view the accuracy, precision, and recall for the model.

## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1: Logistic Regression Model
    * Items in testing test: 19384
    * Model Accuracy: 0.99
    * Precision when predicting healthy loans: 1.00
        * Nearly all of the loans predicted to be healthy were healthy
    * Recall when predicting healthy loans: 1.00
        * Nearly all of the healthy loans were predicted to be healthy
    * Precision when predicting high-risk loans: 0.87
        * 87% of the loans predicted to be high-risk were high-risk loans
    * Recall when predicting high-risk loans: 0.89
        * 89% of the high-risk loans were predicted to be high-risk

## Summary

With an accuracy of 0.99, and a precision and recall for high-risk loans of above 0.85 for all scenarios, this model performed extremely well with the data.  As such, I would recommend that this model continue to be used for predicting whether or borrower's have loans that are considered to be high-risk.