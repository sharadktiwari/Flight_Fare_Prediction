# Flight_Fare_Prediction

Predicting fare of flight after getting trained from training data contains Flight details.

# Dataset:
Flight Fare Prediction Posted by Nikhil Mittal in Kaggle.
* 4 - Time Series Columns, 4 - Categorical Columns handled during EDA. Created 30 Feature Columns.
* Selected Best Features from 30 Features.

To Achieve Best Accuracy and To Reduce Overfitting Problem, I used  Random Forest Regressor (With Hyperparameter tuning)

# ABOUT :
Took Flight Fare Data & performed Data Wrangling. During EDA handling Categorical data is major task. Using Features selection technique took best features & 
trained Random Forest Regressor model. After Prediction calculated Errors & Model Score. To Reduce Errors & to boost model score used RandomizedSearchCV for 
Hyper Parameter Tuning. 

 # Values Prior Hyperparameter Tuning
   MAE :  1215.47,
   MSE :  4050931.77, 
   RMSE :  2012.69,
   
# Parameters Obtained After Hyperparameter tuning - 
 'n_estimators': 100,
  'min_samples_split': 2,
  'min_samples_leaf': 1,
  'max_features': 'auto',
  'max_depth': 15
  
# Values After Hyperparameter Tuning
   MAE :  1177.21,
   MSE :  3646424.16,
   RMSE :  1909.56,
  
# Achieved    r2_score -   0.8222

# Contributors:
> Sharad Kumar Tiwari
