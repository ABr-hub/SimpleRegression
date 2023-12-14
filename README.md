# SimpleRegression
This repository showcases a simple regression problem in PyTorch.

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

In this repository, a sample polynomial regression is showcased, 
illustrating the application of a polynomial function with a degree of 5. 
The specific function to be approximated is defined as follows, providing a 
practical example of how polynomial regression can be utilized to model complex 
relationships in data.

$2 \cdot x + 3 \cdot x^2 + 4 \cdot x^{3} + 5 \cdot x^{4} + 6 \cdot x^{5} +10$

This function can be plotted as follows: \
<img src="https://github.com/ABr-hub/SimpleRegression/blob/dbe142c6ea1086df32fe07c60ed94cfaba4d2512/ressources/SampleRegression_appFunction.png" width=60% height=60%>

It's essential to note that in this sample, the demonstration involves approximating 
a mathematically predefined function. As a result, the data used in this context does 
not exhibit standard deviation, as the focus is on showcasing the polynomial regression's 
ability to accurately capture the predetermined mathematical relationship without inherent 
variability.

The approximation process by the neural network is illustrated below: \
<img src="https://github.com/ABr-hub/SimpleRegression/blob/35fda00c6e2354bc611c8d7d01eb8d8a2ed1c7e7/ressources/Reg1.gif" width=60% height=60%>

---
### Other examples

In the subsequent examples, the same neural network used previously as a function 
approximator is employed for two distinct scenarios. The first case highlights the network's 
ability to approximate an absolute valued function, underscoring the effectiveness of 
polynomial regression in capturing the nuances of non-linear behaviors. Subsequently, 
the neural network is applied to approximate a step function in the second example, demonstrating 
the versatility of polynomial regression in effectively modeling abrupt changes and 
discontinuities within datasets.

<img src="https://github.com/ABr-hub/SimpleRegression/blob/f2f85b85b4e87364faceb033d76aa774c6ec32e7/ressources/AbsReg.gif"  width=43% height=43%/> <img src="https://github.com/ABr-hub/SimpleRegression/blob/6c5ced72b2a999f7156c90600dd3aef5f117fdd0/ressources/StepReg.gif"  width=45% height=45%/>
