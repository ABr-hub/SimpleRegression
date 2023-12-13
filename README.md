# SimpleRegression
This repo showcases a simple regression problem in PyTorch

---
### Regression

Regression is a statistical method used for modeling the relationship between a 
dependent variable and one or more independent variables. The goal of regression 
analysis is to understand and quantify the extent to which changes in the 
independent variables are associated with changes in the dependent variable. 
Linear regression, the most common form, assumes a linear relationship between 
the variables, while other types, such as polynomial regression or multiple 
regression, account for more complex relationships or involve multiple predictors. 
Regression analysis is widely employed in various fields, including economics, 
finance, biology, and machine learning, to make predictions, understand patterns, 
and uncover underlying relationships in data.

<img src="https://github.com/ABr-hub/SimpleRegression/blob/cb96b20a1bcd329a19b68f9e23c0e0e907db0c62/ressources/SampleRegression.png" width=60% height=60%>

---
### Sample polynomial regression / function approximation

In this repo a samlpe polynomial regression is demonstrated.
The function to approximate is of degree 5 and defined as follows:

$2 \cdot x + 3 \cdot x^2 + 4 \cdot x^{3} + 5 \cdot x^{4} + 6 \cdot x^{5} +10$

This function can be plotted as follows:

<img src="https://github.com/ABr-hub/SimpleRegression/blob/dbe142c6ea1086df32fe07c60ed94cfaba4d2512/ressources/SampleRegression_appFunction.png" width=60% height=60%>

The approximation process by the neural network is illustrated below:

<img src="https://github.com/ABr-hub/SimpleRegression/blob/35fda00c6e2354bc611c8d7d01eb8d8a2ed1c7e7/ressources/Reg1.gif" width=60% height=60%>

