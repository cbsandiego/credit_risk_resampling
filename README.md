# Credit Risk Analysis Machine-Learning Model
![machinelearning](images/credit_report.jpg)

## Overview of the Analysis

The following machine-learning model will allow users to use various techniques to train and evaluate models with imbalanced classes.  From a dataset of historical lending activity, we will build a model that will help us identify healthy loans vs. high-risk loans.  Healthy loans typically outnumber risk loans, so we will create a `Logicistic Regression` model with our original data and compare that with a resampled training data that uses `RandomOverSampler`.

    > **[Logistic Regression](https://towardsdatascience.com/logistic-regression-detailed-overview-46c4da4303bc)** - uses a categorical dependent variable to help predict an outcome from a sample of data it's provided.

We will use the following financial information:

* Loan Size
* Interest Rate
* Borrower Income
* Debt to Income
* Number of Accounts
* Derogatory Marks
* Total Debt
* Loan Status

Based on the total sample of `healthy loan` '0' vs `high-risk loan` '1', our model will help us predict whether an applicant is a high-risk or not.  The total sample size for each will help us determine our model's accuracy.

To help us test the accuracy of our prediction, we 
Describe the stages of the machine learning process you went through as part of this analysis.
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1 - Original Data:
  * Description of Model 1 Accuracy, Precision, and Recall scores.
![original](images/original_report.jpg)


* Machine Learning Model 2 - Over Sampler:
  * Description of Model 2 Accuracy, Precision, and Recall scores.
![imbalanced](images/imbalanced_report.jpg)

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )
