# Electricity-Load-Forecasting
Forecasting household electric power consumption using machine learning techniques, particularly time-series modeling.

# ⚡ Household Power Consumption Forecasting using Machine Learning

This project focuses on forecasting household electric power consumption using machine learning techniques, particularly time-series modeling. We use the [UCI Household Electric Power Consumption Dataset](https://archive.ics.uci.edu/ml/datasets/individual+household+electric+power+consumption) to explore, model, and compare various forecasting algorithms, including PyCaret’s built-in models.

## 📊 Problem Statement
Accurate energy consumption forecasting is crucial for smarter electricity usage, demand planning, and optimizing grid operations. In this project, we aim to predict future values of **Global Active Power** by leveraging historical consumption data, uncovering temporal patterns and evaluating multiple machine learning models to identify the best-performing ones.


## 📁 Project Structure

├── notebooks/

│ └── time_series_modeling.ipynb # Main Colab notebook

├── models/

│ └── model_1.pkl, model_2.pkl, ... # Top 10 saved PyCaret models

├── data/

│ └── household_power_consumption.txt # Original dataset

├── outputs/

│ └── plots, CSVs, and forecasts

├── README.md


## 🧠 Models Compared

The following time-series models were evaluated using PyCaret:

- ARIMA
- ETS
- LightGBM
- CatBoost
- Ridge Regression
- ElasticNet
- Random Forest
- KNN
- Prophet
- Gradient Boosting Regressor

Each model was assessed on performance metrics such as **MAE**, **RMSE**, and **R²**.

## 📌 Key Features

- 📈 Multimodel comparison using PyCaret
- 📅 Minute-level time-series analysis
- 🧼 Preprocessing, EDA, and trend decomposition
- 💾 Model saving with versioning in Google Drive
- ✅ Ready to extend with multivariate modeling


## 📚 Dataset Info
Source: UCI Machine Learning Repository

Size: ~2 million rows (minute-level records from 2006 to 2010)

Target: Global_active_power

## ✨ Future Work
Add multivariate forecasting with external regressors

Integrate anomaly detection

Deploy best model with Streamlit or Flask

## 📬 Contact
Feel free to connect on LinkedIn or raise an issue if you'd like to collaborate or have questions.

