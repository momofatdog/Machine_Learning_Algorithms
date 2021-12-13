# Logistic Regression
Linear Regression is a popular supervised Machine Learning approach for forecasting continuous data. Logistic Regression, on the other hand, is a supervised Machine Learning technique that is essentially useful in binary classification (separating discreet values). 
By computing the likelihood of each member of the set, Logistic Regression is used to classify items of a set into two categories (binary classification).

![](https://miro.medium.com/max/1838/1*dm6ZaX5fuSmuVvM4Ds-vcg.jpeg)

## Steps
In logistic regression, we decide a probability threshold. If the probability of a particular element is higher than the probability threshold then we classify that element in one group or vice versa.
* Randomly select x, y from the training data.

* Feed-Forward into the neural network

* Updates weights and bias with learning rate 
    
* Repeat the above three steps until desired loss in-sample is reached or a maximimum number of steps is reached.

## Data: Pima Indians Diabetes Database
The National Institute of Diabetes and Digestive and Kidney Diseases provided this data. The goal of this dataset is to diagnose whether a patient has diabetes using diagnostic metrics provided in the collection. All of the patients at this clinic are Pima Indian women who are at least 21 years old. There are various medical predictor factors in the dataset, as well as one  binary target variable, **Outcome**. And the predictor variables are:
* Pregnancies
* Glucose
* BloodPressure
* SkinThickness
* Insulin
* BMI
* DiabetesPedigreeFunction
* Age

## Package 
I will use the following packages in this project:
* [matplotlib.pyplot](https://matplotlib.org/stable/api/_as_gen/matplotlib.pyplot.html)
* [numpy](https://numpy.org)
* [pandas](https://pandas.pydata.org)
* [sklearn](https://scikit-learn.org/stable/)

## Reference
Mondal , S. (2020, December 1). Linear Vs Logistic Regression | Linear And Logistic Regression. Analytics Vidhya. https://www.analyticsvidhya.com/blog/2020/12/beginners-take-how-logistic-regression-is-related-to-linear-regression/.
