Linear Regression – House Price Prediction
Overview
This project implements a house-price prediction system using Linear Regression. The model learns relationships between property-related features and house values and uses those relationships to predict prices for unseen data. The project was completed as part of the AI/ML Engineering – Basic track of the ArithMatrix Virtual Internship Program (AVIP) 2026.

Objective
To develop a regression model capable of predicting house prices based on available numerical housing-related features.
Dataset
The project uses the California Housing dataset.
The dataset contains numerical housing-related features, while the target variable represents median house value.

Methodology
Load the dataset.
Inspect the features.
Check for missing values.
Separate features and target.
Divide the dataset into training and testing sets.
Train the Linear Regression model.
Generate test predictions.
Calculate MAE.
Calculate RMSE.
Calculate R².
Generate a residual plot.
Compare predictions with actual values.
Save the trained model.

Technologies Used
Python
Pandas
NumPy
Scikit-learn
Matplotlib
Seaborn
Google Colab / Jupyter Notebook
Model

The project uses Linear Regression.
The model learns coefficients from the training data to represent the relationship between the independent variables and the house-value target.
For a new observation, the learned coefficients are used to calculate the predicted house value.

Evaluation Metrics
The model is evaluated using:
MAE: Mean Absolute Error represents the average absolute difference between actual and predicted values.
RMSE: Root Mean Squared Error gives greater weight to larger prediction errors because the errors are squared before averaging.
R² Score: R² measures the proportion of variation in the target variable explained by the regression model.

Evaluation Outputs
The project generates:
MAE
RMSE
R² score
Residual plot
Prediction-versus-actual comparison
Sample predictions
Model Saving

The trained Linear Regression model is saved for later inference.
How to Run
Open the notebook in Google Colab or Jupyter Notebook.
Load the California Housing dataset.
Run the preprocessing steps.
Train the Linear Regression model.
Generate predictions.
Calculate the evaluation metrics.
Analyze the residual plot.
Save the trained model.

Expected Result
The system predicts house values for unseen observations and evaluates the predictions using MAE, RMSE, and R².

Applications
Potential applications include:
Property analytics
Real-estate platforms
Market analysis
Property valuation support
Investment analysis

Future Enhancements
The Linear Regression model can be compared with:
Random Forest Regression
Gradient Boosting
XGBoost
Ridge Regression
Lasso Regression
Cross-validation and feature engineering can also be introduced.

Author
M. Ayshwarya
