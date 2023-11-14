# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
* Explain what financial information the data was on, and what you needed to predict.
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
*Answer* 
The purpose of this analysis is to use machine learning models to predict credit risk. The data is on loans and whether they are healthy or high-risk. The goal is to predict whether a loan is healthy or high-risk based on the features of the loan. The variables we are trying to predict are the loan status, which is either healthy or high-risk. The value counts for the loan status are 68470 healthy loans and 347 high-risk loans.


* Describe the stages of the machine learning process you went through as part of this analysis.
*Answer* 
The first stage of the machine learning process was to split the data into training and testing sets. The second stage was to create a logistic regression model with the original data. The third stage was to predict a logistic regression model with resampled training data. The fourth stage was to write a credit risk analysis report. 
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).
*Answer*
I used the `LogisticRegression` classifier and the `RandomOverSampler` module from the imbalanced-learn library to resample the data.


## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.
  Accuracy Score: 0.9520479254722232
  Precision Score: 0.99
  Recall Score: 0.94
  F1 Score: 0.96



* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.
  Accuracy Score: 0.9936781215845847
  Precision Score: 1.0
  Recall Score: 0.99
  F1 Score: 0.99


## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

If you do not recommend any of the models, please justify your reasoning.
*Answer*
The two models perform equally well. The accuracy, precision, and recall scores are the same for both models. The performance does not depend on the problem we are trying to solve. It is equally important to predict the 0's and the 1's.



I recommend both models because they perform equally well. The accuracy, precision, and recall scores are the same for both models. The performance does not depend on the problem we are trying to solve. It is equally important to predict the 0's and the 1's.
