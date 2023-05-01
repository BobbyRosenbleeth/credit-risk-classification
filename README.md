# credit-risk-classification

This repo contains a Jupyter Notebook that develops a loan approval model based on data of defaults. A logistic regression model is first developed using a selection of training data. Then a model is developed using a different set of data. Both models show strong results, suggesting that they are predictive and can be used in production. Outputs are shown for each model to show their strength.

## Analysis Overview

In this analysis, loan status (default or preforming) is considered the y variable. The x variable includes borrow characteristics, like borrower income and debt-to-income. Loan characteristics like loan size and interest rate are also included. The data are then split into training and test sets, and a logistic regression is created. Predictions are made and the accuracy of the model is shown using the model's accuracy score, a confusion matrix, and a classification report. Resampled data using the RandomOversampler method is then used to create a logistic regression model. The model's performance is evaluated by looking at its accuracy score, a confusion matrix, and a classification report. The logistic regression, fit with the oversampled data, does a very good job predicting loan outcomes.

## Results

- **Accuracy Score:** The balanced accuracy score of the initital model was 0.94. It was 0.99 for the model created using random oversampling. The accuracy score represents the total number of correct predictions divided by the total number of predictions. As can be seen, the model is highly accurate.

- **Precision Score:** The Precision Score measures the proportion of positively predicted labels that are actually correct. The initial model had a Precision Score of 1.0 for loans that paid off and 0.89 for loans that defaulted -- very high scores. The random oversampling model had a similarly high Precision Score, 0.99 for both.

- **Recall Score:** The Recall Score measures the model's ability to correctly predict the positives out of actual positives. This is also very high for both models, 1.00/0.87 and 0.99/0.99 respectively.

## Summary

A machine learning model is created using historical loan performance data. I recommend that the company use this model going forward. The model provides strong decisioning results.
 
