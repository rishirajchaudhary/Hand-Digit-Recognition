# Handwritten Digit Recognition using Artificial Neural Networks
This is a project on handwritten digit recognition using artificial neural networks (ANN). The goal is to train an ANN to recognize the digits from 0 to 9 based on their images.

# Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

# Prerequisites
- Python 3
- NumPy
- Matplotlib
- scikit-learn
- Tensorflow
- Keras

# Dataset
The dataset used in this project is the MNIST dataset. It contains 60,000 training images and 10,000 test images of handwritten digits. You can download the dataset from here.

After downloading the dataset, extract the files and place them in a folder named data in the project directory.

# Preprocessing the Data
Before training the ANN, the data needs to be preprocessed. This involves flattening the 28x28 pixel images into a 1D array of length 784 and scaling the pixel values to be between 0 and 1.
