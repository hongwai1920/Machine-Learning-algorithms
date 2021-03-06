# K Nearest Neighbor Image Classifier
The CIFAR-10 dataset consists of 60000 32x32 colour images in 10 classes, with 6000 images per class. There are 50000 training images and 10000 test images.

The dataset is divided into five training batches and one test batch, each with 10000 images. The test batch contains exactly 1000 randomly-selected images from each class. The training batches contain the remaining images in random order, but some training batches may contain more images from one class than another. Between them, the training batches contain exactly 5000 images from each class.

Below is a peek of the CIFAR-10 image dataset. 

<p align="center"> <img  src="https://github.com/hongwai1920/Machine-Learning-algorithms/blob/master/K%20Nearest%20Neighbor%20Image%20Classifier/Images/CIFAR-10.png" width="350" height="350"></p> 

## k_nearest_neighbor.py
The file contains the class KNearestNeighbor with train, predict, compute_distances and predict_labels methods.
Its uses <img src="https://latex.codecogs.com/svg.latex?\ell^2" title="\ell^2" /> distance as metric in classification.

## [k nearest neighbor image classifier.ipynb](https://nbviewer.jupyter.org/github/hongwai1920/Machine-Learning-algorithms/blob/master/K%20Nearest%20Neighbor%20Image%20Classifier/k%20nearest%20neighbor%20image%20classifier.ipynb)
The notebook contains a detailed introduction and imeplementation of K Nearest Neighbor algorithms from k_nearest_neighbor.py.
We also perform a k-fold cross validation on the hyperparameter k to determine the best k that gives the highest accuracy.

The following is the cross validation on k graph (cross validation accuracy against k), which extracted from the notebook k nearest neighbor image classifier.ipynb.

<p align="center"> <img  src="https://github.com/hongwai1920/Machine-Learning-algorithms/blob/master/K%20Nearest%20Neighbor%20Image%20Classifier/Images/cross-validation%20on%20k.png" width="650" height="500"></p> 
