# Credit_Risk_Analysis

## Overview of the analysis: 
Statistical modeling for Credit Card risk
Using SMOTE algorithm to oversample & undersample credit card data set from LendingClub, and ClusterCentroids algorthim for undersample to compare two machine learning models to reduce bias to predict credit risk.

## Resources:
Python mlenv
Jupyter Lab

## Results: 
Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all six machine learning models. 
Use screenshots of your outputs to support your results.

## Summary: 
In the first four models we did a combination Oversample, Undersample and a combination of both to try and determine which model is best at predicting which loans are the highest risk. The next two models we resampled the data using ensemble classifiers to try and predict which which loans are high or low risk. In our first four models our accuracy score is not as high as the ensemble classifiers and the recall in the oversampling/undersampling/mixed models is low as well. 
For the credit card data set, the Easy Ensemble AdaBoost Classifier is the best model to choose with its .93 balanced accuracy. The other models were below .80 balanced accuracy. The precision for all models were similar and within an appropriate range.
Typically in your models you want a good balance of recall and precision which is why I recommend the ensemble classifiers over the first four models. It appears that the Easy Ensemble had the best balance of all the models because of it's high accuracy score and good balance of precision and recall scores.