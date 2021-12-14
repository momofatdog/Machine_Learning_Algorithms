# K-Nearest Neighbors

A k-nearest-neighbor method, abbreviated KNN, is a data categorization strategy that assesses how probable a data point is to belong to one of two groups based on which data points are closest to it. The k-nearest-neighbor technique is an example of a "lazy learner," which means that it does not create a model using the training set until the data set is queried.


<img src="https://cdn.analyticsvidhya.com/wp-content/uploads/2018/08/keylines-clustering-algorithm.png" width="600" height="500" />

## Steps
* Step-1: Select the number K of the neighbors
* Step-2: Calculate the Euclidean distance of K number of neighbors
* Step-3: Take the K nearest neighbors as per the calculated Euclidean distance.
* Step-4: Among these k neighbors, count the number of the data points in each category.
* Step-5: Assign the new data points to that category for which the number of the neighbor is maximum.
* Step-6: Our model is ready.
## Data
**User Dataset**

There is a Car manufacturer company that has manufactured a new SUV car. The company wants to give the ads to the users who are interested in buying that SUV. So for this problem, we have a dataset that contains multiple user's information through the social network. The dataset contains lots of information but the Estimated Salary and Age we will consider for the independent variable and the Purchased variable is for the dependent variable.
* **Estimated Salary** (independent variable)
* **Age** (independent variable)
* **Purchased** (yes/no; dependent variable)


## Package 
I will use the following packages in this project:
* [matplotlib.pyplot](https://matplotlib.org/stable/api/_as_gen/matplotlib.pyplot.html)
* [matplotlib.colors](https://het.as.utexas.edu/HET/Software/Matplotlib/api/colors_api.html)
  * [ListedColormap](https://matplotlib.org/stable/api/_as_gen/matplotlib.colors.ListedColormap.html)
* [numpy](https://numpy.org)
* [pandas](https://pandas.pydata.org)
* [seaborn](https://seaborn.pydata.org)
* [sklearn](https://scikit-learn.org/stable/)
  * [KNeighborsClassifier](https://scikit-learn.org/stable/modules/generated/sklearn.neighbors.KNeighborsClassifier.html)
  * [Confusion Matrix](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.confusion_matrix.html)

## Reference
Python, R. (n.d.). The K-Nearest Neighbors (kNN) Algorithm In Python – Real Python. The k-Nearest Neighbors (kNN) Algorithm in Python – Real Python. https://realpython.com/knn-python/.

K-Nearest Neighbors Algorithm | KNN Regression Python. (2018, August 22). Analytics Vidhya. https://www.analyticsvidhya.com/blog/2018/08/k-nearest-neighbor-introduction-regression-python/.

K-Nearest Neighbor(KNN) Algorithm for Machine Learning - Javatpoint. (n.d.). www.javatpoint.com. https://www.javatpoint.com/k-nearest-neighbor-algorithm-for-machine-learning.
