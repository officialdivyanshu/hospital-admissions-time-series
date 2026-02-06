# Time Series Analysis on Hospital Admissions (ARIMA Forecasting)

## 📌 Project Overview
This project performs end-to-end **Time Series Analysis** on hospital-related datasets (Admissions, Mortality, Pollution) to understand patterns over time and forecast future values using the **ARIMA model**.

The workflow follows standard Data Science steps:
- Data loading & preprocessing  
- Time series visualization  
- Stationarity testing (Rolling Mean + ADF Test)  
- Data transformation (log, differencing)  
- Model building (ARIMA)  
- Forecasting  
- Model evaluation (RMSE, MAE)

This project is implemented using **Python in Google Colab**.

---

## 📂 Dataset Description
The datasets used in this project:
- `HDHI_Admission_data.csv` – Daily hospital admissions  
- `HDHI_Mortality_Data.csv` – Mortality counts  
- `HDHI_Pollution_Data.csv` – Pollution indicators  
- `table_headings.csv` – Column description / metadata (reference)

> Note: The datasets are included in the `/data` folder for reproducibility.

---

## 🧠 Problem Statement
To analyze hospital admission trends over time, identify:
- Trend  
- Seasonality  
- Cyclic patterns  
- Irregular components  

And to build a **forecasting model (ARIMA)** that predicts future hospital admissions.

---

## ⚙️ Tech Stack
- Python  
- Google Colab  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Statsmodels  
- Scikit-learn  

---

## 🧪 Methodology

1. **Data Collection**  
   Load CSV datasets into Colab.

2. **Data Preprocessing**  
   - Convert date column to datetime  
   - Handle missing values  
   - Sort by date  
   - Set date as index  

3. **Exploratory Data Analysis (EDA)**  
   - Plot time series  
   - Observe trends and seasonality  

4. **Stationarity Check**  
   - Rolling mean & rolling std  
   - Augmented Dickey-Fuller (ADF) test  

5. **Data Transformation**  
   - Log transformation  
   - Differencing to make series stationary  

6. **Model Building**  
   - ARIMA model selection and training  

7. **Forecasting**  
   - Predict future values  
   - Plot actual vs forecast  

8. **Evaluation**  
   - RMSE  
   - MAE  

---

## 📈 Results
The ARIMA model successfully captures the underlying time series structure and provides reasonable forecasts for hospital admissions.

---

## ▶️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/time-series-project.git
