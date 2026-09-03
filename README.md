**Turbofan Engine Remaining Useful Life Prediction**

A machine learning project for predicting the degradation and remaining life of turbofan engines using the NASA C-MAPSS FD001 dataset and a Random Forest Regressor.

**Project Overview**

Predictive maintenance helps identify the health condition of equipment before failure. In this project, sensor measurements from turbofan engines are analyzed to estimate the engine's Life Ratio, which represents its progression from the beginning of operation toward its end of life.

**Objectives**

1. Analyze turbofan engine sensor data.
2. Identify and remove sensors with constant values.
3. Create a normalized Life Ratio as a degradation indicator.
4. Train a Random Forest regression model.
5. Compare predicted and actual degradation trends.
6. Evaluate the model using Mean Squared Error (MSE).

**Dataset**

The project uses the NASA C-MAPSS (Commercial Modular Aero-Propulsion System Simulation) dataset.

The C-MAPSS dataset contains simulated turbofan engine run-to-failure data with multiple operational settings and sensor measurements.

This project uses data from:

FD001 for initial analysis and modeling.

FD001–FD004 test datasets for additional processing and analysis.

**Methodology**

1. NASA C-MAPSS Dataset
2. Load Training & Test Data
3. Remove Empty Columns
4. Assign Sensor Names
5. Exploratory Data Analysis
6. Remove Constant Sensors
7. Create Life Ratio
8. Correlation Analysis
9. Feature Selection
10. Train/Test Split
11. Random Forest Regression
12. Prediction & Evaluation
13. Compare True vs Predicted Life

**Machine Learning Model**
A Random Forest Regressor with 100 trees and random state 42 was used to predict the engine Life Ratio from sensor data. The dataset was split into 80% training and 20% testing data.

**Model Evaluation**

The model was evaluated using Mean Squared Error (MSE).

For the initial FD001 experiment, the obtained MSE was:

MSE = 0.00362

The project also visualizes the true versus predicted Life Ratio over operating cycles for individual engine units.

**Visualization**

The project includes:

1. Sensor histograms
2. Correlation heatmap
3. True vs. predicted Life Ratio plots

These visualizations help evaluate how well the model follows the engine's degradation trajectory
