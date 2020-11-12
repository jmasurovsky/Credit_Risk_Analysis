# Credit_Risk_Analysis

## Overview

The purpose of this analysis is to predict high or low credit risk using supervised machine learning algorithms. The idea is to compare algorithms that oversample the data, undersample, and a combination of both in order to reduce bias  LendingClub, a lending services company, has provided the credit card dataset in ordefr to perform the analysis.

## Results

- Oversampling the dataset, using the naive bayes algorithm, had a balance accuracy score of 64%, a precision score of 99%, and a recall score of 65%.

- Oversampling the dataset, using the SMOTE algorithm, had a balance accuracy score of 63%, a precision score of 99%, and a recall score of 65%.

- Undersampling the dataset, using the cluster centroids algorithm, had a balance accuracy score of 51%, a precision score of 99%, and a recall score of 41%.

- A combination of over and undersampling the dataset, using the SMOTEEN algorithm, had a balance accuracy score of 63%, a precision score of 99%, and a recall score of 53%.

- The Balanced Random Forest Classifier had a balance accuracy score of 79%, a precision score of 99%, and a recall score of 91%.

- The Easy Ensemble Classifier resulted in a balance accuracy score of 93%, a precision score of 99%, and a recall score of 94%.

## Summary

From the six machine learning models performed, all models showed a precision score of 99%. Undersampling the dataset was least effective in predicting credit risk because of the lowest balanced accuracy and recall score. The Easy Ensemble Classifer model was the most effective in predicting credit-risk based off of a balance accurancy score of 93% and a recall (sensitivity) score of 94%. I would recommend using this model to predict credit-risk. The confusion matrix shows the least number of predictions to be categorized as false positive and false negative, and the most correctly prediction true positives and true negatives.
