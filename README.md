# Seoul_bike_sharing_prediction
![image](https://github.com/udaykbce/Seoul_bike_sharing_prediction/assets/107920149/bf1a6559-960c-43a2-8df7-d65e05bb3b12)

The machine learning project aims to provide the bike rental company of Seoul city with accurate demand for each hour of the day, based on seasons, weather, holiday, etc.

# Attribute Information:

Date: year-month-day

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

# Data Pipeline:
● Exploratory Data Analysis (EDA): In this part, we have done some EDA on the features to see the trend.

● Data Processing: In this part, we went through each attribute and encoded the categorical features.

● Model Creation: Finally in this part, we created the various models. These various models are being analyzed and we tried to study various models so as to get the best performing model for our project.

# Algorithms Used :

Regularized linear regression:

• Lasso regression

• Ridge regression

Ensemble techniques:

• Decision tree regression

• Random-forest regression

• XG–Boost regression

• XG–Boost GridsearchCV


# Conclusions:

• No overfitting is seen.

• When we compare the root mean squared error and mean absolute error of all the models, the XG- boost grid search CV regression model has less root mean squared error and mean absolute error, ending with the Adj. R-squared of 91% in test data. So, finally, this model is best for predicting the bike rental count on daily basis.

• For all the models, temperature and Functioning days were ranked as the most influential variable to predict the rental bike demand at each hour.
