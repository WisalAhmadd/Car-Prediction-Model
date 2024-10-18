In this Prediction Model we use the data set found in Kaggle you can use the one already uploaded or any othre you want 
just install and download the libraries and CSV file and Run the code!

# Car Price Prediction Model
This repository contains a TensorFlow-based deep learning model for predicting car prices using various input features. The model is designed to process tabular data and predict car prices based on the training dataset.

# Dataset
The dataset used for training is loaded from `train.csv` file and contains various features related to car specifications. The model is trained to predict the car prices using the features.

# Place your dataset file `train.csv` in the same directory as the script.
Run the model training script


After training, the model will output performance metrics, including loss and RMSE for both training and validation sets.

The model will also plot the training history and display Actual vs. Predicted car prices for visual comparison.

# Visualization
The script includes visualization to compare:
- Loss and validation loss across epochs
- RMSE for training and validation sets
- Actual vs. Predicted car prices in bar chart form

# Conclusion
The model demonstrates good performance with an R-squared value of 0.8458, which means it explains around 84.58% of the variance in the car prices. The MAPE value indicates that predictions are, on average, 15.90% off from the actual values.
