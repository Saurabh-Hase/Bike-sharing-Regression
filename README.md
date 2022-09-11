# Bike-sharing-Regression
Currently, Rental bikes are introduced in many urban cities for the enhancement of mobility comfort. It is important to make the rental bike available and accessible to the public at the right time as it lessens the waiting time. Eventually, providing the city with a stable supply of rental bikes becomes a major concern. The crucial part is the prediction of the bike count required at each hour for the stable supply of rental bikes.

In this project, our task is to build a predictive model, which could help Rental bike services in predicting the Rental bike count for a particular condition. As this is a supervised machine learning problem to solve we have used various supervised algorithms to find the relationship between the dependent and independent variables.

First we stared our project by importing dataset containing weather information (Temperature, Humidity, Windspeed, Visibility, Dewpoint, Solar radiation, Snowfall, Rainfall), the number of bikes rented per hour and date information. After importing the data the EDA has been performed on the dataset along with data cleaning.

Further, we used pandas profiling and switviz library to do the Exploratory Data analysis and then also do the data cleaning process, In which we also worked with outliers. Further we used normalisation method to scale the data as the scaling plays imortant part before applying model. We used yeo-johanson normalistion technique as we have some zero values and some negative values in our dataset.

After that we checked the correlation of independent variable with each other as for regression process needs to check the multicolineatity between the variables. After we used one hot encoding to change our catagorical variable into the numerical variable as our machine can not work with string values.

Then, we apply Linear regresssion, Lasso regression, Ridge regression, Elastic net Regression, Ploynmial Regression, Decision Tree Regression, Random Forest, Gradient Boosting and eXtreme Gradient Boosting and evaluate them using Mean Square Error, Root Mean Square Error, R Square and Adjusted R Square.

Finaly we concluded the highest R Square and Adjusted R Square we got from eXtreme Gradient Boosting model which is 0.85 and 0.85.
