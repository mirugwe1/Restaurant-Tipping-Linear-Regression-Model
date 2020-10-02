# Restaurant-Tipping-Linear-Regression-Model
The goal of this project is to build a linear model for predicting the average amount of tip in dollars a waiter is expected to earn from the restaurant given the predictor variables i.e. total bill paid, day, the gender of the customer (sex) time of the party, smoker, and size of the party. And this was achieved through the use of the Linear Regression method.   The dataset of 200 observations and 7 variables was divided into training and testing sets in a ratio of 8:2 respectively. The model was fitted using the lm() function of R on the train set and tested on the testing set using predict() function. And the model fitness was deeply analyzed to understand how well it fits the data.   Using Lasso regularization approach, the model was improved and this helped to identify the most important predictors in estimating the amount of tip received by the waiter. And also an interaction of size and smoker was included in the final model which greatly improved its data fitness.
