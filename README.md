# Forecasting with Big Data
This repository demonstrates the use of linear regression for forecasting with big data in Python. Also, we compare different packages for running the linear regression and summarize the advantages and disadvantages for each package in this study.

## Data Source:
The data set is a industry panel data that records the product prices, sales, company assets, liabilities, industry concentraction, etc by quarters. Total of 391469 observations in the data set. The varaible for prediction is sales. In this exercise, we demonstrate a simple multiple linear regression for forcasting sales based on the features used for training the model. 

## Linear Regression Model:
Many data scientists use linear regression as the starting point of many statistical modeling and predictive analysis project. The importance of fitting a linear model to a large data set cannot be overstated. "Linear" term in the linear regression model refers to the coefficients, and not the degree of the features. Compare to more complex machine learning models (such as random forest, XGBoost, neural network, etc), linear regression model is more interpretable and uses less computational power (relative faster).

## Packages:
In this repository, we use 4 different Python packages for running the linear regression model on the same data set. The purpose for this exercise has two,

1. Demonstrates the use of different packages for the same task.
2. Compare the performance of each method on Big Data set.

Here is a list of methods we cover in this study:

|  Package  |  Method  |  Resource  |
|  :---:  |  :---:  |  :---:  |
|  Scipy  |  Stats.linregress()  |  https://docs.scipy.org/doc/numpy-1.13.0/reference/generated/numpy.polyfit.html  |
|  Numpy  |  numpy.linalg.lstsq()  |  https://docs.scipy.org/doc/numpy-1.13.0/reference/generated/numpy.linalg.lstsq.html#numpy.linalg.lstsq  |
|  Statsmodels  |  Statsmodels.OLS()  |  https://www.statsmodels.org/dev/index.html  |
|  Scikit Learn  |  sklearn.linear_model.LinearRegression()  |  https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LinearRegression.html  |

