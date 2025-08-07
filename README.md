# Pneumonia Detection Using Convolutional Neural Networks(CNN)
This project uses a Convolutional Neural Network (CNN) to detect Pneumonia from chest X-ray images. It classifies images into two categories: NORMAL and PNEUMONIA.

Tools & Technologies:
Python,
TensorFlow & Keras,
Matplotlib,
Google Colab / Kaggle Notebooks

Dataset: The dataset consists of labeled chest X-ray images split into training, validation, and testing sets.

Model Architecture: A CNN model with multiple convolutional and pooling layers followed by dense layers and dropout for regularization.

Performance: Accuracy: 
Test Accuracy of 81.1% - meaning the model correctly classified ~81% of chest X-ray images in the test set.
Test Loss of 0.51 - Loss of 0.51 is reasonable, though there is room for improvement.

EarlyStopping and ModelCheckpoint were used to optimize training
