# MSDS-422-Assignment-2---Evaluating-Linear-Models
# Boston Housing Study

This project using SciKit Learn Machine Learning methods to determine the best fit for a linear model. The exercise uses the Boston housing data from: David A. Belsley, Edwin Kuh, and Roy E.Welsch. 'Regression Diagnostics: Identifying Influential Data and Sources of Collinearity.'
Background Materials

All explanatory variables (with the exception of neighborhood) and all 506 census tract observations from the Boston Housing Study.

# Response variables
(1) the median value of homes in thousands of 1970 dollars or 
(2) the log median value of homes in thousands of 1970 dollars

# The following regression methods were used for comparision.
linear regression
ridge regression
lasso regression
elastic net

# Evaluation
Evaluate these methods within a cross-validation design, using root mean-squared error (RMSE) as an index of prediction error.
Python Scikit Learn should be your primary environment for conducting this research.

# Management Questions to Answer
Advising a real estate brokerage firm in its attempt to employ machine learning methods. The firm wants to use machine learning to complement conventional methods for assessing the market value of residential real estate.

Of the modeling methods examined in your study, which would you recommend to management, and why?

# Results and Recommendations
The results from the 10-fold cross-validation in standardized units informs us that both the Linear and Ridge regression models performed the best with 0.50 and 0.50, respectively, under the root mean-squared error metric. Elastic Net regression model coming in next with a reporting 0.52 root mean-squared error metric and Lasso regression model taking last place with a root mean-squared error of 0.54. Therefore, I recommend from the regression models presented the Linear regression model using the log mean home market valuation for further valuation endeavors until other methods can be explored and compared.


Python Programming
Python packages: matplotlib, numpy, os, pandas, and seaborn
Jupyter Notebook
Python Code

# Programming Resources
A detailed example shows how to evaluate alternative regressors within a cross-validation design:  That is example is entitled "Regression Examples: Predicting Sales" under Technology Resources.
