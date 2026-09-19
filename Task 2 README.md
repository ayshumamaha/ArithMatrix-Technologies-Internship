Spam SMS / Email Classifier
Overview
This project implements a text-classification system that automatically identifies whether an SMS or email message is Spam or Ham (legitimate). The project was completed as part of the AI/ML Engineering – Basic track of the ArithMatrix Virtual Internship Program (AVIP) 2026.

Objective
To develop a machine-learning model capable of classifying messages as spam or legitimate using text-based features.

Dataset
The project uses the SMS Spam Collection dataset.
The dataset contains labelled messages belonging to two categories:

Spam
Ham
Methodology
Load the dataset.
Inspect labels and messages.
Convert labels into numerical form.
Split the dataset into training and testing sets.
Convert text into TF-IDF features.
Train a Logistic Regression classifier.
Evaluate the classifier.
Generate a confusion matrix.
Test example messages.
Display predicted class and probability.
Save the complete preprocessing/model pipeline.

Technologies Used
Python
Pandas
NumPy
Scikit-learn
Matplotlib
Seaborn
Google Colab / Jupyter Notebook
Feature Extraction

TF-IDF (Term Frequency–Inverse Document Frequency) is used to convert text messages into numerical feature vectors.
Model
The project uses Logistic Regression for binary text classification.

The complete pipeline includes:
TF-IDF vectorization
Logistic Regression classification

Evaluation
The classifier is evaluated using:
Accuracy
Precision
Recall
F1-score
Confusion matrix
Probability-based predictions

The implementation also includes example predictions for at least ten messages.

Saved Model
The complete preprocessing and classification pipeline is saved as: spam_classifier.pkl

How to Run
Open the notebook in Google Colab or Jupyter Notebook.
Install the required dependencies.
Load the SMS Spam Collection dataset.
Run the preprocessing and training cells.
Evaluate the model.
Enter new SMS/email text for prediction.


Expected Result
The system classifies a new message as either Spam or Ham and can provide the predicted probability for the classification.

Author
M. Ayshwarya
