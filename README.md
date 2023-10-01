# Amazon ML Challenge - Product ID Prediction

This repository contains the code and data for the Amazon ML Challenge, which aims to predict Product IDs based on various product attributes. The challenge involves data preprocessing, exploratory data analysis, and training machine learning models for prediction.

## Dataset

The dataset used in this project consists of two main files:
- `train.csv`: This file contains the training data, including product titles, bullet points, descriptions, and other attributes.
- `test.csv`: This file contains the testing data for which we need to make predictions.

## Data Preprocessing

1. **Data Loading**: The training and testing data were loaded from CSV files.

2. **Handling Missing Values**: Missing values in the dataset were either dropped or filled with appropriate values.

3. **Text Cleaning**: Text data in the "TITLE," "BULLET_POINTS," and "DESCRIPTION" columns were cleaned by making text lowercase, removing square brackets, links, punctuation, and words containing numbers.

4. **Data Exploration**: Exploratory data analysis was performed, including statistical summaries and visualization of key attributes.

## Machine Learning Models

Three machine learning models were trained and evaluated for predicting product IDs:

1. **Linear Regression**: A basic linear regression model was used as a baseline.

2. **Decision Tree Regressor**: A decision tree regressor model was employed to capture nonlinear relationships.

3. **Random Forest Regressor**: A random forest regressor, an ensemble method, was used for improved prediction accuracy.

## Evaluation Metrics

For each model, the following evaluation metrics were calculated:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R-squared Score (R2)

## Usage

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/yourusername/Amazon-ML-Challenge.git
