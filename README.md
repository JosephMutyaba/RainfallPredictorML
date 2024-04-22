# Rainfall Prediction Model

This project aims to predict rainfall using machine learning algorithms.

## Overview

The prediction model utilizes various machine learning algorithms to predict the amount of rainfall based on historical weather data. The dataset includes features such as location, latitude, longitude, and monthly rainfall measurements.

## Features

- One-hot encoding of categorical features
- Model training and evaluation using cross-validation
- Evaluation metrics: RMSE, R-squared score

## Installation

To run the project locally, follow these steps:

1. Clone the repository:

    ```
    git clone https://github.com/your-username/rainfall-prediction.git
    ```

2. Run the Jupyter Notebook or Python script:

    ```
    jupyter notebook rainfall_prediction.ipynb
    ```

## Usage

1. Prepare your dataset with historical weather data.
2. Modify the notebook/script to load your dataset and preprocess it accordingly.
3. Train and evaluate the machine learning models using the provided functions.
4. Make predictions on new data using the trained models.

## Models

The following machine learning algorithms were evaluated for rainfall prediction:

- Linear Regression
- Ridge Regression
- Decision Tree
- Random Forest
- Artificial Neural Network (MLPRegressor)
- K-Nearest Neighbors (KNN)

## Evaluation

Each model was trained and evaluated using k-fold cross-validation. The evaluation metrics used include:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R-squared Score
