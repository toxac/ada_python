# Regularization In Multiple Regression

During the Machine Learning model building, the Regularization Techniques is an unavoidable and important step to improve the model prediction and reduce errors. This is also called the Shrinkage method. Which we use to add the penalty term to control the complex model to avoid overfitting by reducing the variance.

reference:
[https://aunnnn.github.io/ml-tutorial/html/blog_content/linear_regression/linear_regression_regularized.html](https://aunnnn.github.io/ml-tutorial/html/blog_content/linear_regression/linear_regression_regularized.html)

----------

The too many parameters/attributes/features along with data and those permutations and combinations of attributes would be sufficient, to capture the possible relationship within dependent and independent variables.


## The Need for Regularization
Unlike polynomial fitting, it’s hard to imagine how linear regression can overfit the data, since it’s just a single line (or a hyperplane). One situation is that features are correlated or redundant.

Suppose there are two features, both are exactly the same, our predicted hyperplane will be in this format:

$$y^ = w0 + w1x1 + w2x2$$

