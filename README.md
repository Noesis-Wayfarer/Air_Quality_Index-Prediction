# 🌍 Air Quality Index (AQI) Prediction

> Predicting air quality today to protect public health tomorrow.

An end-to-end Machine Learning project that predicts the **Air Quality Index (AQI)** using historical pollutant concentration data. This project explores data preprocessing, exploratory data analysis, feature importance, regression model comparison, and deploys the best-performing model through an interactive **Streamlit** web application.

---

## 📖 Overview

Air pollution is one of the most significant environmental challenges affecting public health worldwide. The Air Quality Index (AQI) is a standardized metric used to communicate air quality levels and their associated health impacts.

This project leverages Machine Learning techniques to forecast AQI values using pollutant concentration data, enabling better environmental monitoring and informed decision-making.

---

## 🎯 Objectives

- Predict Air Quality Index (AQI) using historical air pollution data.
- Perform data cleaning and preprocessing.
- Conduct Exploratory Data Analysis (EDA).
- Compare multiple regression algorithms.
- Evaluate model performance using standard regression metrics.
- Identify the most influential pollutants affecting AQI.
- Deploy the final model using Streamlit.

---

## 🛠️ Tech Stack

| Category | Technologies |
|----------|--------------|
| Programming Language | Python |
| Data Analysis | Pandas, NumPy |
| Data Visualization | Matplotlib, Seaborn |
| Machine Learning | Scikit-learn, XGBoost |
| Model Deployment | Streamlit |
| Model Persistence | Joblib |

---

## 📂 Dataset

**Source:** Kaggle – Air Quality Dataset

**File Used:** `city_day.csv`

### Features

- PM2.5
- PM10
- NO
- NO₂
- NOx
- NH₃
- CO
- SO₂
- O₃

**Target Variable**

- AQI (Air Quality Index)

---

## 🔄 Project Workflow

```text
Dataset
    │
    ▼
Data Cleaning
    │
    ▼
Exploratory Data Analysis
    │
    ▼
Feature Selection
    │
    ▼
Model Training
    │
    ▼
Model Evaluation
    │
    ▼
Best Model Selection
    │
    ▼
Streamlit Deployment
```

---

## 🤖 Machine Learning Models

The following regression algorithms were implemented and compared:

- Linear Regression
- Random Forest Regressor
- XGBoost Regressor

---

## 📊 Evaluation Metrics

The models were evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

---

## 🏆 Results

Among all evaluated models,

**Random Forest Regressor** achieved the highest prediction accuracy.

Key observations:

- PM2.5 was identified as the strongest predictor of AQI.
- Ensemble methods significantly outperformed Linear Regression.
- The model successfully captured complex non-linear relationships between pollutants and AQI.


---

## 📈 Future Improvements

- Deep Learning-based AQI prediction
- Real-time AQI forecasting using live APIs
- Weather parameter integration
- Interactive forecasting dashboard
- Cloud deployment

---

> *"Predicting air quality today helps protect public health tomorrow."*
