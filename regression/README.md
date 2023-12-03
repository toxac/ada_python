# Simple Linear Regression

## Key Concepts

### What is it?
Linear regression is a data analysis technique that predicts the value of unknown data by using another related and known data value. It mathematically models the unknown or dependent variable and the known or independent variable as a linear equation.

### Why is it important?
Linear regression models are relatively simple and provide an easy-to-interpret mathematical formula to generate predictions. Linear regression is an established statistical technique and applies easily to software and computing. Businesses use it to reliably and predictably convert raw data into business intelligence and actionable insights. Scientists in many fields, including biology and the behavioral, environmental, and social sciences, use linear regression to conduct preliminary data analysis and predict future trends. Many data science methods, such as machine learning and artificial intelligence, use linear regression to solve complex problems.

### How does it work?
At its core, a simple linear regression technique attempts to plot a line graph between two data variables, x and y. As the independent variable, x is plotted along the horizontal axis. Independent variables are also called explanatory variables or predictor variables. The dependent variable, y, is plotted on the vertical axis. You can also refer to y values as response variables or predicted variables.

### Linear Regression in ML
What is linear regression in machine learning?
In machine learning, computer programs called algorithms analyze large datasets and work backward from that data to calculate the linear regression equation. Data scientists first train the algorithm on known or labeled datasets and then use the algorithm to predict unknown values. Real-life data is more complicated than the previous example. That is why linear regression analysis must mathematically modify or transform the data values to meet the following four assumptions.

**Linear relationship**

A linear relationship must exist between the independent and dependent variables. To determine this relationship, data scientists create a scatter plot—a random collection of x and y values—to see whether they fall along a straight line. If not, you can apply nonlinear functions such as square root or log to mathematically create the linear relationship between the two variables.

**Residual independence**

Data scientists use residuals to measure prediction accuracy. A residual is the difference between the observed data and the predicted value. Residuals must not have an identifiable pattern between them. For example, you don't want the residuals to grow larger with time. You can use different mathematical tests, like the Durbin-Watson test, to determine residual independence. You can use dummy data to replace any data variation, such as seasonal data.

**Normality**

Graphing techniques like Q-Q plots determine whether the residuals are normally distributed. The residuals should fall along a diagonal line in the center of the graph. If the residuals are not normalized, you can test the data for random outliers or values that are not typical. Removing the outliers or performing nonlinear transformations can fix the issue.

**Homoscedasticity**

Homoscedasticity assumes that residuals have a constant variance or standard deviation from the mean for every value of x. If not, the results of the analysis might not be accurate. If this assumption is not met, you might have to change the dependent variable. Because variance occurs naturally in large datasets, it makes sense to change the scale of the dependent variable. For example, instead of using the population size to predict the number of fire stations in a city, might use population size to predict the number of fire stations per person.


## Types of Regression
Some types of regression analysis are more suited to handle complex datasets than others. The following are some examples.

### Simple linear regression
Simple linear regression is defined by the linear function:

$$y = \beta_0 + \beta_1 x + \epsilon$$

β0 and β1 are two unknown constants representing the regression slope, whereas ε (epsilon) is the error term.

You can use simple linear regression to model the relationship between two variables, such as these:

- Rainfall and crop yield
- Age and height in children
- Temperature and expansion of the metal mercury in a thermometer

### Multiple linear regression
In multiple linear regression analysis, the dataset contains one dependent variable and multiple independent variables. The linear regression line function changes to include more factors as follows:

$$y = \beta_0 * x0 + \beta_1 x1 +...+ \beta_n xn+ \epsilon$$


As the number of predictor variables increases, the β constants also increase correspondingly.

Multiple linear regression models multiple variables and their impact on an outcome:

- Rainfall, temperature, and fertilizer use on crop yield
- Diet and exercise on heart disease
- Wage growth and inflation on home loan rates

### Logistic regression
Data scientists use logistic regression to measure the probability of an event occurring. The prediction is a value between 0 and 1, where 0 indicates an event that is unlikely to happen, and 1 indicates a maximum likelihood that it will happen. Logistic equations use logarithmic functions to compute the regression line.

These are some examples:

- The probability of a win or loss in a sporting match
- The probability of passing or failing a test 
- The probability of an image being a fruit or an animal

--------

## Planning

## EDA

## Construction

## Evaluation and Interpretation

-------

## Examples 