# Housing Price Prediction
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.




## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

The company wants to know:

* Which variables are significant in predicting the price of a house, and
* How well those variables describe the price of a house.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
* Ridge Regression model performs best with an alpha (lambda) value of 20. Ridge regression model has a test r2 score of 86.56%.
* Lasso Regression model performs best with an alpha (lambda) value of 0.001. Lasso regression model has a test r2 score of 87.94%.
* We could see that the test R2 score is highest with the lasso regression model. Also, this model is better than the ridge regression model because the lasso model reduces the number of features making the model simpler by retaining only the significant features.

The Most significant variables that have a positive effect on the price of the house are:
* Exterior1st - Exterior covering on house
* Neighborhood - Physical locations within Ames city limits
* OverallCond - Rates the overall condition of the house
* OverallQual - Rates the overall material and finish of the house
* BsmtExposure - Refers to walkout or garden level walls
* BsmtFullBath - Basement full bathrooms

The Most significant variables that have a negative effect on the price of the house are:
* Condition2 - Proximity to various conditions
* Fence - Fence quality
* LotFrontage - Linear feet of street connected to property
* HouseStyle - Style of dwelling
* BldgType - Type of dwelling

When the price of the property is lesser than the predicted price from the model, the housing company can buy the property.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- pandas - version 1.4.4
- seaborn - version 0.11.0
- matplotlib - version 3.5.
- numpy - version 1.23.2
- scikit-learn - version 1.2.0

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->
