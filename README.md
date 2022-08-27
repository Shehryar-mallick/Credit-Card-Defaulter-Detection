# Credit Card Defaulter Detection

## Description:

This is a machine learning project to predict the credit card defaulters of the bank dataset namely: 
default of credit card clients Data Set. (link:https://archive.ics.uci.edu/ml/datasets/default+of+credit+card+clients)

## Steps Involved:

1) Exploratory data analysis.
2) Data Preprocessing and Wrangling.
3) Data Visualization.
4) Development of various machine learning models for classification. The models used were:
  4.1) KNN
  4.2) Gaussian NB
  4.3) Bernoulli NB
  4.4) Logistic Regression
  4.5) Decision Tree
  4.6) Bagging
  4.7) XGBoosting
  4.8) Bagging with max voting.
  
5) Cross Validation


## Results:

XGBoosting algorithm performed best with scores:
-------------------------------------------------------------
Accuracy = 81.18790496760259%
-------------------------------------------------------------
              precision    recall  f1-score   support

     class 0       0.79      0.84      0.82      4583
     class 1       0.83      0.78      0.81      4677

    accuracy                           0.81      9260

-------------------------------------------------------------
