# Handwritten-digt-recognition
handwritten digit recognition using MNIST dataset and Tensorflow to train a model

## Dataset used
For this project I used the MNIST dataset. It is freely available on the Internet.

## Requirements
1. Python 3
2. Sklearn
3. OpenCV
4. numpy
5. Jupyter-Notebook

## Training CNN model


## Digit recognition using OpenCV
<b>untitled.ipynb</b> - This is a python notebook for recognising handwritten digit in images using OpenCV .This file is using trained CNN model.

## Model Architecture

The neural network model used in this project consists of a sequence of layers:

* Input layer: This layer receives the input image, which is a 28x28 pixel grayscale image.
* Flatten layer: This layer converts the 2D image data into a 1D array, which can be processed by the following layers.
* Dense layer: This is a fully connected layer with 128 units and ReLU activation.
* Output layer: This layer has 10 units, one for each possible digit (0-9), and uses softmax activation to output a probability distribution over the possible digits. The model is trained using the Adam optimizer and categorical cross-entropy loss. The training process is run for 5 epochs with a batch size of 32.

## How to use these projects
You can use these projects direct opening the particular python notebook <b>untitled.ipynb</b>.
