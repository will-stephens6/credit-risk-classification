# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
    The analysis focused on developing machine learning models to predict loan risk, aiming to distinguish between healthy loans and those at high risk of defaulting
* Explain what financial information the data was on, and what you needed to predict.
    Utilizing a dataset comprised of various financial indicators such as loan size, interest rate, borrower income, and more. the key objective was to predict the loan_status variable, which indicates whether a loan is healthy (0) or at high risk (1).
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
* Describe the stages of the machine learning process you went through as part of this analysis.
    Data preparation, including splitting the data into features (X) and labels (y), and further into training and testing sets.
    Implementation of a logistic regression model to serve as Machine Learning Model 1.


## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

*
  * Description of Model Accuracy, Precision, and Recall scores.
    Machine Learning Model: Logistic Regression with Original Data

    Balanced Accuracy Score: 0.952
    Precision:
    Healthy loans (0): ~1.00
    High-risk loans (1): 0.86
    Recall:
    Healthy loans (0): ~1.00
    High-risk loans (1): 0.91



## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
*The logistic regression model demonstrated excellent capability in predicting both healthy and high-risk loans, as shown by its high balanced accuracy, precision, and recall scores. The model was particularly effective in identifying high-risk loans, which is critical for minimizing financial losses due to defaults. Given its robust performance across various metrics, this model is recommended for use in evaluating loan risk. It balances well between identifying both classes, making it a valuable asset for risk management strategies. Further refinement and continuous evaluation are suggested to maintain or improve its performance over time, especially considering the dynamic nature of financial data and risk factors.
