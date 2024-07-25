# Stock-Market-Prediction-with-LSTM
This repository contains a project for predicting stock prices using the Long Short-Term Memory (LSTM) neural network model. The project utilizes historical stock data of Netflix (NFLX) to train and test the LSTM model for predicting stock prices.
Model
The LSTM model used in this project has the following architecture:

Input layer
Two LSTM layers with 25 units each
Dropout layer with a rate of 0.1
Dense output layer
The model is compiled with mean squared error (MSE) as the loss function and Adam optimizer.

Results
The model is trained for 100 epochs with training and validation mean absolute error (MAE) as the evaluation metric. The results indicate the model's performance in predicting stock prices.
