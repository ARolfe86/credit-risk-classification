# Module 20 Report Template

## Overview of the Analysis

The purpose of this analysis is to evaluate the performance of the logistic regression machine learning model in predicting the credit risk associated with loans. The analysis was conducted on financial data of loan sizes, interest rates, borrowers income, debt-to-income ratios, number of accounts, derogatory marks, and total debt. The objective was to predict the loan status, being either a healthy loan of ('0') or high-risk loan of ('1').

The stages of this machine learning process included the following:

1. Split the datasets for training and testing
2. Create and fit a logistic regression model with data
3. Evaluate the model's performance by observing accuracy, precision, recall, and f1 scores

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model:
  * Accuracy: The accuracy of the model is 0.99, meaning that it correctly classifies 99% of the instances.

  * Precision: For healthy loans ('0'): The model has a precision of 1.00, meaning that it perfectly identifies true positives with no false positives. For high-risk loans ('1'): The model has a precision of 0.87, meaning that it is moderately effective in identifying high-risk loans with some false positives.

  * Recall: For healthy loans ('0'): The model has a recall of 1.00, meaning that it perfectly identifies all instances of healthy loans with no false negatives. For high-risk loans ('1'): The model has a recall of 0.89, meaning that it is moderately effective in identifying high-risk loans with some false negatives.





## Summary

The logistic regression model is doing a great job predicting the '0' (healthy loan) label, with perfect precision, recall, and f1-score of (1.00). The logistic regression model is also doing a good job predicting the '1' (high-risk loan) label, with relatively high precision, recall, and f1-score. The model can still improve closer to perfect in predicting the '1' (high-risk loans), as shown by the lower precision, recall, and f1-score compared to the '0' (healthy loans).