## Predict whether a customer will leave the bank soon

**This Project shows;**
- ability to  prepare the data for training and process all of the feature types
- ability to explained the preprocessing steps thoroughly
- ability to investigate the balance of classes
- ability to study the model without taking into account the imbalance of classes and giving findings about the task research
- ability to split the data into sets
- ability to work with the imbalance of classes
- ability to use at least two techniques for imbalance fixing
- ability to performed the model training, validation, and final testing correctly
- ability to abtain an F1 score of 0.59
- ability to examine the AUC-ROC values at the given F1 score
- ability to keep to the project structure and keep the code neat

**The project involves:**
- Examining the balance of classes. Train the model without taking into account the imbalance. Describing the findings.
- Improving the quality of the model using at least two approaches to fixing class imbalance. Use the training set to pick the best parameters. Train different models on training and validation sets. Find the best one. Describe the findings.
- Performing the final testing.

## Data description
### Features
*RowNumber* — data string index\
*CustomerId* — unique customer identifier\
*Surname* — surname\
*CreditScore* — credit score\
*Geography* — country of residence\
*Gender* — gender\
*Age* — age\
*Tenure* — period of maturation for a customer’s fixed deposit (years)\
*Balance* — account balance\
*NumOfProducts* — number of banking products used by the customer\
*HasCrCard* — customer has a credit card\
*IsActiveMember* — customer’s activeness\
*EstimatedSalary* — estimated salary
### Target
*Exited* — сustomer has left

## Task
Beta Bank customers are leaving: little by little, chipping away every month. The bankers figured out that it’s cheaper to retain the existing customers rather than to attract new ones.
We need to predict whether a customer will leave the bank soon. The data on clients’ past behavior and termination of contracts with the bank has been provided.
We need to build a model with the maximum possible F1 score of at least 0.59 for the test set.
There's also need to measure the AUC-ROC metric and compare it with the F1.

## Libraries Used
_pandas, sklearn.model_selection, sklearn.ensemble, sklearn.tree, sklearn.datasets, sklearn.utils, sklearn.metrics_
