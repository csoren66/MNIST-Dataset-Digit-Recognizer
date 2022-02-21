# MNIST-Dataset-Digit-Recognizer

MNIST ("Modified National Institute of Standards and Technology") is the de facto “hello world” dataset of computer vision. Since its release in 1999, this classic dataset of handwritten images has served as the basis for benchmarking classification algorithms. As new machine learning techniques emerge, MNIST remains a reliable resource for researchers and learners alike.

# Overview of the dataset
The MNIST dataset consists of grayscale images of handwritten digits (0 to 9).
Each image is of dimension 28x28.
Dataset contains 60000 Training images and 10000 Test images
The dataset comes inbuilt with tf.keras, with normalized images, separated into training and testing sets![68747470733a2f2f75706c6f61642e77696b696d656469612e6f72672f77696b6970656469612f636f6d6d6f6e732f322f32372f4d6e6973744578616d706c65732e706e67](https://user-images.githubusercontent.com/67580321/154894496-68711268-0476-4c49-8c03-9adc96e76d1f.png)

# What we are building
We are building an image classifier capable of identifying handwritten digits ranging from 0 to 9. To train the model, we will use the training set of 60000 images and the rest 10000 testing set to test the model later on.

Our neural network will be a fully connected (densely connected) neural network.
Input layer of 784 input (28x28 image pixels)
2 hidden fully connected layers of 256 nodes each (this number may change as we play around with the network)
output layer with 10 nodes (1 node for each digit from 0 to 9)
input layer[754] --> dense1[256] --> dense2[256] --> output[10]
