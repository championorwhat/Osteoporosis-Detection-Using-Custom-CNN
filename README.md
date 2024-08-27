# Osteoporosis-Detection-Using-Custom-CNN
This project focuses on detecting osteoporosis using a custom Convolutional Neural Network (CNN) architecture.

## Overview
This project focuses on detecting osteoporosis using a custom Convolutional Neural Network (CNN) architecture. Osteoporosis is a condition characterized by weakened bones, increasing the risk of fractures. Early detection is crucial for effective treatment and prevention of severe complications. The model developed in this project is designed to classify images into categories related to osteoporosis, providing a reliable and efficient solution for medical professionals.

## Model Architecture
The custom CNN model was meticulously designed to achieve high accuracy in detecting osteoporosis. The architecture consists of multiple convolutional layers followed by batch normalization and max-pooling layers. Dense layers and dropout layers are included to prevent overfitting and ensure robust performance. The final layer utilizes softmax activation to classify the images into the relevant categories.

## Key Features:
Convolutional Layers: Extract features from input images, allowing the model to learn complex patterns associated with osteoporosis.
Batch Normalization: Accelerates training and improves model stability.
Max-Pooling Layers: Reduce spatial dimensions, making the model computationally efficient.
Dropout Layers: Prevent overfitting by randomly dropping neurons during training.
Dense Layers: Enable the model to make decisions based on the extracted features.
Softmax Activation: Used in the output layer to classify images into multiple categories.
Data Augmentation
To enhance the model's generalization capabilities, data augmentation techniques were applied. This includes random rotations, shifts, flips, and zooms, ensuring that the model is exposed to various transformations of the input images during training. These augmentations help the model perform well even with a limited dataset.

## Performance Metrics
The model's performance was evaluated using the following metrics:
Accuracy: Achieved an accuracy of 89%, indicating the model's overall effectiveness in classifying images correctly.
AUC (Area Under the Curve): Provides insight into the model's ability to distinguish between classes. A high AUC value reflects a strong classification performance.
Recall: Measures the model's ability to correctly identify positive cases of osteoporosis, ensuring that the model is sensitive to detecting the condition.

