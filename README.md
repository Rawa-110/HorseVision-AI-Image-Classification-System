# HorseVision-AI-Image-Classification-System

Project Description

HorseVision AI is an artificial intelligence project that uses deep learning and computer vision techniques to recognize and classify images. The main goal of this project is to train a machine learning model that can identify a specific class of images and predict the correct category with a high level of confidence.

The model was created using Google Teachable Machine, where images were collected and organized into different classes. The system was trained using a neural network model, then exported as a Keras model (keras_model.h5) for testing and prediction.

The trained model was loaded using TensorFlow and Keras, and images were processed before being given to the model. The system analyzes the input image, extracts important visual features, and compares them with the patterns learned during training. After processing, it outputs the predicted class name and the confidence percentage.
In this project, the model successfully recognized a horse image and predicted the correct class with a confidence level of approximately 99.99%, demonstrating the effectiveness of deep learning for image recognition tasks.

Objectives
To understand how artificial intelligence can be used for image classification.
To build and train a deep learning model using Teachable Machine.
To apply computer vision techniques for recognizing images.
To test the accuracy of a trained AI model.
To use TensorFlow and Keras for loading and running the model.

Tools and Technologies
Python: Programming language used to build the prediction system.
TensorFlow: Framework used for machine learning and deep learning.
Keras: Library used to load and run the trained neural network model.
Google Colab: Online environment used for testing the model.
Google Teachable Machine: Platform used to train and export the image classification model.

How the System Works
Data Collection:
Images are collected and divided into different categories (classes).
Model Training:
The images are used to train a neural network model using Teachable Machine.
Model Export:
The trained model is exported as a Keras file (keras_model.h5).
Image Processing:
The input image is resized and converted into a format that the model can understand.
Prediction:
The AI model analyzes the image and predicts the correct class.
Output Result:
The system displays the predicted class and confidence score.

Results

The model successfully classified the test image as:

Class: Horse
Confidence: 99.9986%

This result shows that the trained model can accurately recognize images and make reliable predictions.
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/492893db-38e1-41e4-810e-0ad181e6b2c3" />

Conclusion

This project demonstrates the power of artificial intelligence and deep learning in image recognition. By training a neural network model and using TensorFlow and Keras, the system can identify objects from images with high accuracy. This type of technology can be applied in many fields such as animal recognition, security systems, healthcare, and automated inspection systems.
