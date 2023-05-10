# Module 12 Report Template

## Overview of the Analysis

The purpose of this analysis was to build two seperate a logistic regression models and determine how well, and which, can better predict healthy vs high-risk credit loans.
## Results

* Machine Learning Model 1:
  *Healthy loans had a precision of 1.0, a recall of 1.0, and a combined f1-score of 1.00
  *High-Risk loans had a precision of 0.87, a recall of 0.89, and a combined f1-score of 0.88
  *Balanced-accuracy for this model was 94.4%



* Machine Learning Model 2:
  *Healthy loans had a precision of 1.0, a recall of 1.0, and a combined f1-score of 1.00
  *High-risk loans had a precision of 0.87, a recall of 1.0, and a combined f1-score of 0.93
  *Balanced-accuracy for this model was 99.6%

## Summary

Of the two models, I would suggest using the second one.  While both models predict healthy loans very precisely, fitting model 2 with oversampled data improved the precision of high risk loans as seen in the accuracy score.