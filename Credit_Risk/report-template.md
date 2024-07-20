# Module 20 Report

## Overview of the Analysis
- Purpose of the analysis:
    - The purpose of this analysis is to see how effective we are at predicting credit worthiness of an individual for a loan.
- What financial information the data was on, and what we needed to predict:
    - We looked at various factors, such as the loan amount, borrower income, debt to income ratio, number of accounts the individual held, total amount of debt, number of dergatory marks, and the interest rate of the loan.
    - Using these factors, we needed to make predictions on whether a candidate was a high risk for creditworthiness or not.
- Basic information about the variables we were trying to predict:
    - We were trying to predict the loan status of the individual based on the various financial factors mentioned earlier.
- Stages of the machine learning process we went through as part of this analysis:
    - The first phase was dividing up our labels, which was the loan status, and the features, which were all of the financial factors listed.
    - Once we had these elements divided up, we were able to start splitting up our data into training and testing groups.
    - We then created a logistic regression model and then fit it to our X and y training data.
    - Once we had our logistic regression model fitted, we made predictions using the X testing data.
    - Once this was performed, we finished out the process by generating a confusion matrix and classification report to assess the performance of our logistics regression model.

## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
    * Description of Model 1 Accuracy, Precision, and Recall scores.

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

If you do not recommend any of the models, please justify your reasoning.
