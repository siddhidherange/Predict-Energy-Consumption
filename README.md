# Energy Consumption Prediction

A Deep Learning project using a Neural Network (MLP) to forecast energy consumption based on environmental variables.

## Overview
This project uses a dataset of 1,000 records to train a regression model. It analyzes the relationship between weather-related inputs and energy demand.



## Key Features
- **Data Scaling**: Uses `StandardScaler` for optimized neural network training.
- **Deep Learning Model**: A Sequential model with Dense layers (64, 32 neurons) built in TensorFlow.
- **Inputs**: Temperature, Humidity, Wind Speed, and Solar Irradiance.
- **Target**: Energy Consumption.

## Tech Stack
- **Python**: Core language.
- **TensorFlow/Keras**: Model building and training.
- **Scikit-learn**: Data splitting and preprocessing.
- **Pandas/NumPy**: Data manipulation.
- **Matplotlib**: Performance visualization.

## Quick Start
1. **Clone**: `git clone https://github.com/yourusername/repo-name.git`
2. **Install**: `pip install pandas numpy scikit-learn tensorflow matplotlib`
3. **Run**: Open `Predict_Energy_Consumption.ipynb` and execute all cells.

## Results
The model uses the **Adam** optimizer and **MSE** loss function to effectively minimize prediction error, providing accurate energy forecasts for resource planning.
