# Introduction
# Corn Leaf Health Classification using Neural Networks

The goal of this project is to develop a model that can accurately classify between healthy corn leaves and infected. This classification task is crucial for early detection and effective management of plant diseases, in order to prevent the spreading of the desease.


## Dataset

The dataset used is from kaggle and consists of a 13GB collection of corn leaf images, categorized into healthy and infected classes. Each image varies in size and quality and orientation, presenting a real-world challenge for classification. Since the significant size of the dataset (13GB), we'll explore methods to efficiently handle and process this data, in order to save most space and keep most of the variance of the original dataset.

https://www.kaggle.com/datasets/qramkrishna/corn-leaf-infection-dataset

## Approach

After imported the dataset we will preprocess them in order to help the model in the learning process. After preprocessing we will reduce the dimension of the dataset, thanks to PCA, in order to keep most variance from the original dataset. With our reduced dataset we will build from scratch a simple Neural Network with 3 hidden layer utilizing pytorch and we will evaluate the performance.
