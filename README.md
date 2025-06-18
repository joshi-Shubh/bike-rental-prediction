# 🚲 Bike Rental Demand Prediction using Machine Learning

This project builds a regression model to predict the number of bike rentals based on various environmental and seasonal features.

## 📁 Project Contents

- `Bike_Rental_prediction.ipynb`: Jupyter notebook with EDA, feature engineering, model training, and evaluation.
- `requirements.txt`: Required Python libraries to run the notebook.

## 📊 Dataset

- **Features**:
  - datetime
  - season
  - weather
  - temperature
  - humidity
  - windspeed
  - holiday/working day
- **Target**: Number of bikes rented (`count`)

## 🧠 Models Used

- Linear Regression
- Random Forest Regressor
- Gradient Boosting Regressor etc.

## 📈 Evaluation Metrics

- RMSE (Root Mean Squared Error)
- MAE (Mean Absolute Error)
- R² Score

## 🚀 How to Run

```bash
pip install -r requirements.txt
jupyter notebook
