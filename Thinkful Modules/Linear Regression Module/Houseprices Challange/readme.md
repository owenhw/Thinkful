# Houseprices Linear Regression
Supervised Learning Challenge

The well know Ames Houseprices data set is widely used for learning and demonstration purposes. I will use this data set to demonstrate my ability to use the Python data stack for linear regression.

## Data set

This data set was accessed via Kaggle and contains information about houses sold in Ames Iowa between 2006 and 2010. More information about this data set including the data dictionary can be found here: https://www.kaggle.com/c/house-prices-advanced-regression-techniques/overview

This data set was compiled by Dean De Cock and the original publication can be found here: http://jse.amstat.org/v19n3/decock.pdf

## Objective

To create a machine learning model that will predict the saleprice of a house based upon our data set. This is an illustrative example to demonstrate my ability to work with data and produce a viable model.

This model likely would not generalize because this data set is limited to houses in a specific municipality and time frame.

However the general principals of this exercise should generalize. If one were to collect or find new data using the same variables this model could presumably be retrained on the new data. This would provide valuable insight to a variety of stakeholders such as an individual trying to decide how to price their home, or a new home buyer trying to access how much they could expect to pay.


## Challenges Within the Data set

The most significant challenge in this data set will be multicollinearity. Several of the variables such as the square footage of the garage and the number of cars the garage has capacity for are strongly correlated. This will make feature selection difficult.
