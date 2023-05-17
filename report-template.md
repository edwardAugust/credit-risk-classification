# Module 12 Report Template
## Analysis

### Overview
The purpose of this analysis is to determine if a client presents a credit risk. On the csv file we've read into a DataFrame risk is recorded as a binary under the columnn loan_status: 0 is a healthy loan, 1 indicates potential default. Based on the data's features, we need to make a model that will assess loaner risk. 
Using a logistic regression we will be able train our model on the training data, and make prediction based on our original data.

### Results

* Machine Learning Model:
  * The model achieved ~ 95.205% accuracy 
  * The model more precisely predicted healthy loans
  * Recall scores showed that the model favored positive assements, recalling over the original data, 100% for healthy loans while 15% of credit risks were classified healthy.

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Both models appear to have the same values, possibly this is a developper error, further investigation is required.
* Performance is lacking. More exploration is needed.
* This model over diagnoses healthy loans. From a banking standpoint, it would not be efficient to continue relying this model. As a hypthetical, we can imagine that Silicon Bank must have had a poor risk assessment model, which means they lent out too many loans that were a credit risk and therefore lost other people's money.
