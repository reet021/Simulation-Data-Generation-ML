# Data Generation using Modelling and Simulation for Machine Learning

## Objective
To generate synthetic data using a simulation approach and evaluate machine learning models on the generated data.

## Simulation Tool Used
scikit-learn data generation module (make_regression)

## Parameters and Bounds
- Number of samples: 100 – 1000
- Number of features: 5 – 20
- Noise level: 0 – 20

## Methodology
1. Synthetic data was generated using a regression-based simulator.
2. 1000 simulated samples were created.
3. Data was split into training and testing sets.
4. Multiple ML models were trained and evaluated.

## Models Compared
- Linear Regression
- Decision Tree
- Random Forest
- Support Vector Regression
- K-Nearest Neighbors

## Evaluation Metrics
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R2 Score

## Results
Random Forest achieved the best performance on the simulated dataset.

## Tools Used
- Google Colab
- Python
- scikit-learn
- NumPy
- Pandas
