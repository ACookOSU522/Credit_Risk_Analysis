# Credit_Risk_Analysis

## Overview of the analysis: 
Statistical modeling for Credit Card risk
Using SMOTE algorithm to oversample & undersample credit card data set from LendingClub, and ClusterCentroids algorthim for undersample to compare two machine learning models to reduce bias to predict credit risk.

## Resources:
Python mlenv
Jupyter Lab

## Results: 

Naive Random Oversampling results: Our balanced accuracy test it 67%, the precision for the high_risk has a very low positivity at 1% and the recall is 74%


SMOTE oversampling results: the accuracy score is 66.2%, the precision for the high_risk loans has a low positvity again at 1% and recall is 69% overall


Undersampling results: balanced accuracy score is 66.2% overall, the precision is at 99% and the recall is 41%


Combination(over and undersampling) results: balanced accuracy score is 54.7% the precision is 99% and the recall is 57% overall


Balanced Random Forest Classifier results: the accuracy score is 77.2% the precision is 99% and the recall is 88%


Easy Ensemble AdaBoost Classifier results: the accuracy score is 91.7% the precision is 99% and the recall is 94%

## Summary: 
In the first four models we did a combination Oversample, Undersample and a combination of both to try and determine which model is best at predicting which loans are the highest risk. The next two models we resampled the data using ensemble classifiers to try and predict which which loans are high or low risk. In our first four models our accuracy score is not as high as the ensemble classifiers and the recall in the oversampling/undersampling/mixed models is low as well. 
For the credit card data set, the Easy Ensemble AdaBoost Classifier is the best model to choose with its .93 balanced accuracy. The other models were below .80 balanced accuracy. The precision for all models were similar and within an appropriate range.
Typically in your models you want a good balance of recall and precision which is why I recommend the ensemble classifiers over the first four models. It appears that the Easy Ensemble had the best balance of all the models because of it's high accuracy score and good balance of precision and recall scores.