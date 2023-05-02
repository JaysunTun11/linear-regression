README: Python Implementation of Linear Regression

This implementation is a Python implementation of the linear regression algorithm, which is a commonly used supervised learning technique used for regression tasks. 
Given a set of labeled training data, consisting of instances (or examples) each with a set of features and an associated continuous output label, the goal of linear 
regression is to find a linear function that maps the features to the continuous output labels.

The linear regression algorithm works as follows:

1. Define a hypothesis function that maps the input features to the predicted output label. In linear regression, the hypothesis function is a linear combination of the 
input features, where each feature is multiplied by a corresponding weight parameter.
2. Define a cost function that measures the difference between the predicted output labels and the true output labels in the training data. In linear regression, 
the most commonly used cost function is the mean squared error (MSE).
3. Optimize the weight parameters of the hypothesis function to minimize the cost function using an optimization algorithm such as gradient descent or normal equations.
The output of linear regression is a set of weight parameters that define the linear function that maps the input features to the continuous output label.

Linear regression is useful for many applications, including predicting housing prices, stock prices, and sales figures. However, the quality of the predictions 
obtained depends heavily on the quality of the features used and the assumptions of linearity and independence of the features. Techniques such as regularization and
feature engineering can be used to improve the performance of the linear regression model. This implementation includes the option to use both gradient descent and 
normal equations to optimize the cost function, as well as the ability to visualize the regression line and residuals.
