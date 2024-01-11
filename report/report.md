# Credit Risk Classification Report 

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.

  - The purpose of this analysis is to determine if the model can be accutate enough to predict healthy loans vs high risk loans.

* Explain what financial information the data was on, and what you needed to predict.

  - `loan_status` is used for the predictions

* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).

      value_counts
      0    75036
      1     2500

      oversampled
      0    56271
      1    56271

* Describe the stages of the machine learning process you went through as part of this analysis.

  1. Prepare data
  2. Separate the data into columns `X` and `y`
  3. `train_test_split`
  4. Pick the machine learning model for classification, LogisticRegression
  5. Fit the model with training data
  6. Use the model to make predictions with the test data so 25% default test data to be evaluated.
  7. Evaluate the predictions comparing metrics, confusion matrix, classification report.

* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).

  The methods used were 
    
    - SKLearn
    - LogisticRegression
    - train_test_split
    - confusion_matrix
    - classification_report 

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Accuracy: 0.99
  * Precision
    * Class 0: 1.00
    * Class 1: 0.85
  * Recall 
    * Class 0: 0.99
    * Class 1: 0.91


* Machine Learning Model 2:
  * Accuracy: 0.99
  * Precision
    * Class 0: 1.00
    * Class 1: 0.84
  * Recall 
    * Class 0: 0.99
    * Class 1: 0.99

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

If you do not recommend any of the models, please justify your reasoning.
