# Neural_Collaborative_Filtering

## Introduction:

Neural Collaborative filtering is a Deep Learning based solution that uses the flexibility, complexity, and non-linearity of Neural Networks to build a recommender system.
NCF combines non-linearity from Neural Networks with Matrix Factorization. It replaces the user-item inner product with a neural architecture to learn a deeper understanding between users and items.

See the original paper for more details:
https://arxiv.org/abs/1708.05031

## Data:

The dataset contains a set of movie ratings from the MovieLens website, a movie recommendation service.

https://grouplens.org/datasets/movielens/latest/ 

## Requirements:

```pandas:``` Data analysis and manipulation tool.

```Numpy:``` Numerical analysis library.

```scikit-learn:``` Machine Learning library.

```string:``` Common string operations module.

```re:``` This module provides regular expression matching operations.

```keras:``` Open-source software library that provides a Python interface for artificial neural networks. Keras acts as an interface for the TensorFlow library

## First part:

After preparing the data and transforming it into the tensor format required by Keras, a first model is created. This first version uses user IDs and movie ratings as inputs following the paper's architecture.

## Second part:

In this part, a second version of the model is defined using the previous network structure. The new model includes movie features as product features input, which are mostly used in Content-Based methods. The result is a hybrid recommendation system.
