## Developing a Model to pick the right plan for the subscribers of a Telecom Company

**This project shows;**
- ability to use existing libraries to build machine learning models.
- ability to keep to the project structure and keep the code neat

**This project involves:**
- Splitting the data into train, validation, and test sets.
- Choosing the sets' sizes.
- Investigating the quality of different models by changing hyperparameters.
- Describing the findings of the study.
- Testing the models.
- Checking the quality of the model using the test set.
- Sanity checking the model.
- General conclusion.

## Data description
Every observation in the dataset contains monthly behavior information about one user. The information given is as follows:\
сalls — number of calls,\
*minutes* — total call duration in minutes,\
*messages* — number of text messages,\
*mb_used* — Internet traffic used in MB,\
*is_ultra* — plan for the current month (Ultra - 1, Smart - 0).

## Task
Mobile carrier Megaline had found out that many of their subscribers were using legacy plans. They wanted to develop a model that would analyze subscribers' behavior and recommend one of Megaline's newer plans: Smart or Ultra.The task is to develop a model that will pick the right plan.\
    The threshold for accuracy should be 0.75 using the test dataset.

## Libraries Used
_pandas and sklearn_
