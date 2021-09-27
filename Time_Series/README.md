## Predict the amount of taxi orders for the next hour for a Taxi Company

**This project shows:**
- ability to preprocess the data
- ability to use different models and hyperparameters
- ability to avoid code duplication
- ability to give the findings
- ability to keep to the project structure and keep the code neat

**The project involves:**
- Downloading the data and resampling it by one hour.
- Analyzing the data.
- Training different models with different hyperparameters. 
- Ensuring that the test sample is set to 10% of the initial dataset.
- Testing the data using the test sample and providing a conclusion.

## Data Description
*datetime -* Thie time the order was given\
*num_orders -* Number of orders given at a given time.

## Task
Sweet Lift Taxi company has collected historical data on taxi orders at airports. To attract more drivers during peak hours, we need to predict the amount of taxi orders for the next hour. Build a model for such a prediction.
The RMSE metric on the test set should not be more than 48.

**Libraries Used**\
_pandas, statsmodels.tsa.seasonal, sklearn.model_selection, sklearn.utils, sklearn.linear_model, sklearn.tree, sklearn.ensemble, sklearn.metrics, matplotlib_
