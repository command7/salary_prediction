# Salary Prediction using Regression Model

## Description
Machine learning models were trained to predict the salary of an individual using data such
* Miles from metropolis
* Years of experience
* Company that employed him/her
* Type of job
* Degree
* Industry employed in

Miles from metropolis was found to be negatively correlated with salary and years of experience was found to be positively correlated with salary.

Linear Regression model was considered the base line model and training the model with the data provided a Mean Squared Error of 387.
## Models Considered

Model that were considered in this project were

* Decision Tree Regressor
* Ridge Regression
* Lasso Regression
* Stochastic Gradient Descent Regressor

Initially they all seemed to provide the same Mean Squared Error as the Linear Regression. Hence Feature engineering was performed.

## Feature Engineering

Polynomial features to a degree of 2 were added to the data set. After adding these polynomial features, the Mean Squared Error of these models was found to decrease by about 20 units to 366.

## Validation

In order to make sure that the model was not over fitting, cross validation with 5 folds was performed and the outputs provided evidence to confirm that the models were not overfitting.

## Final Model
