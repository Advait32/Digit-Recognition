# Digit-Recognition

We implement a deep neural network consisting of convolutional and fully connected layers to classify handwritten digits of the MNIST dataset. The labeled dataset consists of 42000 images of size 28x28 = 784 pixels (one gray-scale number) including the corresponding labels from 0,..,9.This architecture is implemented with TensorFlow. In order to prevent the network from overfitting during learning we implement dropout and data augmentation, i.e. new images are generated from the original ones via rotation, translation and zooming. Finally, we predict the digit classes for the test set and write the  file.
