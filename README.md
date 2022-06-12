# BoomBikes Sharing Linear Regression Assignment.
> This assignment is a programming assignment wherein it is built a multiple linear regression model for the prediction of demand for shared bikes.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
- A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits. 
- So in this Assignment analysed the factors affecting the demand for the shared bikes.
- A data set is provided for the year 2018 & 2019 which is pre-covid19 Era.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- The variables 'year', 'workingday', 'temp', and months 'Sep'(Aoril to October Bike rental increases, with september at peak) , weekend on 'Sat', season time 'summer' & 'winter' have a positive impact on the count of bike rentals.
- The variables 'Light Snow','Mist + Cloudy','spring'  have a negative impact on the count of bike rentals.
-  Hence, bike demand will be high in the 
   - months of April to October especially when temperature is comfortable
   - low wind speed , 
   - low rain and snow as well as a misty or cloudy atmosphere. 
   - winter than to summer.
   - coming years



## Technologies Used
- Pandas  - Version: 1.2.4
- Numpy - Version: 1.20.1
- seaborn -  Version: 0.11.1
- matplotlib - Version: 3.3.4
- train_test_split from sklearn.model_selection
- MinMaxScaler from sklearn.preprocessing
- RFE from sklearn.feature_selection
- LinearRegression from sklearn.linear_model
- sm from statsmodels.api
- variance_inflation_factor from statsmodels.stats.outliers_influence
- r2_score from sklearn.metrics