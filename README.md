# credit-risk-classification

## Overview of the Analysis

* The purpose here is to analyze a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.

* The dataset reflected the following financial information: the loan size, the interest rate, the borrower income, the debt-to-income ratio, the number of accounts, the derogatory marks and the	total debt of each loan application.

* In the dataset, we can see there is a discrepancy between the healthy loans (0) counts and the high-risk loans (1) counts: 75036 healthy loans count vs 2500 high-risk count.

* I went through the following stages of the machine learning to process the analysis: Pre-processing (cleaning and preparing the raw data), then training (recognizing the pattern), then validating and evaluating the model.

* First, I used the supervised learning classification model called Logistic Regression to predict the probability of the binary healthy loans vs high-risk loans event to occur. Then, I used the resampling method to generate more data points as to balance the dataset and make a more accurate model. 

## Results

* Machine Learning Model 1:
  * Accuracy - how often the model is correct: the model displays 18679 true positive results and 558 true negative results. 

  * Precision - the ratio of the correctly predicted true positives to the total predicted positive observations: the model performs better predicting healthy loans (precision 1) than high-risk loans (precision 0.87).

  * Recall - the ratio of actual positives identified correctly: the model performs better predicting healthy loans (recall 1) than high-risk loans (recall 0.89).

  * Support - the number of actual occurrences of the class in the specified dataset: according to the support column, the model is imbalanced in the training data (healthy loans 18759 vs high-risk loans 625), indicating structural weaknesses in the reported scores, in the evaluation process.



* Machine Learning Model 2:
  * Accuracy - how often the model is correct: the model displays 55945 true positive results and 55954 true negative results. 

  * Precision - the ratio of the correctly predicted true positives to the total predicted positive observations: the model performs equally well for predicting healthy loans (precision 0.99) and high-risk loans (precision 0.99).

  * Recall - the ratio of actual positives identified correctly: the model performs equally well for predicting healthy loans (recall 0.99) and high-risk loans (recall 0.99).

  * Support - the number of actual occurrences of the class in the specified dataset: according to the support column, the model is balanced in the training data (healthy loans 56277 vs high-risk loans 56277), indicating structural strength in the reported scores, in the evaluation process.


## Summary

* My recommendation would be to use the 'Machine Learning Model 2' as its reported scores are balanced and shows high levels of Accuracy, Precision and Recall for both healthy loans and high-risk loans. With more data points after the resampling, the model 'Machine Learning Model 2' demonstrated higher performance, being more suitable to predict the loan risks and classify them as healthy loans or high-risk loans.