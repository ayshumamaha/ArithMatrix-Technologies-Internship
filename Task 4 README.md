Plant Disease Detection
Overview
This project implements an image-classification system for identifying plant disease categories from plant images using a Convolutional Neural Network (CNN).
The project was completed as part of the AI/ML Engineering – Basic track of the ArithMatrix Virtual Internship Program (AVIP) 2026.

Objective
To develop an image-classification model capable of identifying different plant health and disease categories from photographs.

Dataset
The project uses the PlantVillage image dataset.
The dataset contains images representing different plant health and disease categories. The images are organized into class directories so that the TensorFlow image dataset loader can identify the classes automatically.

Methodology
Load the image dataset.
Identify class directories.
Resize images.
Normalize pixel values.
Create training and validation datasets.
Build the CNN classification model.
Train the model.
Evaluate model performance.
Generate a classification report.
Generate per-class performance.
Perform sample predictions.
Display prediction confidence.
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

A Convolutional Neural Network is used for multi-class image classification.
The CNN extracts visual features from plant images. The final Softmax layer generates probabilities for the available disease categories. The category with the highest probability is selected as the prediction.

Evaluation
The project includes:
Classification report
Per-class performance
Confusion matrix
Prediction confidence
Sample inference images
Model evaluation
Model Saving

The trained model is saved for later inference and reuse.

How to Run
Open the notebook in Google Colab or Jupyter Notebook.
Load the PlantVillage dataset.
Run the preprocessing cells.
Train the CNN model.
Evaluate the model.
Test sample plant images.
Save or load the trained model for inference.

Expected Result
The system predicts the disease or health category of a plant image and provides the corresponding prediction confidence.

Applications
Potential applications include:
Agricultural monitoring
Crop health analysis
Early disease identification
Farm decision-support systems
Agricultural research

Author
M. Ayshwarya
