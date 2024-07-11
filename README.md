# Handwritten Digit Recognition using TensorFlow

![Handwritten Digit Recognition](https://miro.medium.com/v2/resize:fit:372/1*AO2rIhzRYzFVQlFLx9DM9A.png)

## Table of Contents
- [Overview](#overview)
- [Goal](#Goal)
- [Advantages](#Advantages)
- [Impact](Impact)
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)
- [Training and Evaluation](#Training_and_Evaluation)
- [Usage](#usage)
- [Contact](#contact)

## Overview
This project demonstrates a deep learning model built with TensorFlow for recognizing handwritten digits (0-9) using the MNIST dataset. The model achieves an accuracy of 97.77% on the test set.

## Goal
The goal of this project is to develop a robust and accurate model for handwritten digit recognition that can be deployed in various real-world scenarios.

## Advantages
This project focuses on leveraging deep learning techniques to automate the recognition of handwritten digits. 
The advantages include:
- **High accuracy and efficiency in digit recognition tasks.**
- **Scalability to handle large datasets and real-time applications.**

## Impact
In real-world scenarios, this project can:
- **Enhance automation in industries such as finance (cheque processing), postal services (mail sorting), and healthcare (medical form data entry).**
- **Improve accessibility by enabling devices to interpret handwritten input more accurately.**

## Dataset
The [MNIST dataset](https://www.kaggle.com/datasets/hojjatk/mnist-dataset) is used for training and testing. 
It consists of 60,000 training images and 10,000 test images of handwritten digits, each of size 28x28 pixels.

## Model Architecture
The model architecture is a sequential neural network with the following layers:
- Flatten: Converts each 28x28 image into a flat array of 784 pixels.
- Dense: Fully connected layer with 128 neurons and ReLU activation function.
- Dense: Fully connected layer with 128 neurons and ReLU activation function.
- Dense: Output layer with 10 neurons (corresponding to digits 0-9) and softmax activation function.

## Training_and_Evaluation
The model is trained using:
- Loss Function: Sparse Categorical Crossentropy.
- Optimizer: Adam.
- Metrics: Accuracy.

After training, the model achieves an accuracy of 97.77% on the test set.

 ## Contact
 **Name:** Moparthi Chandana Sree

 **GitHub:** [Chandana-sree-moparthi](https://github.com/Chandana-sree-moparthi)
 
 **Email:** chandanasreemoparthi@gmail.com
