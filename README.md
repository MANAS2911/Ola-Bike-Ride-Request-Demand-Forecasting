# 🛵 Ola Bike Ride Request Demand Forecasting

A machine learning-powered forecasting system built using Python that predicts the hourly demand for Ola bike ride bookings based on various environmental and temporal factors. The system performs data preprocessing, feature engineering, regression modeling, and EDA visualizations to uncover patterns in bike rental behavior, enabling efficient resource allocation and fleet optimization.

---

## 🚀 Features

- 📊 Exploratory Data Analysis (EDA) on weather, season, time of day, and user type patterns.
- 🧠 Regression modeling using Linear Regression and Stacked Ensemble techniques.
- 📈 Achieved reliable RMSLE performance on both working and non-working days.
- 📅 Hourly, daily, monthly, and seasonal rental trend analysis.
- 🎛️ Custom feature engineering pipeline for time-based and categorical data.
- 📌 Heatmap and regression plot visualizations for correlation analysis.
- 🗂️ Separate model evaluations for working days vs non-working days.
- 📈 RMSLE metric-based model evaluation and optimization.

---

## 📁 Project Structure

Ola-Bike-Demand-Forecasting/
│
├── dataset/                      # Input dataset (bike_rentals.csv)
├── eda_visualizations/           # Generated EDA plots and graphs
├── model/                        # Saved trained models
├── src/
│   ├── data_preprocessing.py     # Data cleaning and transformation scripts
│   ├── feature_engineering.py    # Custom feature creation logic
│   ├── train_model.py            # Model training and stacking ensemble code
│   ├── evaluate_model.py         # Model evaluation and RMSLE computation
│
├── requirements.txt              # Dependencies
└── README.md                     # Project documentation

---

## 📊 Model Details

The forecasting system uses:
- Linear Regression models for hourly demand prediction.
- Stacked ensemble models to refine predictions using Level-1 model outputs.
- Root Mean Square Log Error (RMSLE) as the evaluation metric for all models.
- Split-specific models for Working Days and Non-Working Days to improve accuracy.

---

## 📈 Data Insights & Visualizations

- 📅 Peak demand on working days occurs at 8 AM and 5 PM, aligned with office commutes.
- 🛣️ Non-working days show steady demand throughout the day with a noon peak.
- 🌤️ Rentals highest in clear weather and during Fall and Summer seasons.
- 🌡️ Demand rises with temperature (32°C–36°C ideal for biking) and falls with high humidity.
- 📊 Correlation analysis reveals strong positive influence of temperature on rentals and negative influence of humidity.

---

## 🙋‍♂️ Author

Manas Choudhary,
Final Year Computer Engineering Student,
Project: Ola Bike Ride Demand Forecasting System

Feel free to connect on [LinkedIn](www.linkedin.com/in/contactmanaschoudhary) or raise an issue or PR.

---

## ⭐ Star This Repository
If you like this project, give it a ⭐ to help others find it!
