# 💹 Inflation Impact Analysis with Python

This project presents an in-depth **Exploratory Data Analysis (EDA)** of inflation trends in **India** and the **United States** and their influence on the **USD to INR exchange rate** from 1980 to 2024. It aims to quantify and visualize the relationship between macroeconomic indicators like inflation and foreign exchange rates, utilizing both **actual data** and **theoretical models** like **Purchasing Power Parity (PPP)**.

---

## 📊 Dataset Overview

The analysis uses two preprocessed datasets:

### 📁 1. Inflation Data (`Inflation_Rates_Transformed-1.csv`)

| Column         | Description                                       |
|----------------|---------------------------------------------------|
| `Country`      | Name of the country (`India` or `United States`)  |
| `Year`         | Calendar year of observation                      |
| `Inflation Rate` | Annual inflation rate (%)                       |

### 📁 2. Exchange Rate Data (`USD_INR_Exchange_Rates_1980_2024.csv`)

| Column                          | Description                                        |
|----------------------------------|----------------------------------------------------|
| `Year`                           | Calendar year of observation                       |
| `Average Exchange Rate (INR/USD)` | Yearly average rate of Indian Rupee per US Dollar  |

---

## 🧰 Tools & Technologies

- **Python**
- **Jupyter Notebook**
- **Pandas, NumPy** – data wrangling and processing  
- **Matplotlib, Seaborn** – visualizations  
- **Statsmodels** – trend analysis and forecasting  

---

## 🔍 Core Analyses Performed

### 📈 1. Inflation Rate Trends: India vs United States  
Analyzes how inflation patterns have evolved in both economies from 1980–2024.

- India shows consistently higher inflation than the US.
- Periods of economic stress (like 1991 crisis, 2008 recession, COVID-19) show visible inflation volatility.

📊 *Visualization*:  
![Comparative Inflation](https://github.com/MohithKumar8897/Inflation-Impact-Analysis-with-Python/blob/main/Comparative%20Analysis%20Exchange%20Rate%20vs%20Inflation%20Rates%20(India%20%26%20US).png)

---

### 🔄 2. USD to INR Exchange Rate Evolution  
Tracks the weakening of the Indian Rupee over time relative to the US Dollar.

- INR depreciated from ~₹8/USD in 1980 to ~₹83/USD by 2024.
- Major devaluation phases: 1991 liberalization, 2008 global crisis, post-COVID.

📈 *Visualization*:  
![Trends](https://github.com/MohithKumar8897/Inflation-Impact-Analysis-with-Python/blob/main/Trends%20of%20Exchange%20Rate%20and%20Inflation%20Rates.png)

---

### 🧮 3. Purchasing Power Parity (PPP) Model – Expected Exchange Rate  
PPP posits that the exchange rate between two countries should equal the ratio of their price levels (inflation-adjusted). This analysis calculates the *expected* INR/USD rate using cumulative inflation differentials and compares it to the *actual* exchange rate.

**PPP Exchange Rate Formula**:

\[
E_t = E_0 \times \left(\frac{1 + \text{India's cumulative inflation}}{1 + \text{US's cumulative inflation}}\right)
\]

- Large deviations observed in recent decades.
- Reflects external factors: interest rates, capital flows, monetary policy, market speculation.

📉 *Visualization*:  
![PPP](https://github.com/MohithKumar8897/Inflation-Impact-Analysis-with-Python/blob/main/Actual%20vs%20Expected%20Exchange%20Rate%20(PPP).png)

---

## 💡 Key Insights & Conclusions

- **Persistent Depreciation of INR**: The long-term decline in INR value aligns with sustained inflation gaps between India and the US.
  
- **Short-Term Divergences**: The actual exchange rate often diverges from PPP predictions due to short-term capital movements, policy changes, and geopolitical risks.

- **Structural Breaks in 1991 and 2008**: Liberalization and global crises significantly impacted inflation and forex volatility.

- **India’s Higher Inflation**: Structural factors like supply chain inefficiencies, subsidies, and demand-led growth contribute to India’s higher average inflation.

- **PPP as a Long-Term Indicator**: While the model fails in short-term forecasting, it helps identify currency misalignment over decades.

---

## 📂 Repository Contents

| File                                      | Description                                              |
|-------------------------------------------|----------------------------------------------------------|
| `Inflation Impact Analysis with Python.ipynb` | Main Jupyter notebook with full analysis and charts      |
| `Inflation_Rates_Transformed-1.csv`      | Cleaned inflation dataset for India and the US           |
| `USD_INR_Exchange_Rates_1980_2024.csv`   | Annual INR/USD exchange rates                            |
| PNG Files (charts)                       | Graphical insights stored as static images               |
| `README.md`                              | Project documentation                                    |

---

## 🔗 Project Links (Live on GitHub)

- 📘 [Notebook – Full Analysis](https://github.com/MohithKumar8897/Inflation-Impact-Analysis-with-Python/blob/main/Inflation%20Impact%20Analysis%20with%20Python.ipynb)
- 📁 [Inflation Data](https://github.com/MohithKumar8897/Inflation-Impact-Analysis-with-Python/blob/main/Inflation_Rates_Transformed-1.csv)
- 📁 [Exchange Rate Data](https://github.com/MohithKumar8897/Inflation-Impact-Analysis-with-Python/blob/main/USD_INR_Exchange_Rates_1980_2024.csv)
- 🖼 [Trends Graph](https://github.com/MohithKumar8897/Inflation-Impact-Analysis-with-Python/blob/main/Trends%20of%20Exchange%20Rate%20and%20Inflation%20Rates.png)
- 📊 [PPP Deviation Plot](https://github.com/MohithKumar8897/Inflation-Impact-Analysis-with-Python/blob/main/Actual%20vs%20Expected%20Exchange%20Rate%20(PPP).png)
- 📈 [Comparative Inflation Analysis](https://github.com/MohithKumar8897/Inflation-Impact-Analysis-with-Python/blob/main/Comparative%20Analysis%20Exchange%20Rate%20vs%20Inflation%20Rates%20(India%20%26%20US).png)

---

> 👨‍💻 **Author**: Mohith Kumar  
> 📅 **Project Year**: 2025  
> 🏫 **Institution**: Imarticus Learning  
> 📈 **Tags**: Inflation, Exchange Rate, EDA, PPP, Macroeconomics, INR, USD

