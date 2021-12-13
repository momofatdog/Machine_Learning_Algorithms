# Decision Trees

Decision Trees (DTs) are a type of non-parametric supervised learning approach that is commonly used for **classification** (Yes/No types) and **regression** (Continuous data types). In this project, I will display the algorithm for classification case and regression case, respectively. The objective is to build a model that predicts the value of a target variable using basic decision rules derived from data attributes. A tree is an example of a piecewise constant approximation.

![DT](https://cdn-images-1.medium.com/max/778/1*OLJWt9hD2zTS-x3gRhYuqg.png)

## Properties
* The tree-structured classifier: Interior nodes contain dataset attributes, branches represent decision rules, and each leaf node provides the results.
* The decisions or tests are made based on the characteristics of the provided dataset. 
* It's a graphical depiction for obtaining all feasible answers to a problem/decision depending on certain parameters. 
* It's termed a decision tree because, like a tree, it starts with the root node and grows into a tree-like structure with additional branches. 
* A decision tree simply asks a question and divides the tree into subtrees based on the answer (Yes/No).

## Data
* **Classification Data**: User Dataset includes information of users from a companies database. We will this dataset for predicting that a user will purchase the company’s newly launched product or not. It contains information about
    * UserID
    * Gender
    * Age
    * EstimatedSalary, \$1000
    * Purchased (Yes/No)
    
* **Regression Data**: Ice cream Dataset The goal of the data is to create a model that could predict the daily revenue in dollars based on the outside air temperature (degC)
    * Temperature
    * Revenue

## Package 
I will use the following packages in this project:
* [matplotlib.pyplot](https://matplotlib.org/stable/api/_as_gen/matplotlib.pyplot.html)
* [numpy](https://numpy.org)
* [pandas](https://pandas.pydata.org)
* [sklearn](https://scikit-learn.org/stable/)
   * [DecisionTreeClassifier](https://scikit-learn.org/stable/modules/generated/sklearn.tree.DecisionTreeClassifier.html?highlight=decision%20tree#sklearn.tree.DecisionTreeClassifier)
   * [DecisionTreeRegressor](https://scikit-learn.org/stable/modules/generated/sklearn.tree.DecisionTreeRegressor.html)

## Reference
R, A. (2021, August 12). The Basics Of Decision Trees. Decision Tree Algorithms - Part 1 | By Arif R | DataDrivenInvestor. Medium. https://medium.datadriveninvestor.com/the-basics-of-decision-trees-e5837cc2aba7.
