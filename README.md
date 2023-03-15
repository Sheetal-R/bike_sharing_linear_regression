# Bike Sharing - Linear Regression 
# Bike Sharing Assignment


Table of Contents
General Info
Technologies Used
Conclusions
Acknowledgements

## General Info
### Problem Statement
**Required to build a multiple linear regression model for the prediction of demand for shared bikes**

A US bike-sharing provider **BoomBikes** which provides a service where in bikes are made available for shared use to individuals on a short term basis for a price or free. The bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.


Using various meteorological surveys and people's styles, the **BoomBikes** service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors. **BoomBikes** aspires to understand the demand for shared bikes among the people after this ongoing (Covid-19) quarantine situation ends across the nation. 

The company wants to know:

- Which variables are significant in predicting the demand for shared bikes.
- How well those variables describe the bike demands

The management desires to use this understanding to see how exactly the demands vary with different features and update its  business strategy to meet the demand levels and customer's expectations and thus improve its quality of service and profit margin.


### Solution: A jupyter notebook BikeSharing.ipynb that covers the following
- Reading and Understanding the data
- Visualising the Data
- Data Preparation
- Model building and evaluation

## Technologies Used
- numpy
- pandas
- matplotlib.pyplot
- seaborn
- datetime
- sweetviz
- statsmodels
- sklearn

## Conclusions

### Summarization
- All the VIF values and p-values seem to be in the permissible range now. Also the `Adjusted R-squared` value has dropped from `82.5%` with **10 variables** to just `82%` using **9 variables**. This model is explaining most of the variance without being too complex.
- In residual analysis using normal distribution, The error terms are fairly normally distributed and we can surely live with this. Let's now make predictions on the test-set.
- For the model with 9 variables, the r-squared on training and test data is about **82.5% and 79.68%** respectively. The adjusted r-squared on the train set is about is about **82% and 78.7%**.

## Acknowledgements
This project suggested as part of the IIT-B /Upgrad EDG Program
