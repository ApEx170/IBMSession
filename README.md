# IBMSession


Sure, here is the readme file for the code:

MNIST Handwritten Digit Classification with TensorFlow
Introduction
This project demonstrates how to use TensorFlow to classify handwritten digits from the MNIST dataset. The MNIST dataset consists of 60,000 training images and 10,000 testing images, each of which is a 28x28 pixel grayscale image of a handwritten digit.

Data Preprocessing
The code first preprocesses the data by reshaping the input images to a one-dimensional array of 784 pixels and normalizing the pixel values to be between 0 and 1. The code then one-hot encodes the labels, which means that each label is represented by a vector of 10 elements, where the element corresponding to the correct label is 1 and the other elements are 0.

Model Architecture
The model consists of three layers: a fully connected layer with 512 units, a fully connected layer with 512 units, and an output layer with 10 units. The activation function for the hidden layers is ReLU, and the activation function for the output layer is softmax.

Model Training
The model is trained using the Adam optimizer and the categorical crossentropy loss function. The code trains the model for 10 epochs, with a batch size of 128.

Model Evaluation
The code evaluates the trained model on the test set and reports the accuracy.

Requirements
This project requires the following libraries:

TensorFlow
NumPy
Usage
To run the code, save it as a .py file and then execute the following command:

python MNIST_Handwritten_Digit_Classification.py
The code will print the accuracy of the trained model on the test set.
