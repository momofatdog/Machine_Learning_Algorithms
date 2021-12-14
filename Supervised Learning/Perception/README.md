# Perception
The earliest and most basic model of artificial neural networks is a single-layer perceptron. It's also known as a feed-forward neural network. The single-layer perceptron (SLP) operates on the basis of threshold transfer between nodes.

![](https://static.javatpoint.com/tutorial/tensorflow/images/single-layer-perceptron-in-tensorflow2.png)

* Because there is no a priori information linked with the nodes, the weights allocated to each input node in a single layer perceptron are assigned at random. 
* In addition, a threshold value is assigned at random. 
* SLP now adds all of the weights that have been submitted, and if the sums are more than the threshold, the network is activated. 
* The model is successful if the computed value matches the intended value. 
* If it is not, the error must be determined and the weights must be modified again because there is no back-propagation mechanism involved.

## Data: Banknote Dataset
The Banknote Dataset involves predicting whether a given banknote is authentic given a number of measures taken from a photograph.

It is a binary (2-class) classification problem. The number of observations for each class is not balanced. There are 1,372 observations with 4 input variables and 1 output variable. The variable names are as follows:

* Variance of Wavelet Transformed image (continuous).
* Skewness of Wavelet Transformed image (continuous).
* Kurtosis of Wavelet Transformed image (continuous).
* Entropy of image (continuous).
* Class (0 for authentic, 1 for inauthentic).


## Package 
I will use the following packages in this project:
* [matplotlib.pyplot](https://matplotlib.org/stable/api/_as_gen/matplotlib.pyplot.html)
* [numpy](https://numpy.org)
* [pandas](https://pandas.pydata.org)
* [seaborn](https://seaborn.pydata.org)
* [sklearn](https://scikit-learn.org/stable/)
  * [Perceptron](https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.Perceptron.html)
  * [GridSearchCV](https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.GridSearchCV.html)
  * [cross_val_score](https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.cross_val_score.html)
  * [RepeatedStratifiedKFold](https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.RepeatedStratifiedKFold.html)

## Reference
Baser, A. (2020, May 21). The Perceptron Algorithm for Binary Classification | By Aditya Baser | Analytics Vidhya | Medium. Medium. https://medium.com/analytics-vidhya/the-perceptron-algorithm-for-binary-classification-ab65aaf237d7.

Brownlee, J. (2020, December 10). Perceptron Algorithm for Classification In Python - Machine Learning Mastery. Machine Learning Mastery. https://machinelearningmastery.com/perceptron-algorithm-for-classification-in-python/.
