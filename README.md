Real Estate Price Prediction App

This is a web-based application built using Python, Dash, and scikit-learn to predict real estate prices based on specific input features. The application uses a linear regression model to predict the price of a house in a specific unit area, depending on the following inputs:

Distance to the nearest MRT station
Number of convenience stores nearby
Latitude
Longitude
The app takes these values from the user, processes the inputs through the trained model, and returns a predicted price of a house.

Features
User Input: Users can input values for distance to MRT, number of convenience stores, latitude, and longitude.
Prediction: The app uses a pre-trained linear regression model to predict the house price.
Interactive UI: The web app is built using Dash, providing a simple, interactive interface for predictions.
Error Handling: The app validates the inputs and returns an appropriate message if inputs are missing or invalid.
Project Structure
app.py: The main Python file that contains the Dash application, callback function, and model prediction logic.
Real_Estate.csv: A dataset containing real estate data used for training the model.
linear_regression_model.pkl: The saved machine learning model used for predictions.
requirements.txt: The list of dependencies required to run the app.
Getting Started
Prerequisites
To run this project, you'll need to have the following installed:

Python 3.x
Dash (pip install dash)
Pandas (pip install pandas)
Scikit-learn (pip install scikit-learn)
Joblib (pip install joblib)
