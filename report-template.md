# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
- This analysis aims to train and evaluate Logistic Regression Models to acccurately identify creditworthiness of loan borrowers. 

* Explain what financial information the data was on, and what you needed to predict.
- The dataset contained historical lending activity to predict creditworthiness of borrowers. 

* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
- The variables that were analyzed and predicted are labels 0 (healthy loan) and 1 (high-risk loan).

## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
    * Accuracy Score: Macro Average is 94% for healthy loan applicants. Weighted Average is 99% for risky loan applicants.
    * Precision Score: Healthy loan applicants is 100% while risky loan applicants is 87%. 
    * Recall Score: Healthy loan applicants have a 100% score while risky loan applicants have a 95% score. 

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any.

The logistic regression model is highly recommended to predict the creditworthiness of a borrower. There is an overall accuracy of 99% of this model which is a relatively good and reliable performance. 
