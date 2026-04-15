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
 <img width="1280" height="450" alt="10" src="https://github.com/user-attachments/assets/cbf3045b-13b8-4c8f-aebb-07f80adb9281" />

---

### 🔗 Crash Timing
- Peak accident hour: **17 (5 PM)** — Rush hour  
- Lowest accident hour: **4 AM** — Minimal traffic  
- Accidents occur throughout **all days and months**
- <img width="1280" height="450" alt="1" src="https://github.com/user-attachments/assets/53093dbf-0496-4406-aa3f-de6bc2dc0075" />

---

## 💥 Damage Severity Distribution

- Most crashes fall under **Over $1,500** damage, showing that a large share of incidents are financially significant.
- **$501–$1,500** is the second most common range.
- **$500 or less** is the least common among the main damage categories.
- This suggests many crashes lead to moderate to high property loss, not just minor damage.
- <img width="900" height="600" alt="12" src="https://github.com/user-attachments/assets/4c25c99f-976f-4162-add8-9eaa75cc9f11" />
---

## 🚗 Primary Contributory Causes (Top Causes)

- The most common category is **Unable to Determine**, which suggests many cases lack a clear reported cause.
- Among identified causes, **Failing to Yield Right-of-Way** and **Following Too Closely** are major contributors.
- **Disregarding Traffic Signals** and **Failing to Reduce Speed to Avoid a Crash** also appear frequently.
- These results highlight driver behavior as a major factor in accident occurrence.
  <img width="1200" height="800" alt="13" src="https://github.com/user-attachments/assets/5a67d8b5-8da0-4b8a-8654-6304cf2c271e" />

---
## ⚠️ Primary Contributory Causes (Least Common Causes)

- Rare causes include **Animal**, **Obstructed Crosswalks**, and **Passing Stopped School Bus**.
- **Motorcycle Advancing Legally on Red Light** appears as the least frequent category.
- These events occur far less often than common driver-related causes.
- This section shows that unusual road situations contribute to only a small share of crashes.

<img width="1200" height="800" alt="14" src="https://github.com/user-attachments/assets/ec25c673-02bf-46e4-b7cb-7e10ea93d052" />


---
## 📅 Crash Distribution by Month


- Crashes are highest in **October**, followed by **September** and **December**.
- The lowest counts appear in the early months, especially **February**.
- The chart suggests a seasonal pattern in accident frequency.
- Late-year months may have slightly higher risk due to traffic volume, weather, or travel activity.

  <img width="869" height="552" alt="15" src="https://github.com/user-attachments/assets/c71e0295-fad4-475d-8f88-362c66cf14bc" />

---

### 🔗 Weather Conditions
- Most accidents occur in **clear weather**
- Rain increases risk due to **slippery roads**
- Visibility alone does not prevent accidents  
<img width="1280" height="450" alt="3" src="https://github.com/user-attachments/assets/a0367cac-54d7-40fa-8d96-c722084dd898" />

---

### 🔗 Lighting Conditions
- Majority occur during **daylight**
- Night conditions still show significant accidents  
- Dusk/Dawn contribute due to **low visibility**
<img width="1280" height="450" alt="4" src="https://github.com/user-attachments/assets/fdb93487-38e8-419d-ae5f-38e40264a274" />

---

### 🔗 Traffic Control Devices
- Highest accidents at **traffic signals**
- Second highest at **stop signs**
- Accidents also occur where **no control devices exist**

<img width="1280" height="450" alt="newplot" src="https://github.com/user-attachments/assets/4e5e70ae-c2a1-424b-b3bd-e00d917ea766" />

---

### 🔗 Crash Types
- Most common: **Turning accidents**
- Other major types:
  - Angle crashes  
  - Rear-end collisions  
  - Sideswipe accidents
  - <img width="1000" height="600" alt="5" src="https://github.com/user-attachments/assets/3d1dd14d-78b7-4f6c-8b5b-669da748480b" />



---

### 🔗 Trafficway Type
- Highest accidents on **non-divided roads**
- Lower accidents on:
  - One-way roads  
  - Roads with median barriers
  - <img width="1200" height="800" alt="6" src="https://github.com/user-attachments/assets/6b7d6a63-6f0a-47f9-aa55-577b81ba867e" />

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
