# House-Price-Prediction Case Study (Lasso and Ridge related exercise)

> A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.
> The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

## Table of Contents
* [General Info](#general-info)
* [Dataset Used](#dataset-used)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

## General Information
- Business Goal is to build a model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.


## Dataset Used
> Files used in this Case Study are provided from Upgrad team
 - houserpricepred_train.csv.
 - Data_Dictionary.xlsx --> data dictionary file has description of all columns i.e. meaning of these variables mentioned in houserpricepred_train.csv


## Technologies Used
- Python Library - version 3.0
- Jupyter Notebook - <DineshRawat_House_Price_Prediction_CS.ipynb>
- CSV file
- Excel file


## Conclusions
- Though the model performance by Ridge Regression was better in terms of R2 values of Train and Test, it is better to use Lasso, since it brings and assigns a zero value to insignificant features, enabling us to choose the predictive variables.
- It is always advisable to use simple yet robust model. Equation can be formulated using the features and coefficients obtained by Lasso.
- Final Inference:
- The higher values of positive coeeficients suggest a high sale value.
- The higher values of negative coeeficients suggest a decrease in sale value.
- So, when the market value of the property is lower than the Predicted Sale Price, its the time to buy.



## Contact
Created by [@githubusername] - feel free to contact me!
