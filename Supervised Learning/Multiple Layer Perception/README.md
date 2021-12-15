# Multiple Layer Perception

Because our brain is made up of millions of neurons, a **Neural Network** is basically just a collection of Perceptrons that are linked in various ways and perform different activation functions.

![](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2017/09/Multi-Layer-Perceptron-Neural-Network-Tutorial-Edureka.png)
* Input Nodes – The Input nodes provide information from the outside world to the network and are together referred to as the “Input Layer”.
* Hidden Nodes – The Hidden nodes have no direct connection with the outside world (hence the name “hidden”). They perform computations and transfer information from the input nodes to the output nodes. A Multi-Layer Perceptron has one or more hidden layers.
* Output Nodes – The Output nodes are collectively referred to as the “Output Layer” and are responsible for computations and transferring information from the network to the outside world.

## Steps
* Initialize the weights and bias with small-randomized values.
* Propagate all values in the input layer until output layer(Forward Propagation).
* Update weight and bias in the inner layers(Backpropagation).
* Do it until that the stop criterion is satisfied.

## Data
[CIFAR10 small images classification dataset](https://keras.io/api/datasets/cifar10/)

This is a dataset of 50,000 32x32 color training images and 10,000 test images, labeled over 10 categories. 
The classes are:
* 0 airplane
* 1	automobile
* 2	bird
* 3	cat
* 4	deer
* 5	dog
* 6	frog
* 7	horse
* 8	ship
* 9	truck

## Package 
* [tensorflow](https://www.tensorflow.org)
* [numpy](https://numpy.org)
* [matplotlib.pyplot](https://matplotlib.org/stable/api/_as_gen/matplotlib.pyplot.html)

## Reference
Patrikar, S. (2019, October 1). Batch, Mini Batch & Stochastic Gradient Descent | By Sushant Patrikar | Towards Data Science. Medium. https://towardsdatascience.com/batch-mini-batch-stochastic-gradient-descent-7a62ecba642a.

S. (2017, December 8). Neural Network Tutorial - Artificial Intelligence | Deep Learning | Edureka. Edureka. https://www.edureka.co/blog/neural-network-tutorial/.
