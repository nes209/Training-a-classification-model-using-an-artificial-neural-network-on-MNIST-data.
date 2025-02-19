#  Train a classification model using an artificial neural network on MNIST data.

## Project Description: 
This project uses an artificial neural network built using the TensorFlow library to train a classification model on the MNIST dataset.
The MNIST dataset contains images of handwritten numbers (from 0 to 9) and is commonly used to test deep learning models in classification.
The model is designed as a neural network with multiple Dense layers to accurately classify these numbers.

## Project objective:
* Train a classification model using an artificial neural network on MNIST data.
* Apply deep learning techniques to classify handwritten images into categories ranging from 0 to 9.
* Using ReLU and Softmax distribution as activation functions within the model.
* Evaluating the model performance using test accuracy and post-training loss.

## Contents:

1- Download MNIST dataset.

2- Prepare data to normalize images (convert values ​​to [0, 1] range).

3- Build and train an artificial neural network model.

4- Use Dense and Flatten layers to build the model.

5- Evaluate model performance on test data.

## Main steps performed:

1- Importing necessary libraries like TensorFlow and MNIST.

2- Loading and normalizing the data.

3- Building a neural network model using Sequential.

4- Adding a Flatten layer to convert images from 2D to 1D.

5- Adding two Dense layers with ReLU activation functions.

6- Adding an output layer using Softmax to classify between 10 classes.

7- Aggregating the model using Adam optimizer and categorical_crossentropy as a loss function.

8- Training the model using training data for 5_epochs.

9- Evaluating the model on the test data and measuring the accuracy and loss.

## Outputs:

* The model accuracy (Accuracy) and loss (Loss) are printed on the test data.
* The final output shows Test Accuracy and Test Loss which show how well the model classifies handwritten digits.


## Techniques used:

* TensorFlow: A deep learning library for building and training models.
* MNIST: A benchmark dataset for training handwritten digit recognition models.
* ReLU and Softmax: Activation functions used in neural layers to speed up the training and classification process.
