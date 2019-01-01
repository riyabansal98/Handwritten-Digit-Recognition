# Handwritten-Digit-Recognition

## Problem Statement:

The problem statement is to classify handwritten digits. The goal is to take an image of a handwritten digit and determine what that digit is. The digits range from zero (0) through nine (9).

## Dataset Used:

The MNIST database (Modified National Institute of Standards and Technology database) is a large database of handwritten digits that is commonly used for training various image processing systems. The database is also widely used for training and testing in the field of machine learning. 
The dataset chosen here contains 42000 samples. 

## Metrics:

We will use the accuracy score to quantify the performance of our model. The accuracy will tell us what percentage of our test data was classified correctly. The accuracy is a good metric choice because it will be easy to compare our model’s performance to that of the benchmark as it uses the same metric. Using KNN, the accuracy came out to be 96%


## Algorithm and Technique Used:

Here KNN algorithm is used for the recoginition of handwritten digits in MNIST dataset.

The algorithm is as follows:
- Determine the parameter K = number of nearest neighbours.
- Calculate the distance between query instance and all the training samples.
- Sort the distance and determine nearest neighbours based on the kth minimum distance.
- Gather the category of nearest neighbours.
- Use simple majority of the category of the nearest neighbours as the prediction value of the query instance. 

## Pros and Cons of KNN Algorithm:

### Pros

- Simple Algorithm - Easy to understand and explain.
- Training Time O(1)
- Non parametric algorithm. Used as a baseline algorithm.

### Cons

- Computationally expensive. 
- High memory requirement.
- Prediction stage might be slow. (With large no. of training samples)
