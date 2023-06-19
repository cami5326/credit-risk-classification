# credit-risk-classification

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
* Explain what financial information the data was on, and what you needed to predict.
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
* Describe the stages of the machine learning process you went through as part of this analysis.
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Accuracy - how often the model is correct: the model displays 18679 true positive results and 558 true negative results. 

Precision - the ratio of the correctly predicted true positives to the total prediced positive observations: the model performs better predicting healthy loans (precision 1) than high-risk loans (precision 0.87).

Recall - the ratio of actual positives identified correctly: the model performs better predicting healthy loans (recall 1) than high-risk loans (recall 0.89).

Support - the number of actual occurrences of the class in the specified dataset: according to the support column, the model is imbalanced in the training data  (healthy loans 18759 vs high-risk loans 625), indicating structural weaknesses in the reported scores, in the the evaluation process.



* Machine Learning Model 2:
  * Accuracy - how often the model is correct: the model displays 55945 true positive results and 55954 true negative results. 

Precision - the ratio of the correctly predicted true positives to the total prediced positive observations: the model performs equally well for predicting healthy loans (precision 0.99) and high-risk loans (precision 0.99).

Recall - the ratio of actual positives identified correctly: the model performs equally well for predicting healthy loans (recall 0.99) and high-risk loans (recall 0.99).

Support - the number of actual occurrences of the class in the specified dataset: according to the support column, the model is balanced in the training data (healthy loans 56277 vs high-risk loans 56277), indicating structural strength in the reported scores, in the the evaluation process.


## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

If you do not recommend any of the models, please justify your reasoning.
