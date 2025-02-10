# Uber-Fare-Prediction-using-Python

## 📌 Project Overview
Uber Fare Prediction is a **machine learning project** that aims to accurately predict the fare amount of Uber rides based on various factors such as pickup and dropoff locations, distance, time of the day, and passenger count. This project implements multiple regression models, including **Linear Regression, Random Forest, Gradient Boosting, XGBoost, LightGBM, and Neural Networks**, to compare performance and optimize accuracy.

## 🚀 Features
✅ Data Cleaning & Preprocessing  
✅ Exploratory Data Analysis (EDA)  
✅ Feature Engineering (Distance Calculation, Time Features)  
✅ Model Training (Linear Regression, Random Forest, XGBoost, LightGBM, Neural Networks)  
✅ Performance Evaluation (RMSE, R² Score)  
✅ Hyperparameter Tuning for Optimization  
✅ Deployment-ready Code (Flask API integration - Optional)  

## 📂 Dataset Information
The dataset contains **200,000** Uber ride records with the following features:
- **fare_amount** (Target variable)
- **pickup_datetime** (Date & time of ride)
- **pickup_latitude & pickup_longitude** (Pickup coordinates)
- **dropoff_latitude & dropoff_longitude** (Dropoff coordinates)
- **passenger_count** (Number of passengers)

## 🔬 Exploratory Data Analysis (EDA)
- Checked for **missing values** and handled them appropriately.
- Calculated **trip distance** using Haversine formula.
- Extracted **date-time features** (hour, day, month, weekday) from `pickup_datetime`.
- Visualized **fare distribution** and correlations using Seaborn & Matplotlib.

## 🛠️ Model Training & Performance
### **1️⃣ Baseline Model: Linear Regression**
- **RMSE**: `10.191632`  
- **R² Score**: `0.001486` (Poor Performance)

### **2️⃣ Best Performing Model: Random Forest**
- **RMSE**: `6.112316`  
- **R² Score**: `0.640848`  

### **3️⃣ Advanced Models: XGBoost & LightGBM**
- **XGBoost RMSE**: `6.748792` 
- **LightGBM RMSE**: `5.791985` 

## 🏆 Key Takeaways
✔ **Random Forest & Boosting models outperform Linear Regression.**  
✔ **Hyperparameter tuning improves accuracy significantly.**  
✔ **Deep Learning models (ANN) can further enhance predictions.**  
✔ **LightGBM is the best choice for fast & scalable predictions.**  

## 🛠️ Technologies Used
- **Programming Language**: Python 🐍
- **Data Processing**: Pandas, NumPy
- **Visualization**: Matplotlib, Seaborn
- **Machine Learning Models**: Scikit-Learn, XGBoost, LightGBM, TensorFlow/Keras
- **Deployment (Optional)**: Flask/FastAPI

