# Methodology

## Data Sources
- CPCB monitoring stations (Dissolved Oxygen)
- Meteorological datasets (rainfall, temperature)

## Data Preprocessing
- Missing value imputation
- Outlier removal
- Normalization
- Sliding window sequence creation

## Model Architecture
- LSTM network
- Fully connected output layer
- MSE loss function
- Adam optimizer

## Evaluation Metrics
- RMSE
- MAE
- R²

## Experimental Design
1. Train using historical DO only.
2. Train using historical DO + weather variables.
3. Compare results and analyze improvement.