# Rental Bikes Demand Prediction System
> This project helps in predicting the number of total rental bikes that would be required for a day, for doing so we have trained a linear regression model using historical data where the target variable is the count of total rental bikes required on a day and where the independent variables used for training the model are windspeed, workingday, weathersit, etc.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
- This project helps in predicting the demand for rental bikes on a given day.
- We have trained a linear regression model which will help to predict the demand of rental bikes on a day where the input such as weather situation, windspeed, etc will be provided by the user.
- US bike service provider named BoomBikes has faced loss in business due to lockdown because of covid 19. So to make recovery in the business after the lockdown ends we have trained a linear regression model with the pre-covid historical data which will help the bike service provider to predict the demand of rental bikes on a day.
- We are using a pre-covid bike sharing dataset which consists of data for the year 2018 and 2019.

## Conclusions
- By just performing a bivariate analysis individually on each of the independent variables against the target variable I could see that independent variables named season, weathersit, holiday, yr, temp, atemp play a good role in determining the demand of rental bikes on a particular day.
- After training the linear regression model and checking its statistics I found out that the variables windspeed, workingday and the dummy variables derived from the weathersit column are mainly determining the total demand of rental bikes on a particular day.
- The trained model most significantly depends upon the "light snow or light rain" dummy variable where the relationship is such that if there is light snow or light rain on a day then the demand for rental bike will decrease on that day. Here the "light snow or light rain" dummy variable has been derived from the weathersit column hence we can conclude that weather plays a good role in predicting the demand of the rental bikes on a particular day.


## Technologies Used
- pandas - version 1.0.5
- matplotlib - version 3.2.2
- seaborn - 0.10.1
- sklearn - version 0.23.1
- statsmodels - version 0.11.1


## Acknowledgements
Give credit here.
- This project was an assignment by Upgrad to strengthen the linear regression concepts.
- This project is based on the dataset provided by Upgrad for the assignment.


## Contact
Created by [@harshdeep] - feel free to contact me!