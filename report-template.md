# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
* Explain what financial information the data was on, and what you needed to predict.
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
* Describe the stages of the machine learning process you went through as part of this analysis.
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).

###
The purpose of creating the 2 models was to find out how well supervised machine learning can predit whether or not a client would default on their loans.  2 models were trained to predict healthy loans and high risk loans

I used a logical regression model and with unsampled and sampled data.  The sampled data model was sampled using the oversampler function from imblearn

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models. 
###

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.

## Summary
Confusion Matrix:
  * According to the confusion matrix the model predicted 18663 actually true, and only 56 false positives.  The false was not as accurate with a prediction of 102 false values that were actually true, and 563 that were false.

Acuracy:
  * The F1 score for healthy loan '0' is 1, while unhealthy '1' is .88.  This indicates that the model predicted the testing data accuratelty.  The accuracy score is very high at .99

Precision:
  * The model predicted a high level of precision .99 for '0' and .91 for '1'

Recall: 
  * On the recall '0' has a higher score of 1.00 while '1' ranks lower at .88.  This indicates the model's sensitivty ranks higher for the healthy loans than high-risk loans.


* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.

## Summary
Confusion Matrix:
  * According to the confusion matrix the model predicted 18649 actually true, and only 4 false positives.  The false was not as accurate with a prediction of 116 false values that were actually true, and 615 that were false.

Accuracy:
  * The F1 score for healthy loan '0' is 1, while '1' high-risk loans is .91.  This indicates that the model predicted the testing data accuratelty.  The accuracy score is very high at .99

Precision:
  * The model predicted a high level of precision .99 for both '0' and '1'

Recall:
  * On the recall '0' has a higher score of 1.00 while '1' ranks lower at .84.  This indicates the model's sensitivty ranks higher for the healthy loans than high risk loans.



Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

## Sumary of both models
The model for the resampled training data performed slightly better than the first model.  

If you do not recommend any of the models, please justify your reasoning.
