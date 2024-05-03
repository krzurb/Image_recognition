Image Recognition

This repository contains an image recognition model trained on the CIFAR-10 dataset.

Author
Author: Krzysztof Urbanowski


OVERVIEW

The Jupyter Notebook file consists of three main sections:

Model Definition Cell:
Contains a list of classes used in the CIFAR-10 dataset and the definition of the Convolutional Neural Network class. Users can modify the architecture of the neural network in this section.

Training Cell:
Allows users to change parameters such as num_epochs, batch_size, and learning_rate if needed. After training, the program prints the accuracy for each class. The pre-trained model is saved as 'saved_model.pth'. This cell doesn't need to be run without changes in the model.

Prediction Cell:
Enables users to make predictions based on input images. Three testing images ('dog.jpg', 'cat.jpg', and 'ship.jpg') are provided in this repository.


USAGE

Modify the model architecture if needed in the Model Definition Cell.

Adjust training parameters if necessary in the Training Cell.

Use the Prediction Cell to make predictions on custom images.


FILES
CIFAR10.ipynb: Jupyter Notebook containing model definition, training, and prediction cells.

saved_model.pth: Pre-trained model saved after training.

dog.jpg, cat.jpg, ship.jpg: Testing images for prediction.

REQUIREMENTS

Python 3.x

PyTorch

torchvision

PIL
