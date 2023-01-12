# End-end-end Multi-Class Dog Classification

This notebook builds an end-to-end multi-class image classifier using TensorFlow 2.0 and TensorFlow Hub.

## 1. Problem

Identifying the breed of a dog given an image of a dog.

When i'm sitting at the cafe and I take a photo of a dog , I want to know what breed of dog it is.


## 2. Data

The data we're usiing is from Kaggle's dog breed 

https://www.kaggle.com/competitions/dog-breed-identification/data

## 3. Evaluation

The evaluation is a file with prediction probabilities for each dog breed of each test image.

https://www.kaggle.com/competitions/dog-breed-identification/overview/evaluation

# 4. Features

Some information about the data:
* We're dealing with images (unstructured data) so it's probably best we use deep learning/transfer learning.
* There are 120 breeds of dogs (this means there are 120 different classes).
* There are around 10,000+ images in the training set (these images have labels)
* There are around 10,000+ images in the test set )these images have no labels, because we'll want to predict them)

![IMG](https://github.com/redrum88/Machine_Learning_and_Data_Science/blob/0e349fdf1c83867ff64bf468e6a5ae7b08c24280/dog-vision/dog-vision-kaggle.jpg?raw=true)
