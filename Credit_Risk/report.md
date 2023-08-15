# Module 12 Report

## Overview of the Analysis

- With this analysis we discover the credit health of the users based in the information on the dataset, the goal is develop a machine learning algorithm to evaluate the risk of the loan
- To achieve this we have to determine the features and the labels, the labels would be the column of loan_status and the rest of them are the features (loan_size, interest_rate
  borrower_income, debt_to_income, num_of_accounts, derogatory_marks, total_debt).
- The predicted values are the summarize of all the features based in the result or the target that we already have in the dataset, to determine the results of future inputs. 
- First of all we need to split the data to put the information into the train test split, then we need to fit our model and we can see the predictions, then evaluate the model's perfomance
  generating a confussion matrix and printing the classification report
- The Logistic regression estimates the probability of an event occurring, such as voted or didn't vote, based on a given dataset of independent variables. This type of statistical model (also
  known as logit model) is often used for classification and predictive analytics.

## Results

Using bulleted lists, describe the balanced accuracy score and the precision and recall score of machine learning model.

* Machine Learning Model: Logistic  Regression

* Description of Model Accuracy, Precision, and Recall scores.
  
- Accuracy:  0.99
- Precision: 0 - 1.00
             1 - 0.85
- Recall:    0 - 0.99
             1 - 0.91   

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any.

- I definitely will use this model because the accuracy was great in the test and this model works very well for this kind od scenarios where you only have two variables (1, 0), may be we can improve the model if we standardize the data, but right now I think this works fine.