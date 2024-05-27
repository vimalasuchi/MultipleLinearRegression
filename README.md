# Project Name
> Multiple Linear Regression Model for Bike Analysis by Vimala using both Linear Regression manually and RFE.
> 
> I have build 2 predicted models and uploaded two relevant pythonnotebook files for the same.
> 

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
## Problem Statement 
A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic.
BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

1. Which variables are significant in predicting the demand for shared bikes.
2. How well those variables describe the bike demands
Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors. 

## Business Goal:
Prepare a model for the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations
I am using this data set for analysis "day.csv"

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->
## Models created

I have build 2 predicted models and uploaded two relevant pythonnotebook files for the same.

1. MLR_Bike_Viimala_using MLR.ipynb - 
In this file I have used the Multiple Linear regression model to create the base model with all variables and then based on p-value and Variable Inflation Factor (VIF) analysis, manually dropped variables until the final predicted model was statistically signficant. 

2. MLR_Bike_Viimala_using RFE.ipynb

In this file I have used the automated Recursive Feature Elimination method to create the base model and then based on p-value and Variable Inflation Factor (VIF) analysis, manually dropped variables until the final predicted model was statistically signficant. 

## Approach Followed

1. Data Analysis
2. Data cleaning 
    a. reducing redundant colums
3. Data Visualization using uni-variate and bi-variate, multi-variate analysis and understanding the correlation - multicollinearity 
4. Data Preparation
    a. converting the variables - to categorical variables
    b. creating dummy variables for all the categorical variables
5. Data Modelling using multiple linear regression model using all variables
    a. Create train and test data 
6. Creating various models based on P-value and VIF for train data
7. Based on Final model, do a residual analysis on the train data 
8. Make predictions using the final model
9. create test data set and Evaluate the model on test data set 
10. Calculate the r2

## Conclusions

As per our final Model, the below predictor variables influences bike booking :

Positive influence

1. temp
2. yr_2019
3. season_winter
4. mon_sep
5. season_summer
6. weekday_mon
7. workingday_yes_workingday
8. mon_aug 
9. mon_oct

Negative Influence
1. weathersit_Mist_Cloudy
2. windspeed
3. hum
4. Weathersit_LightSnow_Rain

**The R2 values are **

R-squared for train data: 85.67
R-squared for test data: 79.76
Mean Squared Error 0.1

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python 

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was done using EDA sample .
- References for data cleanup and visualization used google support...


## Contact
Created by [@githubusername] - @vimalasuchi


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
