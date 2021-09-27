## Developing an app to attract new customers to a  Used Car Sales Service

**This Project shows;**
- ability to prepare the data
- ability to consider different models and hyperparameters
- ability to avoid code duplication
- ability to describe the findings
- ability to keep to the project structure and  keep the code neat

**The Project involves:**
- Training different models with various hyperparameters (considering that various implementations of gradient boosting don't count as different models.) The main point of this step is to compare gradient boosting methods with random forest, decision tree, and linear regression.
- Analyzing the following;
     - the quality of the prediction
     - the speed of the prediction
     - the time required for training                                                    

## Data description
### Features
*DateCrawled* — date profile was downloaded from the database\
*VehicleType* — vehicle body type\
*RegistrationYear* — vehicle registration year\
*Gearbox* — gearbox type\
*Power* — power (hp)\
*Model* — vehicle model\
*Mileage* — mileage (measured in km due to dataset's regional specifics)\
*RegistrationMonth* — vehicle registration month\
*FuelType* — fuel type\
*Brand* — vehicle brand\
*NotRepaired* — vehicle repaired or not\
*DateCreated* — date of profile creation\
*NumberOfPictures* — number of vehicle pictures\
*PostalCode* — postal code of profile owner (user)\
*LastSeen* — date of the last activity of the user
### Target
*Price* — price (Euro)

## Task
Rusty Bargain used car sales service is developing an app to attract new customers. In that app, one can quickly find out the market value of a car. With access to historical data: technical specifications, trim versions, and prices. We need to build the model to determine the value considering the quality, speed and time taken to train the model

## Libraries Used
_pandas, numpy, matplotlib, scipy, sklearn.model_selection, sklearn.linear_model, sklearn.tree, sklearn.ensemble, sklearn.metrics, sklearn.datasets, lightgbm, catboost_
