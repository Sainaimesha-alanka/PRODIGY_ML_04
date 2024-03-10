# PRODIGY_ML_04
Hand-Gesture recognition model
This repository contains code on Developing a hand gesture recognition model that can accurately identify and classify different hand gestures from image or video data, enabling intuitive human-computer interaction and gesture-based control systems.

##Algorithm:
##Data Preprocessing:

Split the dataset into training and validation sets.
##Model Definition:

Create a Convolutional Neural Network (CNN) model using TensorFlow and Keras.
##Data Augmentation:

Apply data augmentation techniques using the ImageDataGenerator to create variations in the training set.
##Model Compilation:

Compile the model with an appropriate optimizer (e.g., Adam), categorical crossentropy loss, and accuracy as the metric.
##Model Training:

Train the model using the augmented training set.
Specify the number of epochs and monitor the validation accuracy.
##Model Evaluation:

Evaluate the model on the validation set to assess its performance.
Display the accuracy achieved on the validation set.


Confusion Matrix:

Use scikit-learn's confusion_matrix to compute the confusion matrix based on the model's predictions on the validation set.
##Usage:
Dataset from Kaggle Hand Gesture.
Used Jupiter Notebook for Python Coding.
##Techniques:
CNN model is implemented in this project.
