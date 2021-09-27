## Building a Gold Extraction and Purification Model


```python
**This project shows;**
- ability to prepare and analyze the data
- ability to develop ML models
- ability to check the model‘s quality
- ability to keep to the project structure and explain the steps performed
- ability to explain findings
- ability to keep the code neat and avoided code duplication
```

**The project involves:**\
***Preparing the data***
- Checking that recovery is calculated correctly. Using the training set, calculate recovery for the rougher.output.recovery feature. Find the MAE between the calculations and the feature values. Providing findings.
- Analyzing the features not available in the test set i.e their parameters and their type
- Perform data preprocessing.

***Analyze the data***
- Taking note of how the concentrations of metals (Au, Ag, Pb) change depending on the purification stage.
- Compare the feed particle size distributions in the training set and in the test set. If the distributions vary significantly, the model evaluation will be incorrect.
- Consider the total concentrations of all substances at different stages: raw feed, rougher concentrate, and final concentrate. Taking note of any abnormal values in the total distribution. If present, is it worth removing such values from both samples. Describe the findings with and without eliminate anomalies.

***Build the model***
- Writing a function to calculate the final sMAPE value.
- Training different models while evaluating them using cross-validation. 
- Picking the best model and test it using the test sample Providing findings.

## Data Decription
*date,* \
*primary_cleaner.input.sulfate,* \
*primary_cleaner.input.depressant,* \
*primary_cleaner.input.feed_size,* \
*primary_cleaner.input.xanthate,* \
*primary_cleaner.state.floatbank8_a_air,* \
*primary_cleaner.state.floatbank8_a_level,* \
*primary_cleaner.state.floatbank8_b_air,* \
*primary_cleaner.state.floatbank8_b_level,* \
*primary_cleaner.state.floatbank8_c_air,* \
*secondary_cleaner.state.floatbank4_a_air,* \
*secondary_cleaner.state.floatbank4_a_level,* \
*secondary_cleaner.state.floatbank4_b_air,* \
*secondary_cleaner.state.floatbank4_b_level,* \
*secondary_cleaner.state.floatbank5_a_air,* \
*secondary_cleaner.state.floatbank5_a_level,* \
*secondary_cleaner.state.floatbank5_b_air,* \
*secondary_cleaner.state.floatbank5_b_level,* \
*secondary_cleaner.state.floatbank6_a_air,* \
*secondary_cleaner.state.floatbank6_a_level*

## Task
To prepare a prototype of a machine learning model for Zyfra. This is a company that develops efficiency solutions for heavy industry.
The model should predict the amount of gold recovered from gold ore using the data on extraction and purification provided.
It should also assist in optimizing the production and elimination of unprofitable parameters.

## Libraries Used
_pandas, numpy, matplotlib, scipy, sklearn.model_selection, sklearn.linear_model, sklearn.tree, sklearn.ensemble, sklearn.metrics_
