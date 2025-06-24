# CNN-for-Image-Classification
Image classification model using a Convolutional Neural Network (CNN) in PyTorch, trained on the CIFAR-10 dataset.

Project Description
This project showcases the implementation and training of a Convolutional Neural Network (CNN) using PyTorch for the task of image classification on the CIFAR-10 dataset. The primary goal was to explore the practical application of deep learning in computer vision and achieve a reasonable performance on a standard benchmark dataset.

I successfully achieved an accuracy of up to 54% on the test set, demonstrating the model's capability to distinguish between the 10 image classes: airplane, automobile, bird, cat, deer, dog, frog, horse, ship, and truck.

Dataset: CIFAR-10
CIFAR-10 is a widely used dataset in computer vision, consisting of 60,000 32x32 pixel color images across 10 classes, with 6,000 images per class. It is divided into 50,000 training images and 10,000 test images.

Model Architecture
The CNN model is composed of:

Convolutional Layers: For effective feature extraction from images.
Pooling Layers (Max Pooling): To reduce dimensionality, making the model more robust to variations and controlling overfitting.
Activation Functions (ReLU): Applied after convolutional layers to introduce non-linearity.
Batch Normalization: Used to stabilize and accelerate the training process.
Fully Connected Layers: For final classification based on the extracted features.
