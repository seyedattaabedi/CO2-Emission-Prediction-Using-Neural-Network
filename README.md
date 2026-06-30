# CO2 Emission Prediction Using Neural Network

This project uses a Deep Neural Network (DNN) built with Keras/TensorFlow to predict vehicle CO₂ emissions based on engine and fuel consumption features.

## Features

* Engine size
* Number of cylinders
* Fuel consumption in city
* Fuel consumption on highway
* Combined fuel consumption

## Technologies Used

* Python
* TensorFlow / Keras
* Pandas
* NumPy
* Scikit-learn
* Matplotlib

## Model Architecture

* Input Layer: 5 features
* Hidden Layer: Dense(20, ReLU)
* Output Layer: Dense(1)

## Workflow

1. Load and preprocess dataset
2. Split data into training and testing sets
3. Build neural network model
4. Train model using Mean Squared Error loss
5. Predict vehicle CO₂ emissions

## Goal

The goal of this project is to demonstrate regression using neural networks for environmental and automotive datasets.
