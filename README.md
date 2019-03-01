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

## Baseline Model used

* Linear Regression

## Models Considered

Model that were considered in this project were

* Gradient Boosting Regressor
* Random Forest Regressor

## Cross Validation

In order to make sure that the model was not over fitting, cross validation with 5 folds was performed. The results were
* The Gradient Boosting Regressor was found to have a mean MSE 356
* Random Forest Regressor was found to have a mean MSE of 366.

## Final Model

Gradient Boosting Regressor was the final model with a Mean Squared Error of 356.
