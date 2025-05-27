# Traffic_Volume_Prediction_202401100300176
# 🚦 Traffic Volume Prediction

This project aims to build a regression model to predict traffic volume based on time and weather data using machine learning techniques. It includes feature engineering, data visualization, model training, and evaluation.

---

## 📌 Problem Statement
Predict the **traffic volume** using weather and time data to assist in traffic management, planning, and optimization.

---

## 🎯 Objectives
- Build a regression model to predict traffic volume.
- Perform feature engineering to improve model performance.
- Visualize relationships between features and the target.
- Evaluate model performance using standard metrics.

---

## 🗂️ Dataset
- **Source**: [Kaggle - Metro Interstate Traffic Volume](https://www.kaggle.com/uci/metro-interstate-traffic-volume)
- Features include:
  - `date_time`: timestamp of the record
  - `weather_main`, `weather_description`: weather conditions
  - `temp`, `rain_1h`, `snow_1h`, `clouds_all`, etc.
  - `traffic_volume`: the target variable

---

## 🛠️ Technologies Used
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- XGBoost, Random Forest

---

## 🔍 Methodology
1. Data Cleaning and Preprocessing
2. Feature Engineering (hour, weekday, weather encoding, etc.)
3. Exploratory Data Analysis (EDA)
4. Regression Model Implementation:
   - Linear Regression
   - Random Forest Regressor
   - XGBoost Regressor
   - Gradient Boosting Regressor
5. Model Evaluation (MAE, RMSE, R² Score)
6. Results and Visualization

---

