# MNIST-Digit-Classification-MIT-DL-Lab2.1
This project is a part of MIT 6.S191 Introduction to Deep Learning course. In the first portion of this lab, we will build and train a convolutional neural network (CNN) for the classification of handwritten digits from the famous MNIST dataset. The MNIST dataset consists of 60,000 training images and 10,000 test images. Our classes are the digits 0-9.

Example from MNIST dataset

![dataset](https://user-images.githubusercontent.com/68354896/188329407-322d1917-3d00-4711-815b-9e062e59f34f.png)

First Architecture: Simple neural network consisting of two fully connected layers 

![mnist_2layers_arch](https://user-images.githubusercontent.com/68354896/188329431-559f5b28-7b96-42c9-8374-b008f1c55b0b.png)

Second Architecture: Convolutional Neural Network (CNN) composed of two convolutional layers and pooling layers, followed by two fully connected layers, and ultimately output a probability distribution over the 10 digit classes (0-9).

![cnn architecture](https://user-images.githubusercontent.com/68354896/188329566-c7b59f77-e422-4522-8126-d3d755b49473.png)  

Predictions where correct prediction labels are blue and incorrect prediction labels are grey. The number gives the percent confidence (out of 100) for the predicted label.

![predictions vs labels](https://user-images.githubusercontent.com/68354896/188329512-dfb8765d-f137-4cd4-a503-04591d86bd89.png)

