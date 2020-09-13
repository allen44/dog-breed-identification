# Summary: dog-breed-identification
A notebook for machine learning image recognition model forthe Kaggle competition: https://www.kaggle.com/c/dog-breed-identification/

# Multi-class Classification
This notebook builds and end-to-end multi-class image classifier using TenhsorFlow 2.0 and TensorFlow Hub

##1. Problem
This model attemptst to identify the breed of the dog in a photo.

Application: I want to identify a dog breed when I photograph it with my phone.

##2. Data
The data we're using is from Kaggles's data set. https://www.kaggle.com/c/dog-breed-identification/

##3. Evaluation
The identification is evaluated on Multi Class Log Loss

##4. Features
Some information about the data:

We're dealing with images (unstructured data) so it's probably best that we use deep learning/transfer learning.

There are 120 classes (because there are 120 breeds of dogs)

There are around 10000 images in the training set (these images have labels).

There are around 10000 images in the test set (these images have no labels).
