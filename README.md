# Bike-Sharing-Demand-Prediction-
## Project Summary -
• Rental bikes is a multi-billion dollar industry, whose popularity is increasing among masses for short distance travelling within cities.To keep up with the demand,it is important to predict the demand for rented bikes per hourly basis to increase the customer satisfaction by reducing the waiting time thus giving an edge over other competitors.

• One of the biggest challenges faced in the bike-sharing system is the unavailability or shortage of bike. This issue has attracted numerous researchers to predict the demand of bike-sharing so that the company is able to redistribute the bikes efficiently and accurately.

• Correctly predicting the count of the bikes can be challenging especially when the data collected are often imbalance . Moreover, despite the several efforts to train models to predict the demand, there is no consensus on which machine learning techniques that will provide the best performance due to the different features applied.

• In this project we have built various regression models to predict the demand for rented bikes.Models used are Linear regression with lasso and ridge regularization,Decision tree,Random forest,Gradient Boosting and XG Boosting.Based on the R2 score,we have found Gradient Boosting model the most accurate model.Gradient Boosting seems to have generalised well on the given data.
## Problem Statement
Currently Rental bikes are introduced in many urban cities for the enhancement of mobility comfort. It is important to make the rental bike available and accessible to the public at the right time as it lessens the waiting time. Eventually, providing the city with a stable supply of rental bikes becomes a major concern. The crucial part is the prediction of bike count required at each hour for the stable supply of rental bikes.

## Data Description:
The dataset contains weather information (Temperature, Humidity, Windspeed, Visibility, Dewpoint, Solar radiation, Snowfall, Rainfall), the number of bikes rented per hour and date information.

Attribute Information:
• Date : year-month-day

• Rented Bike count - Count of bikes rented at each hour

• Hour - Hour of the day

• Temperature-Temperature in Celsius

• Humidity - %

• Windspeed - m/s

• Visibility - 10m

• Dew point temperature - Celsius

• Solar radiation - MJ/m2

• Rainfall - mm

• Snowfall - cm

• Seasons - Winter, Spring, Summer, Autumn

• Holiday - Holiday/No holiday

• Functional Day - NoFunc(Non Functional Hours), Fun(Functional hours)

## Steps involved

 • Installing libraies and getting the dataset.

 • Performing EDA (exploratory data analysis).

 • Drawing conclusions from the data.

 • Hypothesis Testing

 • Feature Engineering and Preprocessing the data.

 • Training different models.

 • Evaluating metrics of all the models.

### Algorithms used

 • Linear Regression

 • Decision Tree Regressor

 • Random Forest Regressor

 • Gradient Boosting

 • XG Boosting

## Conclusion

### Linear Regression

Linear Regression gave underfitted model as the feature relation with the target variable was non-linear one.

Also the lasso and ridge were not helpfull as the model did not overfitted it underfitted due to non-linear relationship.

### Decision Tree

Decision Tree gave good increase in R2 score as compared to linear regression.

Train R2=0.847 and Test R2=0.812 were obtained.

### Random Forest

Gave little gain as compared to decision tree.

Train R2=0.856 and Test R2=0.831 were obtained.

### Gradient Boosting and XGB Boosting

Both boosting techniques gave very good R2 score,better than any of the model.
The reason for choosing Gradient Boosting over XGB Boosting is because very small difference between (train R2=0.948 and test R2=0.897) for Gradient Boosting as compared to XGB Boosting which is (train R2=0.992 and test R2=0.899)
Even though XGB and Gradient Boosting performed equally due to relatively large difference between Train and Test error XGB was not not selected.
Gradient Boosting seems to have generalized well on the given data.
# Gradient Boosting is the model selected based on R2 score.

# Hurrah! I have successfully completed my Machine Learning Capstone Project !!!

