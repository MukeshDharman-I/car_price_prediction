# Car Price Prediction

This project predicts the prices of used cars using a neural network model built with TensorFlow. The model is trained on a dataset containing various car features such as brand, model, fuel type, transmission, engine capacity, power, and more.

## Dataset

- Source: [Hugging Face](https://huggingface.co/datasets/jayaprakash-m/linearRegressionDS)
- The dataset includes car specifications like:
  - Make, Model, Fuel Type, Transmission,etc..
  - Year, Kilometers Driven, Max Power, Max Torque, Engine, Seating Capacity, etc.

## Project Workflow

1. Data preprocessing:
   - Handling missing values
   - One-hot encoding for categorical features
   - Feature extraction from text columns (e.g., power, torque)
   - Scaling of numerical features

2. Model:
   - Input layer
   - Dense layers with ReLU activation
   - Output layer for regression (linear activation)

3. Evaluation:
   - Mean Absolute Error (MAE)
   - Mean Squared Error (MSE)
   - R² Score
   - Actual vs Predicted plot

## Files in this repository

- `car_price.py`: Main notebook with all code
- `car_price_model.h5`: Trained model file
- `README.md`: Project documentation

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/MukeshDharman-I/car_price_prediction.git
   cd car_price_prediction
