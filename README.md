# Housing Price Prediction
>  This assignment is a programming assignment wherein it is built a multiple linear regression model to detect the predictors of the Sales Price of the House.


## Table of Contents
* [General Info](#general-information)
* [Conclusions](#conclusions)
* [Technologies Used](#technologies-used)


## General Information
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file.

The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.
The company wants to know:
- Which variables are significant in predicting the price of a house, and
- How well those variables describe the price of a house.
Also, determine the optimal value of lambda for ridge and lasso regression.



## Conclusions
* Hyperparameter Lambda:
	- Ridge : 1.0
	-Lasso : 0.0001

* Following factors are the good predictor and impact on the sales price of House and are possitively correlated:
	- Ridge : OverallQual, 1stFlrSF, OverallCond, TotalBsmtSF, 2ndFlrSF, GarageArea, BsmtQual, MSZonoing_FV(Floating Village
			  Residential), MSZonoing_RL(Residential Low Density), Foundation Slab.
	- Lasso : OverallQual, 1stFlrSF, TotalBsmtSF, OverallCond, 2ndFlrSF, GarageArea, BsmtQual, LotArea, Foundation Slab,
              KitchenQual.


## Technologies Used
- Pandas  - Version: 1.2.4
- Numpy - Version: 1.20.1
- seaborn -  Version: 0.11.1
- matplotlib - Version: 3.3.4
- train_test_split from sklearn.model_selection
- MinMaxScaler from sklearn.preprocessing
- RFE from sklearn.feature_selection
- LinearRegression from sklearn.linear_model
- r2_score from sklearn.metrics

