# Air Quality Prediction using Machine Learning

Predict air quality levels to help in pollution management and public health risk assessment.

## 📌 Problem Statement
Public health officials and citizens need accurate air quality forecasts to take preventive measures. Raw pollution data is hard to interpret. This project builds an ML model that predicts AQI levels and classifies risk as Good, Moderate, or Unhealthy.

## 🚀 Features
- Predicts Air Quality Index (AQI) based on pollutants: PM2.5, PM10, NO2, SO2, CO, O3
- Classifies air quality into 6 categories as per CPCB standards
- Data preprocessing pipeline for handling missing values and outliers
- Trained ML model with good accuracy for real-world use
- Helps in public health risk assessment and pollution control planning

## 🛠️ Tech Stack
- **Language**: Python
- **Libraries**: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
- **ML Algorithms**: Linear Regression, Random Forest, XGBoost - tested multiple models
- **Tools**: Jupyter Notebook, VS Code

## 📊 Dataset
- Source: Historical air quality data from CPCB / OpenAQ
- Features: PM2.5, PM10, NO2, SO2, CO, O3, Temperature, Humidity
- Target: AQI Value

## 📈 Results
- Best Model: Random Forest Regressor
- Accuracy/R2 Score: 0.89
