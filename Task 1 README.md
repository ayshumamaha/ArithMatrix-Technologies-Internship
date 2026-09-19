Cats vs Dogs Image Classification

Overview
This project implements a binary image classification system using a Convolutional Neural Network (CNN) to classify images into two categories: Cat and Dog. The project was completed as part of the AI/ML Engineering – Basic track of the ArithMatrix Virtual Internship Program (AVIP) 2026.

Objective
To develop a machine-learning/deep-learning image classifier capable of distinguishing between cats and dogs from input images.

Dataset
The project uses the publicly available Cats vs Dogs image dataset.
The dataset contains two classes:
Cat
Dog

Methodology
Load the Cats vs Dogs dataset.
Remove unusable or corrupted images where necessary.
Resize images to a common image size.
Normalize image pixel values.
Create training and validation/test datasets.
Construct the CNN-based classification model.
Train the model.
Evaluate the model.
Generate a confusion matrix.
Perform inference on sample images.
Save the trained model.

Technologies Used
Python
TensorFlow
Keras
NumPy
Matplotlib
Seaborn
Google Colab / Jupyter Notebook
Model

A Convolutional Neural Network (CNN) is used for image classification.
The convolutional layers learn visual features such as edges, textures, shapes, and higher-level image patterns. The final sigmoid layer produces a binary probability, with a threshold of 0.5 used to determine the predicted class.

Evaluation
The project includes:
Model evaluation
Classification report
Confusion matrix
Sample image predictions
Predicted labels
Ground-truth labels
Model Output

The trained model is saved as: cats_vs_dogs_model.keras

How to Run
Open the notebook in Google Colab or Jupyter Notebook.
Install the required libraries.
Load the dataset.
Run the cells sequentially.
Train or load the saved model.
Provide a test image for prediction.

Expected Result
The system predicts whether an input image belongs to the Cat or Dog class and provides evaluation results and sample predictions.

Author
M. Ayshwarya
