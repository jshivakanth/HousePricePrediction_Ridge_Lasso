# House Price prediction Assignment
>A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia.
The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.




## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- The company is looking at prospective properties to buy to enter the market. 
- You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.
- The company wants to know:
    - Which variables are significant in predicting the price of a house, and
    - How well those variables describe the price of a house.
- Also, determine the optimal value of lambda for ridge and lasso regression.
- What is the dataset that is being used?
  * train.csv

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->



<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- numpy - version 1.21.6
- pandas - version 1.3.5
- matplotlib - version 3.1.2
- seaborn - version 0.12.0
- sklearn - version 0.0
- statsmodels - version 0.13.2

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Conclusions
- We have finalised a Lasso model with R2 score of 0.88.
- The optimal value of LAMBDA we got in case of Ridge and Lasso is :
    - Ridge - **1.0**
    - Lasso - **0.0001**
The Top predictors which influence the House sale price are :
- OverallQuality
- MSZoning
- GrLivArea
- Neighborhood
- GarageQual
- Heating_Gas
- LandContour



## Acknowledgements
Give credit here.
- This project was inspired by Upgrad tutorial on Advanced Regression
- This project was based on [Upgrad tutorial](https://learn.upgrad.com/course/4431?courseId=26361).



<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->