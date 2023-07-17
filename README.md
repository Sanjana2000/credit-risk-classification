# credit-risk-classification

# Module 12 Report 

## Overview of the Analysis

* The purpose of this analysis was to evaluate loan risk
* The model was based off of historical lending activity from a peer-to-peer lending services company
* Using a logistic regression model, we are predicting the healthy loan and high-risk loans using the creditworthiness of borrowers
* First, I split the data into training and test sets. I used a logistic regression model with the original data, then predicted a logistic regression model with resampled training data 


## Results

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.
    - Model 1 Accuracy: 99%
    
    - Label 0 Precision: 100%
    - Label 0 Recall: 99%
    
    - Label 1 Precision: 85%
    - Label 1 Recall: 91%


* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.
  
    - Model 1 Accuracy: 99%
    
    - Label 0 Precision: 100%
    - Label 0 Recall: 99%
    
    - Label 1 Precision: 84%
    - Label 1 Recall: 99%

## Summary

I reccomend Model 1, as it performs best. Although Model 2 has better recall for high-risk loans (99% vs. 91%), the precision is better in Model 1 (85% vs. 84%). Both are very similar, but when evaluating performance, it is best to consider the precision of the higher-risk loan predictions vs. healthy. 



