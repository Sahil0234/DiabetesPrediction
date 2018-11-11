# simple-linear-regression-using-python-only

This is a simple but robust linear regression model from scratch in python and is used to predict Blood Sugar of Diabetes Patient from their BMI data.


Data taken from http://www4.stat.ncsu.edu/~boos/var.select/diabetes.tab.txt is showing Blood Sugar (in mg/l) of 442 diabetes patient with 10 baseline variables, age, sex, body mass index, average blood pressure, and six blood serum measurements

Linear Regression model was built from scratch which involves:

Fitting data around straight line equation y = mx+b

Computing errors via Square of errors (y_predicted - y)^2

Minimizing Errors using partial derivatives aka Gradient Descent

Computing new m & b by using Gradient Descent with Learning Rate over many iterations

Using this new m & b to predict Blood Sugar of sample/test data of BMI
