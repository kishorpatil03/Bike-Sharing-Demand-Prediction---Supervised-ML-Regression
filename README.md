# Bike-Sharing-Demand-Prediction---Supervised-ML-Regression
# Summary -
In recent days, Public rental bike sharing is becoming popular because of its increased comfortableness and environmental sustainability. Data used include Seoul Bike , which is a capital city of South Korea.

Main problem with rented bikes is their availability and waiting time. So our aim is to resolve these issues . During peak hours, like in the morning time and evening time demand increases so price also increases.

To resolve this, we performed following steps :

•	Understood the problem statement

•	 Basic cleaning of data and getting the insight about the data

•	 Performing EDA by plotting different plots.

•	Appling various algorithm such as Linear Regression , Decision Tree , Random Forest, Gradient Boosting & XGBoost to get the best model for our dataset.

Analyzing results and drawing conclusions as Follows – 
# Conclusions - 
•	Functioning day is the most influencing feature and temperature is at the second place for Linear Regressor.

•	Temperature is the most important feature for Decision Tree, Random Forest and Gradient Boosting  Regressor.

•	Functioning day is the most important feature and Winter is the second most for XGBoost Regressor.

The feature temperature is on the top list for all the regressors  except  XGBoost.

XGBoost is acting different from all the regressors  as it is considering whether it is winter or not. And is it a working day or not. Though winter is also a function of temperature only but it seems this trick of XGBoost  is giving better results.

XGBoost Regressor has the Least Root Mean Squared Error(RMSE). So It can be considered as the best model for given problem.
