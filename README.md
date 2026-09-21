# NYC Taxi Fare Prediction (Multiple Linear Regression)

Predicting NYC taxi fares using 2017 TLC Yellow Taxi trip data, built as an
end-to-end regression project: data cleaning, EDA, statistical testing,
model building, and assumption diagnostics.

## Results
- R² ≈ 0.96 | MAE ≈ $0.60 | RMSE ≈ $1.33
- `trip_distance` and `duration` are the strongest predictors of fare
- No meaningful multicollinearity (all VIF < 5)

## Project structure
├── nyc_taxi_fare_prediction_mlr.ipynb   # full analysis notebook
├── data/                                 # dataset (or a note on how to get it)
├── README.md
└── requirements.txt

## How to run
1. Clone the repo
2. `pip install -r requirements.txt`
3. Open `nyc_taxi_fare_prediction_mlr.ipynb` in Jupyter

## Data
[2017 Yellow Taxi Trip Data](link-if-public) — NYC Taxi & Limousine Commission.

## Tools
pandas, numpy, scipy, seaborn, matplotlib, scikit-learn, statsmodels
