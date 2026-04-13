# 🔗 Traffic Accident Analysis & Prediction
### Data-Driven Insights for Road Safety Improvement

---

## 🔗 Project Overview
This project analyzes over **209,000+ traffic accident records** to uncover patterns, identify key risk factors, and generate actionable insights for improving road safety.

The analysis focuses on accident trends, severity, and contributing factors, while also preparing the dataset for future **machine learning models**.

---

## 🔗 Objectives
- Analyze traffic accident patterns over time  
- Identify key contributing factors  
- Study the impact of weather, lighting, and road conditions  
- Understand injury severity trends  
- Provide actionable safety recommendations  
- Prepare dataset for predictive modeling  

---

## 🔗 Dataset Summary
- **Total Records:** 209,306  
- **Total Features:** 24  
- **Data Quality:** No missing values  

### 🔗 Data Types
- **Categorical (object):** 14 columns  
- **Float (float64):** 6 columns  
- **Integer (int64):** 4 columns  

### 🔗 Key Features
- **Time:** `crash_date`, `crash_hour`, `crash_day_of_week`, `crash_month`  
- **Environment:** `weather_condition`, `lighting_condition`  
- **Road Conditions:** `trafficway_type`, `roadway_surface_cond`  
- **Severity Metrics:** `injuries_total`, `injuries_fatal`, `most_severe_injury`  
- **Contributing Factors:** `prim_contributory_cause`, `traffic_control_device`  

---

## 🔗 Exploratory Data Analysis (EDA)

### 🚗 Vehicles Involved
- Average vehicles per crash: **~2**
- Majority of accidents involve **two vehicles**

---

### 🔗 Injury Analysis
- Average injuries per crash: **0.38**
- Fatal injuries are **rare**
- Most accidents result in **minor or no injuries**

---

### 🔗 Crash Timing
- Peak accident hour: **17 (5 PM)** — Rush hour  
- Lowest accident hour: **4 AM** — Minimal traffic  
- Accidents occur throughout **all days and months**

---

### 🔗 Weather Conditions
- Most accidents occur in **clear weather**
- Rain increases risk due to **slippery roads**
- Visibility alone does not prevent accidents  

---

### 🔗 Lighting Conditions
- Majority occur during **daylight**
- Night conditions still show significant accidents  
- Dusk/Dawn contribute due to **low visibility**

---

### 🔗 Traffic Control Devices
- Highest accidents at **traffic signals**
- Second highest at **stop signs**
- Accidents also occur where **no control devices exist**

---

### 🔗 Crash Types
- Most common: **Turning accidents**
- Other major types:
  - Angle crashes  
  - Rear-end collisions  
  - Sideswipe accidents  

---

### 🔗 Trafficway Type
- Highest accidents on **non-divided roads**
- Lower accidents on:
  - One-way roads  
  - Roads with median barriers  

---

## 🔍 Key Insights
- Driver behavior is the **primary cause** of accidents  
- High traffic volume increases accident probability  
- Intersections are **high-risk zones**  
- Road design significantly impacts safety  
- Severe injuries are rare but critical  

---

## 🔗  Risk Factors
- Rush hour congestion  
- Driver fatigue and stress  
- Poor visibility (dusk/dawn)  
- Lack of traffic control  
- Unsafe turning and lane changes  

---

## 🔗 Recommendations
- Improve **traffic signal enforcement**  
- Enhance **road infrastructure (dividers, barriers)**  
- Increase **driver awareness campaigns**  
- Improve **lighting and visibility systems**  
- Optimize **intersection design**  

---

## 🔗 Tools & Technologies
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

---

## 🔗 Future Work
- Build models to predict:
  - Accident severity  
  - Injury probability  

### 🔗 Algorithms
- Logistic Regression  
- Random Forest  
- XGBoost  

---
