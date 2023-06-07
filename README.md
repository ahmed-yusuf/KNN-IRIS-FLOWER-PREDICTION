# KNN-IRIS-FLOWER-CLASSIFICATION
Makes prediction based on the iris dataset to train a KNN model to discover the type of flower 
Machine Learning Project : Iris-flower-classification
This program applies basic machine learning (classification) concepts on Fisher's Iris Data to predict the species of a new sample of Iris flower.

Software and Libraries

* Python 3.6.0
* Panda
* Numpy
* scikit-learn

## Introduction
The dataset for this project originates from the UCI Machine Learning Repository. The Iris flower data set or Fisher's Iris data set is a multivariate data set introduced by the British statistician and biologist Ronald Fisher in his 1936 paper The use of multiple measurements in taxonomic problems as an example of linear discriminant analysis.

The data set consists of 150 rows and 5 columns which consists of 50 samples from each of three species of Iris (Iris setosa, Iris virginica and Iris versicolor) . Four features were measured from each sample (in centimetres):

* Sepal Length
* Sepal Width
* Length of the petals
* Width of the petals
* Species

## Working of the KNN(K Nearest Neighbour)
The program takes data from the load_iris() function available in sklearn module.

The dataset is then being processed before it is being fed into the machine learning model

Four features of the sample are used as X(independent variable) and the species column is used as y(dependent variable) in which prediction about the species of the flower is being made

The program then divides the dataset into training and testing samples in 70:30 ratio randomly using train_test_learn() function available in sklearn module.

The training sample space is used to train the program and predictions are made on the testing sample space.

The model is then being evaluated using the Sci-kit learn evaluation metrics

Accuracy score
Confusion Matrix
Classification Report
