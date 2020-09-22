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
The p value of all the features is 00.00 and less than 0.05 which mean all the variables or features are important
The sign of regression coefficient tells you whether there's positive or negative correlation between each independent variable and the dependent variable. Positive coefficient indicates as the value of the independent variable increases, the mean of the dependent varaiable also incresases and a negative cofficient indicates as the the value of the independent variable increases, the value of the dependent varaiable decreases
R-squared is always between 0-100%]
# Risidualm analysis of trained data
My R2_Score is above 50% which makes it good
## Error term
![error term](https://user-images.githubusercontent.com/63025220/93920017-902b8f80-fcdc-11ea-99dc-d2c0ec94c578.PNG)
Error term is normally distributed, it indicates the assumption on the linear model is fulfilled
## Making prediction on final score
The table shows the actual value and the predicted value of the test values of y
![Capture1](https://user-images.githubusercontent.com/63025220/93920765-9ff7a380-fcdd-11ea-92e7-b17f3fb4cbd2.PNG)
The graph shows the plot of the actual vs the predicted values of y-test






