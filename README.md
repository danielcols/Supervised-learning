# credit-risk-classification

## Purpose
A supervised learning model is created that predicts loan defaults based on a variety of factors including loan size, interest rate, income and past derogatory marks.

## Tools
Pandas is used to import and structure the data while Sklearn is used to build, run and evaluate the model. The data is split into a test and train set, and a logistic regression model is fit to the training data. Predictions are made using the testing data, and various accuracy scores as well as a confusion matrix are generated to evaluate the validity of the model. Finally, the RandomOverSampler method is used to balance the highly disproportionate ratio of output values.

## Results
Two models are made and evaluated in this project. Both are linear regression models with the same solver, but the data that goes into each model is different.
