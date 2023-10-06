# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
* Explain what financial information the data was on, and what you needed to predict.
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
* Describe the stages of the machine learning process you went through as part of this analysis.
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).

the purpose of the analysis is to train and make predictions for the data given. The financial data was about money loans and the predictions were based on loan status and predicting the risk of loan statuses. the variables used: _train= to train the data set, _prediction= to predict the outcomes of variable. The varibles that were being predicted were the loan status. First I set variables equal to specific data from the df, then trained those data, and then predicted the data. The methods used were LogisticRegression, train_test_spplit, RandomOverSampler, Counter, confusion_matrix, classification_report, balanced_accuracy_score. 

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.
  precision    recall  f1-score   support

           0       1.00      0.99      1.00     18765
           1       0.85      0.91      0.88       619

    accuracy                           0.99     19384
   macro avg       0.92      0.95      0.94     19384
weighted avg       0.99      0.99      0.99     19384



* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.
     precision    recall  f1-score   support

           0       0.99      0.99      0.99     75036
           1       0.99      0.99      0.99     75036

    accuracy                           0.99    150072
   macro avg       0.99      0.99      0.99    150072
weighted avg       0.99      0.99      0.99    150072

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

the second model performed best because it was in a higher range of 90% of precision in comparison to the first model.

If you do not recommend any of the models, please justify your reasoning.
Both models seemed pretty precise being abovbe 90% so they can be recommended. 