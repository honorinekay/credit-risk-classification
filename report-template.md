# Module 12 Report Template

## Overview of the Analysis

The purpose of this analysis is to create and evaluate the accuracy of a data model that predicts the credit worthiness of potential borrowers from peer-to-peer lending services.

The dataset (77,536 data points) was split into training and testing sets. The training set was used to build an initial logistic regression model (Logistic Regression Model 1) using the LogisticRegression module from scikit-learn. Logistic Regression Model 1 was then applied to the testing dataset. The purpose of the model was to determine whether a loan to the borrower in the testing set would be low- or high-risk and results are summarized below.

financial information the data was on:
- the size of the loan
- its interest rate
- the borrower's income
- the debt to income ratio
- the number of accounts the borrower held
- derogatory marks against the borrower
- the total debt

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.
### Logistic Regression Model 1: 

- Precision: 93% (an average--in predicting low-risk loans, the model was 100% precise, though the model was only 87% precise in predicting high-risk loans)

- Accuracy: 94%

- Recall: 95% (an average--the model had 100% recall in predicting low-risk loans, but 89% recall in predicting high-risk loans)

## Summary

The logistic regression model predicts a healthy, low-risk loan with 100% precision. It predicts a high-risk loan with lower precision at 87%. The balanced accuracy of the model is 94%.

I would recommend using this model to predict the credit worthiness of borrowers, because it has over 90% accuracy in predicting the outcome of the repayment of the initial loan.
