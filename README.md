# 🌤️ US Air Quality Prediction System

An AI-powered web application developed using **Python**, **Machine Learning**, and **Streamlit** to predict the **Air Quality Index (AQI)** based on historical air pollution data. The application provides pollutant-level predictions, interactive analytics, health recommendations, and email-based air quality alerts.

> **Academic Project**  
> Developed as part of **IT3051 – Fundamentals of Data Mining** during **3rd Year, 1st Semester** at the **Sri Lanka Institute of Information Technology (SLIIT)**.


## 📌 Project Overview

Air pollution has become a major environmental and public health concern worldwide. This project leverages **Machine Learning** techniques to analyze historical air quality data and predict the **Air Quality Index (AQI)** for selected locations within the United States.

The system enables users to:
- Generate AQI predictions
- View pollutant-level forecasts
- Analyze pollution trends
- Receive health recommendations based on predicted air quality
- Send air quality alerts via email


## ✨ Features

- 🌍 Location-based Air Quality Prediction
- 📊 Air Quality Index (AQI) Prediction
- 🧪 Pollutant-Level Prediction
  - Ozone (O₃)
  - Carbon Monoxide (CO)
  - Sulfur Dioxide (SO₂)
  - Nitrogen Dioxide (NO₂)
- 📈 Interactive Analytics Dashboard
- 💡 Personalized Health Recommendations
- 📧 Email Alert System
- 🖥️ Interactive Streamlit Web Interface


## 🛠️ Technologies Used

- Python
- Streamlit
- Scikit-learn
- Pandas
- NumPy
- Matplotlib
- Machine Learning
- Data Mining


## 🧠 Machine Learning Model

The application utilizes a **Random Forest Regressor** to predict pollutant values and estimate the Air Quality Index (AQI).

### Data Preprocessing
- Data cleaning
- Missing value handling
- Date feature extraction
- One-Hot Encoding for categorical variables
- Feature engineering

### Model Evaluation Metrics
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score


## 📂 Project Structure

```text
air_quality_app/
│
├── app.py
├── preprocess.py
├── train_model.py
├── requirements.txt
├── README.md
│
├── data/
│   └── US_air_pollution_dataset_2000_2023.csv
│
├── models/
│   ├── air_quality_model.pkl
│   └── label_encoder.pkl
│
├── tabs/
│   ├── input_tab.py
│   ├── prediction_tab.py
│   ├── analytics_tab.py
│   ├── advice_tab.py
│   └── alerts_tab.py
│
└── .streamlit/
```


## 🚀 Installation

Clone the repository:
git clone https://github.com/BinadiSilva/air_quality_app.git

Navigate into the project directory:
cd air_quality_app

Create a virtual environment:
python -m venv venv

Activate the virtual environment:

### Windows
venv\Scripts\activate

### macOS / Linux
source venv/bin/activate

Install dependencies:
pip install -r requirements.txt

Run the application:
streamlit run app.py

The application will be available at:
http://localhost:8501


## 📷 Application Preview

### Home Dashboard

- User-friendly interface for AQI prediction and environmental monitoring.

### Input Features

- Select State
- County
- City
- Date

### Prediction Module

Displays:

- Overall AQI
- Air Quality Category
- Pollutant Predictions

### Analytics Dashboard

Interactive visualizations of:

- AQI Trends
- Pollutant Comparisons
- Historical Analysis

### Advice Module

Provides personalized health recommendations based on predicted AQI.

### Alerts Module

Allows users to upload an email list and send air quality advisory notifications.


## 📊 Dataset

Dataset:

**US Air Pollution Dataset (2000–2023)**

The dataset contains historical air quality information including:

- State
- County
- City
- Date
- Pollutant Measurements
- AQI Values


## 🎯 Learning Outcomes

This project enhanced my practical knowledge in:

- Data Mining
- Machine Learning
- Data Preprocessing
- Feature Engineering
- Model Evaluation
- Data Visualization
- Streamlit Application Development
- Predictive Analytics


## 🔮 Future Improvements

- Real-time AQI prediction using live weather and pollution APIs
- Deep Learning models for improved prediction accuracy
- Interactive geographic visualization
- User authentication
- Cloud deployment
- Mobile-responsive interface


## 📜 License

This project was developed for educational purposes as part of the **IT3051 – Fundamentals of Data Mining** module at **SLIIT**.
