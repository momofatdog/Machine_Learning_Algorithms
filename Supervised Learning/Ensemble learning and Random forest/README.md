# Ensemble learning and Random forest

## Bagging Ensemble Learning
Bagging, also known as Bootstrap Aggregating. Bagging derives its name from the fact that it combines Bootstrapping and Aggregation into a single ensemble model. Multiple bootstrapped subsamples are drawn from a sample of data. On each of the bootstrapped subsamples, a Decision Tree is created. Following the formation of each subsample Decision Tree, an algorithm is used to aggregate across the Decision Trees to build the most efficient predictor. 
![](https://miro.medium.com/max/1400/0*PBGJw23ud8Sp7qO4.)

* Bootstrap samples of the training dataset.
* Unpruned decision trees fit on each sample.
* Simple voting or averaging of predictions.


## Random Forest
The random forest algorithm is a supervised classification algorithm. This algorithm, as the name implies, creates the forest with plentiful trees. In general, the more trees there are in a forest, the more robust it appears. Similarly, with the random forest classifier, the larger the number of trees in the forest, the better the accuracy outcomes.

## Data
There are 270 observations and 5 variables in the heart disease data. The binary categorize response variable "heart disease" specifies whether or not an individual has heart disease. Other risk factors for heart disease include:
* Age
* Sex
* Blood Pressure
* cholestrol

## Package 
I will use the following packages in this project:
* [matplotlib.pyplot](https://matplotlib.org/stable/api/_as_gen/matplotlib.pyplot.html)
* [numpy](https://numpy.org)
* [pandas](https://pandas.pydata.org)
* [seaborn](https://seaborn.pydata.org)
* [sklearn](https://scikit-learn.org/stable/)
  * [RandomForestClassifier](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html)
  * [BaggingClassifier](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.BaggingClassifier.html)
