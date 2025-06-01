# 🌧️ Rainfall Trends in India (1901–2015) – Exploratory Data Analysis with Python

## 🧩 Problem Statement

India's economy and agriculture are highly dependent on rainfall, particularly during the monsoon season. Understanding the long-term trends, variability, and anomalies in rainfall is crucial for sustainable agricultural practices, water resource management, and climate adaptation strategies.

This project focuses on analyzing historical rainfall data from 1901 to 2015 in India to:

- Identify long-term rainfall trends and seasonal variations.
- Detect anomalous rainfall events and patterns.
- Understand correlations between different seasonal periods.
- Analyze the impact of climate change on rainfall distribution.
- Forecast future rainfall using machine learning techniques.

---

## 📂 Dataset

The dataset used is:
- **File**: `rainfall_area-wt_India_1901-2015.csv`
- **Description**: Annual, monthly, and seasonal area-weighted rainfall data for India from 1901 to 2015.

---

## 📁 Files in the Repository

| File | Description |
|------|-------------|
| `rainfall_area-wt_India_1901-2015.csv` | Historical rainfall dataset |
| `Rainfall Trends in India Analysis with Python.ipynb` | Complete EDA and model notebook |
| `.png` Files | Visual insights and charts from the analysis |

---

## 🔍 Key Exploratory Analyses and Visualizations

### 📈 1. Trend in Annual Rainfall (1901–2015)
![Trend](https://github.com/MohithKumar8897/Project-EDA-/raw/main/Rainfall%20Trends%20in%20India%20Case%20Study/Trend%20in%20Annual%20Rainfall%20in%20India%20(1901-2015).png)

- Shows the fluctuating nature of rainfall with a near-constant average.

---

### 🌦️ 2. Average Monthly Rainfall
![Monthly Average](https://github.com/MohithKumar8897/Project-EDA-/raw/main/Rainfall%20Trends%20in%20India%20Case%20Study/Average%20Monthly%20Rainfall%20in%20India%20(1901-2015).png)

- July and August contribute the most to annual rainfall.

---

### ☀️ 3. Seasonal Rainfall Distribution
![Seasonal Distribution](https://github.com/MohithKumar8897/Project-EDA-/raw/main/Rainfall%20Trends%20in%20India%20Case%20Study/Seasonal%20Rainfall%20Distribution%20in%20India%20(1901-2015).png)

- Monsoon (Jun–Sep) dominates the yearly rainfall profile.

---

### 📉 4. Climate Change Impact
![Climate Impact](https://github.com/MohithKumar8897/Project-EDA-/raw/main/Rainfall%20Trends%20in%20India%20Case%20Study/Impact%20of%20Climate%20Change%20on%20Rainfall%20Patterns%20(1901-2015).png)

- 10-year moving average shows a slight post-1960 decline, indicating climate variability.

---

### 🚨 5. Anomaly Detection

#### a. Annual Anomalies
![Annual Anomalies](https://github.com/MohithKumar8897/Project-EDA-/raw/main/Rainfall%20Trends%20in%20India%20Case%20Study/Annual%20Rainfall%20Anomalies%20in%20India%20(1901-2015).png)

#### b. Monthly Anomalies
![Monthly Anomalies](https://github.com/MohithKumar8897/Project-EDA-/raw/main/Rainfall%20Trends%20in%20India%20Case%20Study/Monthly%20Rainfall%20Anomalies%20in%20India%20(1901-2015).png)

- Isolation Forest algorithm used to identify extreme years and months.

---

### 🔗 6. Correlation Analysis
![Correlation](https://github.com/MohithKumar8897/Project-EDA-/raw/main/Rainfall%20Trends%20in%20India%20Case%20Study/Correlation%20Between%20Monsoon%20(Jun-Sep)%20Rainfall%20and%20Other%20Seasons.png)

- Monsoon rainfall highly correlates (0.93) with annual rainfall.

---

### 🔄 7. Clustering Rainfall Patterns
![Clustering](https://github.com/MohithKumar8897/Project-EDA-/raw/main/Rainfall%20Trends%20in%20India%20Case%20Study/Clustering%20of%20Years%20Based%20on%20Rainfall%20Patterns.png)

- K-Means used to label years into Dry, Normal, and Wet categories.

---

### 🔮 8. Rainfall Forecast Using Prophet
![Forecast](https://github.com/MohithKumar8897/Project-EDA-/raw/main/Rainfall%20Trends%20in%20India%20Case%20Study/Annual%20Rainfall%20Forecast%20Using%20Prophet.png)

- Facebook Prophet used to predict future annual rainfall.

---

## ✅ Conclusion

The analysis of India’s rainfall trends and patterns from 1901 to 2015 reveals significant variability in annual and seasonal rainfall, with the monsoon season (June-September) being the dominant contributor. Anomalous years of extreme drought and wetness highlight the unpredictability of rainfall, while clustering shows a shift towards more dry years in recent decades. Correlations indicate the limited dependency of non-monsoon seasons on monsoon rainfall. A time-series forecast using Prophet suggests a slight declining trend in annual rainfall, which emphasises the need for long-term water resource planning and adaptation to changing climate patterns.
---

