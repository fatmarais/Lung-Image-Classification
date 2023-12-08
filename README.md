# Lung Image Classification using Convolutional Neural Networks (CNN)

This project aims to develop a machine learning model for the classification of lung images into three distinct categories: COVID, NORMAL, and PNEUMONIA. The dataset contains 1626 COVID images, 1802 NORMAL images, and 1800 PNEUMONIA images. 

The project unfolds in four main stages:

## 1. Define CNN Architecture
  In the first step, the focus is on defining the architecture of the Convolutional Neural Network (CNN) model. Key considerations include determining the number of convolutional layers, selecting activation functions for each layer, and deciding on the number of hidden units within each layer.
  
## 2. Model Training
  The second step involves the training of the model. The dataset is split into training, validation and testing sets, with the model trained over a specified number of epochs. Initial training is set to 15 epochs, though this parameter can be adjusted later.
  
## 3. Image Prediction
  Following training, the third step entails predicting the classes of test images. The trained model is applied to load test data, predicting the respective classes for each image.

## 4. Model Evaluation
  Lastly, the performance of the model is evaluated in the fourth step. This includes generating a confusion matrix to assess the model's accuracy. The project also involves the creation of a graphical interface, allowing users to test different lung images interactively.
