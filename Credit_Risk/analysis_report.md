# Analysis Report

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
- Machine Learning Model 1:
    - For the precision, we can see that we were nearly perfect with loan healthiness. We were a little less precise when looking at high-risk loans at 84%, but still very good. When we look at the weighted average, we can see that we are at 99% precision, which suggest that even though we are only at 84% with high-risk, the number of cases was low.
    - For the recall, we can see both the healthy cases and high-risk cases, our percentages were high (99% and 94% respectively).
    - For the accuracy, we can see we were at 99%, a very strong score. 
## Summary
- Based off of the results, I would say our model did a very good job of predicting healthy loans vs high-risk ones. One of the main reasons I would recommend this model is because it was very good at identifying the number of healthy cases very well. When thinking about whether it's better to predict 1s, which would be the high risk cases, and 0s, which would be the healthy cases, our model tends to lean more towards classifying cases as high risk when they are not, as opposed to classifying cases as healthy when they are high risk. This to me seems like the better of two wrongs because I would rather have a model that is more sensitive towards identifying cases as high risk then incorrectly assuming cases are healthy when they are not.
