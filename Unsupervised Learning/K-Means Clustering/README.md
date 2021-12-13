# K-Means Clustering and PCA¶
Principal component analysis (PCA) is a widely used statistical technique for unsupervised dimension reduction. K-means clustering is a commonly used data clustering for performing unsupervised learning tasks. It is common practice to do PCA (principal component analysis) prior to running a clustering algorithm (such as k-means). It is thought to enhance clustering outcomes in practice (noise reduction).

<img src="https://novilabs.com/wp-content/uploads/2020/08/principal-component-analysis-and-clustering-on-a-2-D-plane.png" width="600" height="400" />

We'll utilize k-means clustering, a basic segmentation approach that separates the dataset into a predetermined number of groups. Following the selection of the number of clusters, each cluster is assigned a seed value, or set of starting points. Once the initial seeds have been drawn, each data point is assigned to the closest seed based on proximity. The centroid for each seed is calculated next, which is defined as the geometrical center of the data points allocated to each seed. The preceding stages are then repeated until the system converges and we achieve a clustering solution in which the cluster centroids can no longer be changed.

## How to find the Optimal Number of Clusters?
* The Elbow Method
* Silhouette analysis

## Data
The Wheat Seeds Dataset involves the prediction of species given measurements of seeds from different varieties of wheat.

It is a multiclass (3-class) classification problem. The number of observations for each class is balanced. There are 210 observations with 7 input variables and 1 output variable. The variable names are as follows:

* Area.
* Perimeter.
* Compactness
* Length of kernel.
* Width of kernel.
* Asymmetry coefficient.
* Length of kernel groove.
* Class (1, 2, 3).

## Package 
I will use the following packages in this project:
* [matplotlib.pyplot](https://matplotlib.org/stable/api/_as_gen/matplotlib.pyplot.html)
* [numpy](https://numpy.org)
* [pandas](https://pandas.pydata.org)
* [sklearn](https://scikit-learn.org/stable/)
  * [KMeans](https://scikit-learn.org/stable/modules/generated/sklearn.cluster.KMeans.html)
  * [StandardScaler](https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.StandardScaler.html)
  * [silhouette_samples](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.silhouette_samples.html)
  * [silhouette_score](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.silhouette_score.html) 
* [ mpl_toolkits](https://matplotlib.org/2.2.2/mpl_toolkits/index.html)

## Reference

Dabbura, I. (2020, August 10). K-means Clustering: Algorithm, Applications, Evaluation Methods, And Drawbacks | By Imad Dabbura | Towards Data Science. Medium. https://towardsdatascience.com/k-means-clustering-algorithm-applications-evaluation-methods-and-drawbacks-aa03e644b48a.

J. Garbade, D. M. (2018, September 12). Understanding K-means Clustering In Machine Learning | By Dr. Michael J. Garbade | Towards Data Science. Medium. https://towardsdatascience.com/understanding-k-means-clustering-in-machine-learning-6a6e67336aa1.

A Guide To Principal Component Analysis (PCA) for Machine Learning. (n.d.). A Guide to Principal Component Analysis (PCA) for Machine Learning. https://www.keboola.com/blog/pca-machine-learning.

