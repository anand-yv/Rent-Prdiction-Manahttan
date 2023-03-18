# Predicting Manhattan Rent with Linear Regression
## Introduction
This repository focuses on the development of a linear regression model to predict rental costs in Manhattan using data obtained from StreetEasy. The dataset can be accessed on [Kaggle](https://www.kaggle.com/zohaib30/streeteasy-dataset) or dowloaded directly from this repository.
## Exploratory Visualizations

<img src="https://github.com/anand-yv/Rent-Prdiction-Manahttan/blob/main/Rent%20Prediction%20Manhattan/Images/hists.png" width="600" height="600">

---

<img src="https://github.com/anand-yv/Rent-Prdiction-Manahttan/blob/main/Rent%20Prediction%20Manhattan/Images/boxplot.png" width="600" height="600">

--- 

<img src="https://github.com/anand-yv/Rent-Prdiction-Manahttan/blob/main/Rent%20Prediction%20Manhattan/Images/scatter.png" width="600" height="600">

## Methods and Results
The model was developed with Scikit-Learn's [LinearRegression](https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LinearRegression.html). Features were selected based on correlation with rent and absence of multicollinearity. The square footage of the rental unit was the single best predictor of rent, with an R-squared value of .74:

<img src="https://github.com/anand-yv/Rent-Prdiction-Manahttan/blob/main/Rent%20Prediction%20Manhattan/Images/equation.png" width="400" height="200">
