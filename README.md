## Project Goal
This project is to apply linear regression, gradient descent and regularization to tackle the California median house value.

## Introduction
This project has four parts:

* Part I: Getting Oriented
* Part II: Gradient Descent: Linear Regression
* Part III: Prediction
* Part IV: Regularization 

## Dataset
In this project, we will be using a version of the [California Housing Prices Dataset](https://scikit-learn.org/stable/datasets/real_world.html#california-housing-dataset) with additional information.

## Key Findings
Key Findings
* Median income is the strongest predictor
The linear regression model identified median income (MedInc) as the most influential variable in predicting median house value. The coefficient was large and positive, indicating that higher income areas are strongly associated with higher housing prices.

* Population density and housing age have limited impact
Variables such as population, house age, and households showed small coefficients and relatively low impact on housing prices, indicating these features may not be strong predictors in a linear model.

* Model performance is moderate
The R-squared value was around 0.6, suggesting that the linear model explains about 60% of the variance in house prices. This is decent but leaves room for improvement with more complex models or feature engineering.

* Linear assumptions limit accuracy
Visualizations of residuals and predicted vs. actual prices show non-linear patterns, especially in high-price regions. This indicates that a linear regression may not capture the full complexity of the housing market and may benefit from non-linear models like decision trees or gradient boosting.

