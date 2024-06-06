# Dog-vs-Cat-Classification

This project uses the Kaggle API to download and classify images of cats and dogs from a Kaggle competition dataset. The goal is to build a model that can accurately distinguish between images of cats and dogs.


## Table of Contents
Overview
Dataset
Installation
Model
Results


### Overview 
This project leverages deep learning techniques to classify images of cats and dogs. It uses a Convolutional Neural Network (CNN) built with TensorFlow/Keras to achieve this task. The dataset is fetched using the Kaggle API.

### Dataset
The dataset used in this project is the Dogs vs. Cats competition dataset from Kaggle.

### Installation
#### Prerequisites
Python 3.6+
Kaggle API
TensorFlow
Keras
NumPy


### Model
The model is a Convolutional Neural Network (CNN) built using TensorFlow/Keras. The architecture includes multiple convolutional layers followed by max-pooling layers and fully connected layers.

#### Model Architecture
Input: 150x150 RGB images
Convolutional layers
Max-Pooling layers
Fully Connected (Dense) layers
Output: Sigmoid activation for binary classification


### Results
The model achieves an accuracy of 96.2% on the test set.
