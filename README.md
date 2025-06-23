# 🚲 Cross-City Bike Sharing Demand Modeling

📘 **Course Project**  
Topic: **Multicontextual Analysis and Optimization of Bike Sharing Systems with Cross-City Correlation**  
Field: Data Science, Predictive Modeling  
Languages: Python  
Semester: [Specify if needed]

---

## 📌 Overview

This project analyzes urban bike sharing systems using public datasets from cities like **Seoul** and **London**, aiming to understand and model how external factors—such as weather, seasonality, holidays, and day of week—influence rental demand. A special focus is placed on exploring **whether predictive models built on one city (e.g., Seoul) can generalize to others (e.g., London)** and on evaluating the performance of integrated multi-city models.

---

## 🎯 Project Goals

- Identify the **key factors** influencing bicycle rental demand across cities.
- Test whether **models trained on one city** can predict demand in another.
- Analyze **temporal and seasonal patterns** in bicycle usage.
- Develop and compare **individual vs. integrated (multi-city) predictive models**.

---

## ⚙️ Methodology

### 1. 📥 Data Collection
- Public datasets for bike rentals in **Seoul** and **London**.
- Includes rental count, temperature, humidity, wind speed, seasons, weekdays, and holidays.

### 2. 🧼 Data Preprocessing
- Standardization of numerical variables.
- One-hot encoding of categorical features.
- Handling of missing values via imputation or removal.

### 3. 📊 Exploratory Data Analysis (EDA)
- Distribution of rentals across weather/season/time.
- Correlation analysis between features and demand.
- Cross-city comparison of patterns and feature impact.

### 4. 🤖 Modeling
- Machine learning models used:
  - Linear Regression
  - XGBoost
  - Random Forest
- Evaluation via:
  - **RMSE** (Root Mean Squared Error)
  - **Adjusted R²**
- Building both:
  - **City-specific models**
  - **Integrated model** using data from both cities

---

## 🧪 Evaluation Criteria

- Model performance on Seoul vs. London datasets
- RMSE and adjusted R² comparison
- Effectiveness of cross-city prediction
- Does integrated model outperform individual ones?

---

## 🛠 Technologies Used

- **Python 3**
- **Pandas**, **NumPy** – data manipulation
- **Scikit-learn** – ML models and metrics
- **XGBoost**, **RandomForest**
- **Matplotlib**, **Seaborn** – visualization

---

## 📚 Data Sources

- [Seoul Bike Sharing Demand (UCI)](https://archive.ics.uci.edu/dataset/560/seoul+bike+sharing+demand)  
- [London Bike Sharing Dataset (Kaggle)](https://www.kaggle.com/datasets/hmavrodiev/london-bike-sharing-dataset)  
- [Kaggle Competition Example](https://www.kaggle.com/competitions/bike-sharing-demand/code)  
- [Reference Implementation](https://github.com/sinhabishal77/Kaggle-Bike-Sharing-Demand)

---

## 📈 Future Improvements

- Include more cities for stronger generalization
- Incorporate additional contextual features (e.g., events, pollution)
