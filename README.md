# house price prediction
> A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
- The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.
- Data set used for this project is "train.csv"

## Conclusions
- Though the model performance by Ridge Regression was better in terms of R2 values of Train and Test,  it is better to use Lasso, since it brings and assigns a zero value to insignificant features.
- There are some positive and some negative variables that highly effect the final sales price.
- Positive features: GrLivArea, OverallQual, OverallCond, TotalBsmtSF, GarageArea
- Negative features : PropAge, MSSubClass


## Technologies Used
- pandas
- numpy
- sklearn
- matplotlib
- seaborn

## Acknowledgements
- This project was inspired by and based on (https://learn.upgrad.com/course/3094/segment/29380/175269/538072/2760952).


## Contact
Created by [@ADITHYA1609] - feel free to contact me!