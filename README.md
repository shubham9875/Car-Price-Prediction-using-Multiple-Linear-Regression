# Car-Price-Prediction-using-Multiple-Linear-Regression

This repository contains a model of the Car Price Dataset. The dataset contains price data for a number of features present in the car. The aim of this analysis is to build predictive model which can predict the price of cars using feature variables. It will be used by the management to understand how exactly the prices vary with the independent variables. They can accordingly manipulate the design of the cars, the business strategy etc. to meet certain price levels. Further, the model will be a good way for management to understand the pricing dynamics of a new market.

## Problem Statement

A Chinese automobile company Geely Auto aspires to enter the US market by setting up their manufacturing unit there and producing cars locally to give competition to their US and European counterparts. They have contracted an automobile consulting company to understand the factors on which the pricing of cars depends. Specifically, they want to understand the factors affecting the pricing of cars in the American market, since those may be very different from the Chinese market.

## Dataset

The dataset used for this problem statement is Car Price Prediction, which can be downloaded from Kaggle[https://www.kaggle.com/datasets/hellbuoy/car-price-prediction]. The dataset contains 205 rows and 26 columns.

## Files

* Car_Price_Prediction_using_Multiple_Linear_Regression.ipynb: contains jupyter notebook with all the code required to build the model.
* CarPrice_Prediction.csv: CSV File containing the dataset used in this project.
* Data Dictionary- carprices.xlsx: Excel file which will help you to understand every variable in the dataset.
* README.md: This file which contain all the information related to the project.

## Conclusion

I utilized various tools such as the statsmodels.api library and other Python packages to implement a multiple linear regression algorithm. Through this approach, I was able to determine that certain factors, including enginelocation_rear, carwidth, cylindernumber_three, and companyname=BMW, significantly influence the pricing of cars. Based on my analysis, the model achieved an accuracy rate of 78.45% on a test dataset.
