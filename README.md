# Carbon Footprint Projection Using LSTM Neural Network

## Overview

This project demonstrates how to generate synthetic time-series data simulating carbon footprint drivers, train an LSTM deep learning model to forecast future carbon footprint, and visualize both historical and projected data. The model incorporates multiple influencing factors such as energy consumption, industrial output, population, and policy effectiveness.

---

## Features

- Synthetic data generation simulating real-world factors and policy impact.
- Data preprocessing including scaling and sequence creation for LSTM input.
- LSTM model architecture with two layers and dropout for regularization.
- Early stopping callback to prevent overfitting.
- Model training, evaluation, and visualization of results.
- Multi-step future carbon footprint projection using extrapolated feature trends.
- Export of historical and projected data to Excel file.

---

## Requirements

- Python 3.x
- Libraries:
  - `numpy`
  - `pandas`
  - `matplotlib`
  - `scikit-learn`
  - `tensorflow` (with Keras API)

Install dependencies via pip:

```bash
pip install numpy pandas matplotlib scikit-learn tensorflow
Usage
Run the script (e.g., carbon_footprint_projection.py) to:

Generate synthetic carbon footprint data.
Train the LSTM model on historical data.
Evaluate and visualize model performance.
Project carbon footprint for the next 10 years.
Export data to carbon_footprint_projection_data.xlsx.
Optional: Modify parameters such as:
num_years: Number of years for synthetic data generation.
policy_change_year: Year policy starts impacting carbon footprint.
look_back and forecast_horizon: Sequence length and forecast steps for LSTM.
Future feature extrapolation method.

File Outputs
carbon_footprint_projection_data.xlsx — Excel file with two sheets:
Synthetic Historical Data: Generated historical data.
Projected Future Data: Forecasted carbon footprint for future years.

** How It Works **
Data Generation: Simulates trends in energy consumption, industrial output, population, and policy effectiveness over time.
Preprocessing: Normalizes data and creates sequences for the LSTM input.
Model Training: Trains an LSTM neural network to predict carbon footprint based on past data.
Prediction: Produces carbon footprint forecasts one year ahead.
Future Projection: Uses extrapolated future features for multi-year forecasting.
Visualization: Plots historical trends and future projections.

Notes
The dataset is synthetic for demonstration purposes only.
Future feature extrapolation is basic; replace with real forecasts for practical applications.
Model architecture and parameters can be tuned for better performance.
Serves as a baseline for more advanced carbon footprint prediction models.

Contact
Tarinabo williamtarinabo@gmail.com
