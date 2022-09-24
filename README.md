# Bike-sharing-Regression
<b> Problem Description : </b> Currently, Rental bikes are introduced in many urban cities for the enhancement of mobility comfort. It is important to make the rental bike available and accessible to the public at the right time as it lessens the waiting time. Eventually, providing the city with a stable supply of rental bikes becomes a major concern. The crucial part is the prediction of the bike count required at each hour for the stable supply of rental bikes.

In this project, our task is to build a predictive model, which could help Rental bike services in predicting the Rental bike count for a particular condition. As this is a supervised machine learning problem to solve we have used various supervised algorithms to find the relationship between the dependent and independent variables.

<b> Data Description: </b>
The dataset contains weather information (Temperature, Humidity, Windspeed, Visibility, Dewpoint, Solar radiation, Snowfall, Rainfall), the number of bikes rented per hour and date information.

<b> Steps involved : </b>
1. Exploratory Data Analysis : Exploratory Data Analysis, EDA for short, is simply a ‘first look at the data’. It forms a critical part of the machine learning workflow and it is at this stage we start to understand the data we are working with and what it contains. In essence, it allows us to make sense of the data before applying advanced analytics and machine learning.
2. Normalisation : Normalization is generally required when we are dealing with attributes on a different scale, otherwise, it may lead to a dilution in the effectiveness of an important equally important attribute(on a lower scale) because of other attributes having values on a larger scale. For normalisation we used YEO-JOHANSON power  transformation
3. Correlation : A correlation is a statistical measure of the relationship between two variables. The measure is best used in variables that demonstrate a linear relationship between each other. We checked the correlation using VIF number and  then removed the variable accordingly
4. One hot encoding for categorical variable : We used One Hot Encoding to produce binary integers of 0 and 1 to encode our categorical features because categorical features that are in string format cannot be understood by the machine and needs to be converted to numerical format

<b> Machine learning models: </b>
For modelling we tried various regression algorithms like:
1.	Linear Regression
2.	Lasso Regression
3.	Ridge Regression
4.	Elastic Net Regression
5.	Polynomial Regression
6.	Decision Tree
7.	Random Forest
8.	Gradient Boosting
9.	eXtreme Gradient Boosting

<b> Evaluation of models: </b>
For evaluating the models we used 
1. Mean square error
2. Root mean square error
3. R square
4. Adjusted R square

<b> Conclusion: </b>

We applied the above all algorithms and completed our experiments by  evaluating those models with help of different evaluation matrices. 
We have started from EDA, Normalisation, Checking correlation, One hot encoding, then applying various models like Linear Regression, Lasso Regression, Ridge Regression,  Elastic Net Regression, Polynomial Regression, Decision Tree, Random Forest, Gradient Boosting and eXtreme Gradient Boosting. 
After that we have evaluate all those model using different evaluation matrices and we found that Xgboost model giving us best result of R2 = 0.86  and Adjusted R2= 0.86. 





