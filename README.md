# credit-risk-classification

This repo contains a Jupyter Notebook that develops a loan approval model based on data of defaults. A logistic regression model is first developed using a selection of training data. Then a model is developed using a different set of data. Both models show strong results, suggesting that they are predictive and can be used in production. Outputs are shown for each model to show their strength.

# Analysis Overview

In this analysis, historical loan data are split into training and test data sets. Loan status (default or preforming) is considered the y variable. The x variable includes borrow characteristics, like borrower income and debt-to-income. Loan characteristics like loan size and interest rate are also considered. The data are then split into training and test sets, and a logistic regression is created. Predictions are made and the accuracy of the model is shown using the model's accuracy score, a confusion matrix, and a classification report. Resampled data using the RandomOversampler method is then used to create a logistic regression model. The model's performance is evaluated by looking at its accuracy score, a confusion matrix, and a classification report. The logistic regression, fit with the oversampled data, does a very good job predicting loan outcomes.

# Results

**

# Summary

[]
