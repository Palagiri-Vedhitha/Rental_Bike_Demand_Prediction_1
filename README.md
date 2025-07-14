# Rental_Bike_Demand_Prediction_1
# 🚲 Rental Bike Demand Prediction

This project uses machine learning to predict daily bike rental counts based on historical weather and seasonal data from Washington D.C.’s Capital Bikeshare system (2011–2012).

## 📁 Dataset

The dataset used is [day.csv](day.csv), part of the Bike Sharing Dataset from the UCI Machine Learning Repository.

## 📊 Features Used

- Season, Month, Weekday
- Holiday and Working Day indicators
- Weather situation
- Temperature, Atemp (feels-like temperature), Humidity, Windspeed

## 🛠 Technologies

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook

## ⚙ Model

We used a *Random Forest Regressor* to train the model on the dataset and evaluated using:
- R² Score
- Root Mean Squared Error (RMSE)

## 🔍 Project Structure

rental-bike-demand-prediction/
│
├── data/
│ └── day.csv
├── rental_bike_prediction.ipynb
├── requirements.txt
└── README.md

markdown
Copy
Edit

## 💡 Improvements

- Model tuning using GridSearchCV
- Try other models: XGBoost, LightGBM
- Deployment using Streamlit or Flask

## 👤 Author

Palagiri Vedhitha












