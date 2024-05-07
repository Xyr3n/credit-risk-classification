# credit-risk-classification

## Overview of the Analysis

The purpose of the analysis was to train and evaluate loan risk using a historical lending activity dataset. This dataset contained various lending features, including loan size, interest rate, and borrower incomes, among others. We used the loan_status feature to build a model and predict whether the loan status would be healthy (`0`) or high-risk (`1`). The dataset included 75,036 healthy loans and 2,500 high-risk loans. The stages of the machine learning process involved data preparation, feature splitting using `sklearn.model_selection`, model creation and training with `sklearn.linear_model`, feature prediction, and evaluation using `sklearn.metrics`.

## Results

* Machine Learning Logistic Regression Model:
    * Accuracy: 0.99
    * Value `0` precision : 1.00
    * Value `1` precision : 0.87
    * Value `0` recall : 1.00
    * Value `1` recall : 0.89

## Summary

In summary, the logistic regression model demonstrates outstanding performance in predicting healthy loans based on financial information, achieving perfect precision and recall scores of 1. Its performance is slightly lower in predicting high-risk loans, with precision and recall scores comparing to healthy loan. Nevertheless, with an overall accuracy of 0.99, we can confidently conclude that the logistic regression model is a good choice for training the features.
