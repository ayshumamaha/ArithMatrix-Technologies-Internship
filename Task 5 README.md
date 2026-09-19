Hand Gesture Recognition
Overview
This project implements a hand gesture recognition system using image classification and a Convolutional Neural Network (CNN). The system identifies predefined hand gestures from images. The project was completed as part of the AI/ML Engineering – Basic track of the ArithMatrix Virtual Internship Program (AVIP) 2026.

Objective
To develop a computer-vision system capable of recognizing predefined hand gestures from input images.
Dataset
The implementation expects an image dataset organized into class directories.
The gesture classes are automatically identified from the directory structure.

Methodology
Load gesture images.
Identify gesture classes.
Resize images.
Normalize pixel values.
Split the dataset into training and validation data.
Build a CNN model.
Train the model.
Evaluate the model.
Generate a confusion matrix.
Generate sample predictions.
Save the trained model.

Technologies Used
Python
TensorFlow
Keras
NumPy
Pandas
Matplotlib
Seaborn
Google Colab / Jupyter Notebook
Model

A Convolutional Neural Network is used to learn visual patterns associated with different hand gestures.
During inference:
The input image is resized.
Pixel values are normalized.
The image is passed through the trained CNN.
Probabilities are calculated for each gesture class.
The class with the highest probability is returned as the prediction.

Evaluation
The project includes:
Model evaluation
Classification report
Confusion matrix
Prediction confidence
Demonstration images
Sample predictions
Model Saving

The trained model is saved so that it can be loaded later without retraining.

How to Run
Open the notebook in Google Colab or Jupyter Notebook.
Place the gesture dataset in the required directory structure.
Run the preprocessing cells.
Train the CNN model.
Evaluate the model.
Test sample gesture images.
Save or load the trained model.

Applications
Potential applications include:
Human-computer interaction
Accessibility systems
Smart-device control
Gaming
Touchless interfaces
Future Enhancements

The system can be extended with:
Real-time webcam recognition
OpenCV integration
MediaPipe hand landmark detection
Gesture-to-command systems
Video-based gesture recognition

Author
M. Ayshwarya
