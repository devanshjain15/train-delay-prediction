# Train Delay Prediction — Central Railway

Predicts average train delays at Indian railway stations using historical
on-time performance data and a Random Forest Regressor.

## Results
| Metric | Value |
|--------|-------|
| MAE | 6.05 minutes |
| R² Score | 0.941 |
| Model | Random Forest Regressor (100 trees) |
| Dataset | Indian Railways Train Delays 2025 (Kaggle) |

## Features used
- Station identity, Train identity
- % Right time, % Slight delay, % Significant delay
- % Cancelled/unknown, Unreliability score (engineered)

## How to run
1. Clone this repo
2. Place dataset CSV in `data/etrain_delays.csv`
3. Open `train_delay.ipynb` in Jupyter and run all cells

## Tools
Python · Pandas · Scikit-learn · Matplotlib · Seaborn
