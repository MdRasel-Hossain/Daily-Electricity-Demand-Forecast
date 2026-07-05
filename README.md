# Daily Electricity Demand Forecasting

This project builds a machine learning pipeline to forecast daily electricity demand using Spanish electricity market data from Kaggle.

## Dataset
The dataset was taken from Kaggle: Spanish Electricity Market  
Link: https://www.kaggle.com/code/manualrg/daily-electricity-demand-forecast-machine-learning/input

## Project Workflow
- Data cleaning and preprocessing
- Exploratory data analysis
- Feature engineering with time, lag, and rolling features
- Model comparison using Linear Regression, Random Forest, and Gradient Boosting
- Hyperparameter tuning with TimeSeriesSplit
- Final 30-day electricity demand forecast

## Best Model
The Tuned Random Forest model performed best based on RMSE, MAE, MAPE, and R² score.

## Technologies
Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Joblib
