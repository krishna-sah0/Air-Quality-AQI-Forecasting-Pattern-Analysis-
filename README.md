

# 🌫️ Air Quality Analysis & Forecasting (2017–2023)

### **Using EDA • Time-Series Forecasting • Clustering • AI Seasonal Insights**

This project analyzes air pollution trends for **Noida, India** (2017–2023) using multiple data science and machine learning techniques.
The dataset is sourced from **Urban Emissions** (India NCAP AQI Database).

---

## 📁 **Project Structure**

```
├── Task1_EDA.ipynb
├── Task2_AQI_forecasting.ipynb
├── Task3_AQI_Clustering.ipynb
├── Task4_AQI_Seasonal_Analysis.ipynb
├── Noida_AQIBulletins.csv
└── README.md
```

---

# 🚀 **Tasks Overview**

## ✅ **Task 1 — Exploratory Data Analysis (EDA)**

**Objectives:**

* Plot time-series trends of AQI (Index Value)
* Detect missing or abnormal values
* Analyze pollutant distribution

**Outputs:**

* Time-series AQI trend plot
* Prominent pollutant frequency bar chart
* Data quality check (missing/abnormal readings)

<img width="1979" height="980" alt="Time-Series Trend of Index Value (Noida)" src="https://github.com/user-attachments/assets/b38c52dd-6395-4acf-a459-4fb5b9f8ede7" />

<img width="1979" height="980" alt="Distribution of Prominent Pollutant (Noida)" src="https://github.com/user-attachments/assets/2ea7176c-0452-44fa-89aa-655babc3e8df" />


---

## ✅ **Task 2 — Supervised Learning (AQI Forecasting)**

### **Goal:**

Predict **next-day AQI** using time-series supervised learning with lag features.

### **Steps:**

* Converted data into daily time-series
* Prepared **7-day windowed lag dataset**
* Implemented 3 forecasting models:

  * 📌 Persistence (Naive Model)
  * 📌 Linear Regression
  * 📌 Random Forest Regressor
* Evaluated with:

  * MAE
  * RMSE
  * MAPE%

### **Outputs:**

* Predicted vs Actual AQI plot
* Model performance table
* Forecasting notebook

---
<img width="2369" height="979" alt="Predicted vs Actual Index Value (Last 120 days of Test Set) Task 2" src="https://github.com/user-attachments/assets/fc9e20b1-0173-4e9f-aedd-881c028ab1a3" />




## ✅ **Task 3 — Unsupervised Learning (Clustering)**

**Goal:** Cluster days into pollution categories using K-Means.

### **Cluster Labels**

| Cluster | Pollution Level | AQI Range |
| ------- | --------------- | --------- |
| 0       | Low             | 30–165    |
| 1       | Moderate        | 166–294   |
| 2       | High            | 295–500   |

### **Outputs**

* Scatter plot of AQI clusters over time
* Cluster distribution bar chart
* Cluster interpretation summary

---

<img width="1979" height="980" alt="Pollution Clusters Based on Index Value Task 3" src="https://github.com/user-attachments/assets/1bcc3faf-f6b4-47e0-88f6-b7f50075b25c" />

<img width="1180" height="780" alt="Distribution of Pollution Clusters Task 3" src="https://github.com/user-attachments/assets/1590d47e-2381-4a07-9518-59318170c935" />


## ✅ **Task 4 — AI Seasonal Pollution Pattern Detector**

**Goal:** Identify seasonal pollution patterns and generate automated insights.

### **Steps:**

* Calculated monthly average AQI
* Categorized each month:

  * Clean
  * Moderate
  * High Pollution
* Identified consistently high-pollution months
* Generated automated seasonal insights

### **Outputs:**

* Monthly AQI Line Chart
* Pollution Category Bar Chart
* AI-Generated Insight Example:

> **High pollution months typically occur during: November, December, January.**

---

<img width="2379" height="980" alt="Monthly Average Pollution Levels Task" src="https://github.com/user-attachments/assets/dcf59d24-22a1-4b81-be9b-4f0b19af53ff" />

<img width="1979" height="780" alt="Counts of Monthly Pollution Categories Task 4" src="https://github.com/user-attachments/assets/4c477c90-18ec-4d65-9ecb-23e22dba088a" />


# 📊 **Key Visual Outputs**

✔ Time-series AQI trend
✔ AQI forecasting curve (actual vs predicted)
✔ Pollution clusters visualized
✔ Monthly seasonal pattern trends

*(Plots available inside each notebook)*

---

# 📦 **Dataset**

Source: **Urban Emissions (India NCAP AQI Database)**
Years Covered: **2017 – 2023**
City Selected: **Noida**

### Columns:

* Date
* City
* No. of Stations
* Air Quality Category
* Index Value
* Prominent Pollutant

---

# 🛠️ **Technologies Used**

| Category      | Tools                            |
| ------------- | -------------------------------- |
| Programming   | Python, NumPy, Pandas            |
| Visualization | Matplotlib                       |
| ML Models     | Scikit-Learn                     |
| Clustering    | KMeans                           |
| Forecasting   | Linear Regression, Random Forest |
| Environment   | Jupyter Notebook                 |

---

# 🔮 **Future Improvements**

* LSTM deep-learning forecasting
* Multi-city pollution comparison
* Feature-rich AQI prediction (weather, pollutant levels)
* Dashboard using Streamlit / PowerBI

---

# 🙌 **Acknowledgements**

* Dataset: [https://urbanemissions.info](https://urbanemissions.info)
* Tools: Python, Scikit-Learn, Matplotlib
* Project developed for Machine Learning & Data Analysis coursework

---

