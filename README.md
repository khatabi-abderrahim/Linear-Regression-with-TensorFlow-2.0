# Linear-Regression-with-TensorFlow-2.0

In this project, we’re going to use TensorFlow 2.0-compatible code to train a linear regression model. Linear Regression is a very common statistical method that allows us to learn a function or relationship between a dependent variable and one or more independent variables. The dependent variable is also called a label and independent variables are called features.
Brief Summary of Linear Regression
Linear Regression is a very common statistical method that allows us to learn a function or relationship from a given set of continuous data. For example, we are given some data points of x and corresponding y and we need to learn the relationship between them that is called a hypothesis.

In case of Linear regression, the hypothesis is a straight line, i.e,
 h(x) = wx + b 
Where w is a vector called Weights and b is a scalar called Bias. The Weights and Bias are called the parameters of the model.
If you want to run the existing code (written in version 1.x) with version 2.0, you have two options:
Run your TensorFlow 2.0 installation in version 1.0 mode by using the below two lines of code:

import tensorflow.compat.v1 as tf
