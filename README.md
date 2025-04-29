# CNN-Cat-vs-Dog-Project
This project involves building a Convolutional Neural Network (CNN) model using Keras and TensorFlow to classify images of cats and dogs.


# Key Features:
Data Preprocessing with ImageDataGenerator including rescaling, shearing, zooming, and horizontal flipping to improve model generalization.

# Deep CNN Architecture:

3 Convolutional layers with increasing number of filters (32 → 64 → 128)

MaxPooling after each convolution to reduce spatial dimensions

Fully connected Dense layers with Dropout to prevent overfitting

Training on a labeled dataset with binary crossentropy loss and Adam optimizer.

Testing and Evaluation on a separate test dataset to measure performance.

Single Image Prediction to classify unseen images individually (real-time testing).

Achieved strong model performance (~90%+ test accuracy).

# Technologies Used:
Python

Keras with TensorFlow backend

NumPy

PIL (Python Imaging Library)

# How to Run:
Prepare the dataset in training_set/ and test_set/ folders (cats and dogs subfolders).

Train the model by running the Python script.

Predict new images by supplying the image path for inference.

This project showcases skills in Deep Learning, CNN model design, and computer vision, making it ideal for real-world binary classification problems.

