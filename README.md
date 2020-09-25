# Digit-Recognition
Introduction

MNIST ("Modified National Institute of Standards and Technology") is a basic dataset dataset of computer vision. Since its release in 1999, this classic dataset of handwritten images has served as the basis for benchmarking classification algorithms. As new machine learning techniques emerge, MNIST remains a reliable resource for researchers and learners alike.

Approach
For this, we will be using Keras (with TensorFlow as our backend) as the main package to create a simple neural network to predict, as accurately as we can, digits from handwritten images. In particular, we will be calling the Functional Model API of Keras, and creating a 3-layered neural network.Optimizer used here is Adam optimizer.

Adam Optimizer:
Adam is an optimization algorithm that can be used instead of the classical stochastic gradient descent procedure to update network weights iterative based in training data.

Implementation of program:
We first import data set from keras and assign them to our training data and label, and testing data and labels.we then perform grayscale normalization to reduce the effect of illumination's differences.
Then we build a 3 layered neural network and optimize it using Adam optimizer and epochs=10(number of passes in training to optimize error)

Result:
We plot the given image ,actual number and number predicted by the program.


