# Credit-Risk-Analysis
## Overview of the Analysis

Suppose that we have a dataset containing loans along with information about these loans. People have defaulted (stopped paying) some of the loans. Fitting a machine learning model to this data is supervised learning—because we already have the answers about this dataset (whether each loan has defaulted). Once we fit the model, the benefit of supervised learning is that we can use the model to make predictions about new data. That is, we can predict which loans in the future will be good or bad.

We are building a toolbox of models by applying supervised learning techniques to predict whether a loan will default based on data supplied by a peer-to-peer lending company. To help us with our prediction, we are going to do these steps:

* Check for any class imbalance.

* Apply sampling techniques and use machine learning models to make accurate predictions for imbalanced data.

* Compare the classification models and sampling algorithms.

Split the Data into Training and Testing Sets

Create a Logistic Regression Model with the Original Data

Predict a Logistic Regression Model with Resampled Training Data

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Logistic Regression Model with the Original Data:
  * Model accuracy is 95.20%, Precision avg 99%, and Recall scores avg 99%.


* Logistic Regression Model with Resampled Training Data:
  * Model accuracy is 95.20%, Precision avg 99%, and Recall scores avg 99%.

## Summary

The values for the healthy loans (class 0) is virtually identical between the logistic regression models using both the original and the resampled data. For the 1 class (high-risk loans), the value associated with the model's precision is virtually identical between the model using oversampled data (0.95) and the original data (0.95). The recall number, however, is much higher for the logistic regression model using oversampled data at 0.99 versus the model using the original data at 0.91. Overall, the logistic regression model using the resampled data made much more accurate predictions for the loan data across both classes.
