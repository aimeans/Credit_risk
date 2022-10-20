# Module 12 Report 

## Overview of the Analysis


* The purpose of this analysis was to see how resampling a minority class can affect the accuracy, precision and f1 score of a machine learning model.
* using lending information with training dataset to better predict risky loans.
* The variables that were used were X for Features and y for target variable dataframe.
* First we analyze the data using standardscaler then use the training data to predict the classification of high risk or low risk loans. We then take this data and split it to determine accuracy precision, specificity and f1 score.
* This data was used to train a logistic regression model to predict the testing target variables.


## Results

* Machine Learning Model 1 - Imbalanced:
  * Description of Model 1 Accuracy, Precision, and Recall scores.
  * Imbalanced Data Accuracy: 91%
  * Imbalanced Data Precision low-risk: 100% high-risk: 85%
  * Imbalanced Data Recall Score low-risk: 99% high-risk: 91%
  * Imbalanced Data Specificity low-risk: 91% high-risk: 99%
  * Imbalanced Data F1 Score low-risk: 100 high-risk: 88






## Summary


* the healthy loan performed better, based on the fact that its precision was high and recall was also high giving us a 1.00 f1 score.
* performance definitely depends on the problem were trying to solve as it would always be better to hae more data to continue to train this model but it does seem to have enough data to get the results we were looking for.


