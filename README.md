# Real Estate Price Prediction
## Problem Statement
Consider a real estate company that has a dataset containing the house prices of unit area in the state of Maryland, USA. It wishes to use the data to optimize the prices based on important factors such housing age, distance to the nearest MRT station, number of convenience stores, latitude and longitude
## Essentially, the company wants —
•	To identify the variables affecting house prices per unit area, 
•	To create a linear model that quantitatively relates house prices with variables such as house age, distance to the nearest MRT station etc
•	To know the accuracy of the model, i.e. how well these variables can predict house prices.
## Business Goal
I am required to model the price of houses of a unit area with the available independent variables. It will be used by the management to understand how exactly the prices vary with the independent variables. They can accordingly manipulate the design of the houses, the business strategy etc. to meet certain price levels. Further, the model will be a good way for management to understand the pricing dynamics of a new market.
## Dataset
The dataset is obtained from Kaggle. It includes just over 414 rows and 8 columns. It has independent features such such house age, distance to the nearest MRT station, numbetr of convenience stores, latitude and longitude. All of these features play a very important roll in our prediction of of target(y).
# Data splitting to training and testing model
sklearn.model_selection is the library use to split our data into training and testing dataset. 
## 80% will be traing data and 20% testing data
# OLS regression results
![olsregression](https://user-images.githubusercontent.com/63025220/93915840-9880cc00-fcd6-11ea-8566-de75dd47278b.PNG)


