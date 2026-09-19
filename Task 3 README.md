K-Means Customer Segmentation
Overview
This project implements customer segmentation using the K-Means clustering algorithm. The objective is to group customers into meaningful segments based on selected customer characteristics.
The project was completed as part of the AI/ML Engineering – Basic track of the ArithMatrix Virtual Internship Program (AVIP) 2026.

Objective
To identify groups of customers with similar characteristics using unsupervised machine learning.

Dataset
The project uses a customer dataset containing attributes such as:

Annual Income
Spending Score
Methodology
Load the customer dataset.
Inspect the data.
Select clustering features.
Check for missing values.
Standardize the selected features.
Apply the Elbow Method.
Select an appropriate number of clusters.
Train the K-Means model.
Calculate cluster assignments.
Calculate cluster centroids.
Calculate cluster sizes.
Visualize the clusters.
Create customer profiles.
Develop actionable recommendations.

Technologies Used
Python
Pandas
NumPy
Scikit-learn
Matplotlib
Seaborn
Google Colab / Jupyter Notebook
Algorithm

The project uses K-Means clustering, an unsupervised learning algorithm.
K-Means repeatedly assigns observations to the nearest centroid and updates centroid positions until the clustering converges.

Elbow Method
The Elbow Method is used to investigate suitable values of k, representing the number of clusters.

Outputs
The project generates:
Cluster labels
Cluster sizes
Cluster centroids
Elbow plot
Cluster visualization
Customer profiles
Business-oriented recommendations
How to Run
Open the notebook in Google Colab or Jupyter Notebook.
Load the customer dataset.
Run the preprocessing steps.
Apply the Elbow Method.
Train the K-Means model.
Visualize the resulting clusters.
Analyze the customer profiles.

Expected Result
The system divides customers into meaningful groups and provides cluster characteristics that can be interpreted for business applications such as customer analytics and marketing.

Author
M. Ayshwarya
