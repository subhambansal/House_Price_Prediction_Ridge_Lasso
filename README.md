# Model Building for Surprise_Housing_Assignment

A US-based housing company named Surprise Housing has decided to enter the Australian market. 
The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price.
For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.
The company is looking at prospective properties to buy to enter the market. 
You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

The company wants to know:
- Which variables are significant in predicting the price of a house, and
- How well those variables describe the price of a house.

### Business Goal :

You are required to model the price of houses with the available independent variables.
This model will then be used by the management to understand how exactly the prices vary with the variables.
They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns.
Further, the model will be a good way for management to understand the pricing dynamics of a new market.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
> Business Problem:
You are required to model the price of houses with the available independent variables.
This model will then be used by the management to understand how exactly the prices vary with the variables.
They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns.
Further, the model will be a good way for management to understand the pricing dynamics of a new market.

> The company wants to know:
- Which variables are significant in predicting the price of a house
- How well those variables describe the price of a house

> Solution Stratgy: 
Divided analysis in below mentioned border catogry

### The steps to be followed in this exercise are as follows:
#### Data EDA
#### Data Cleaning 
#### Data Visualization
#### Data Preparation
#### Train Test Split
#### Recursive feature elimination (RFE)
#### Model Building and Evaluation

## Conclusions
- The optimal lambda value in case of Ridge and Lasso is as below:
    - Ridge - 2
    - Lasso - 0.0001

- Also, since Lasso helps in feature reduction (as the coefficient value of one of the feature became 0), Lasso has a 
  better edge over Ridge.
  
- Hence based on Lasso, the factors that generally affect the price are the Zoning classification, Living area
  square feet, Overall quality and condition of the house, Foundation type of the house, Number of cars that can be 
  accomodated in the garage, Total basement area in square feet and the Basement finished square feet area 

## Technologies Used
-  Jupyter notebook as IDE for pyton 3 
-  library - Pandas,Numpy,Matplotlib,seaborn,plotly,statsmodels and sklearn

## Acknowledgements
Give credit here.
- This project was inspired by Upgard Learning

## Contact
contributors 
Subham Bansal [@subhambansal] - contact er.subhambansal@gmail.com

## License
This project is open source available for study