# Gradient Descent

Gradient descent is a popular optimization approach for training machine learning models and neural networks. These models evolve over time with the use of training data, and the cost function inside gradient descent especially functions as a barometer, assessing its correctness with each iteration of parameter changes. The model will continue to change its parameters until the function is near to or equal to zero, at which point it will stop.

![](https://miro.medium.com/max/1200/1*iNPHcCxIvcm7RwkRaMTx1g.jpeg)

## Steps
* Randomly initialize values for the coefficients w and b 
* set MAX_ITER and count = 0
* while count < MAX_ITER,  do coefficient = coefficient — (learning rate * change)
* count += 1


## Data 
I this project, I will use two dataset to fit simple linear regression and multiple linear regreesion respectively. For simple linear regression, I will use each algothrim discussed in the course. For multiple linear regression,   I will utilize SGDRegressor class provided by Scikit-learn API to implement Stochastic Gradient Descent method for regression problems. 

* **Simple Linear regression data**: one predictor and one response
    * This salary data shows the change in salary based on years of experience. Use this dataset to create machine learning models for prediction of salaries of people based on their years of experience.
        * YearsExperience 
        * Salary 
* **Multiple Linear regression data**: 13 predictors and one response
    * The [Boston Housing Dataset](https://www.kaggle.com/prasadperera/the-boston-housing-dataset) is a derived from information collected by the U.S. Census Service concerning housing in the area of Boston MA. 
        * CRIM - per capita crime rate by town
        * ZN - proportion of residential land zoned for lots over 25,000 sq.ft.
        * INDUS - proportion of non-retail business acres per town.
        * CHAS - Charles River dummy variable (1 if tract bounds river; 0 otherwise)
        * NOX - nitric oxides concentration (parts per 10 million)
        * RM - average number of rooms per dwelling
        * AGE - proportion of owner-occupied units built prior to 1940
        * DIS - weighted distances to five Boston employment centres
        * RAD - index of accessibility to radial highways
        * TAX - full-value property-tax rate per \$10,000
        * PTRATIO - pupil-teacher ratio by town
        * B - 1000(Bk - 0.63)^2 where Bk is the proportion of blacks by town
        * LSTAT - % lower status of the population
        * MEDV - Median value of owner-occupied homes in $1000's
        
        
## Package 
I will use the following packages in this project:
* [matplotlib.pyplot](https://matplotlib.org/stable/api/_as_gen/matplotlib.pyplot.html)
* [numpy](https://numpy.org)
* [pandas](https://pandas.pydata.org)
* [sklearn](https://scikit-learn.org/stable/)
  * [SGDRegressor](https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.SGDRegressor.html)

## Reference
Regression Example With SGDRegressor In Python. (n.d.). DataTechNotes: Regression Example with SGDRegressor in Python. https://www.datatechnotes.com/2020/09/regression-example-with-sgdregressor-in-python.html.

Education, I. C. (2020, October 27). What Is Gradient Descent?. What is Gradient Descent? | IBM. https://www.ibm.com/cloud/learn/gradient-descent.


