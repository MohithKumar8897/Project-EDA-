# 📈 Consumer Price Index (CPI) Analysis with Python

This project performs **Exploratory Data Analysis (EDA)** on the Consumer Price Index (CPI) dataset for India across different sectors (Rural, Urban, Rural+Urban). It reveals inflation trends, sectoral growth, seasonal impacts, and COVID-era fluctuations.

---

## 📊 Dataset Description

The dataset includes CPI data for various consumption categories across months and years.

| Feature                              | Description                                           |
|--------------------------------------|-------------------------------------------------------|
| `Sector`                             | Area category: Rural, Urban, or Rural+Urban           |
| `Year`                               | Year of the record                                    |
| `Month`                              | Month of the record                                   |
| `Cereals and products`               | CPI for cereals                                       |
| `Meat and fish`, `Egg`, `Milk` etc. | CPI values for respective food/non-food categories    |
| `Fuel and light`                     | CPI for energy consumption                            |
| `Housing`, `Clothing`, `Education`  | CPI for basic necessity categories                    |
| `General index`                      | Overall Consumer Price Index                          |

---

## 🧰 Libraries Used

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `statsmodels`
- `jupyter`

---

## 📷 Visualizations

- 🏙 **Average CPI Comparison Across Sectors**  
  ![Average CPI](https://github.com/MohithKumar8897/Consumer-Price-Index-Analysis-with-Python/blob/main/Average%20CPI%20Comparison%20Across%20Sectors%20(Rural%2C%20Urban%2C%20Rural%2BUrban).png)

- 📉 **CPI Trends During COVID-19 (2020-2021)**  
  ![COVID Trend](https://github.com/MohithKumar8897/Consumer-Price-Index-Analysis-with-Python/blob/main/CPI%20Trends%20During%20COVID-19%20Period%20(2020-2021).png)

- 📊 **CPI Trends for Selected Sectors**  
  ![Sector Trends](https://github.com/MohithKumar8897/Consumer-Price-Index-Analysis-with-Python/blob/main/CPI%20Trends%20for%20Selected%20Sectors.png)

- 📈 **Inflation Trend Analysis (General CPI Index)**  
  ![Inflation](https://github.com/MohithKumar8897/Consumer-Price-Index-Analysis-with-Python/blob/main/Inflation%20Trend%20Analysis%20(General%20CPI%20Index).png)

- 🔁 **Seasonal Decomposition of General CPI**  
  ![Decomposition](https://github.com/MohithKumar8897/Consumer-Price-Index-Analysis-with-Python/blob/main/Seasonal%20Decomposition%20of%20CPI%20(Observed%2C%20Trend%2C%20Seasonal%2C%20Residual).png)

- 🧮 **Correlation Between Categories and General Index**  
  ![Correlation](https://github.com/MohithKumar8897/Consumer-Price-Index-Analysis-with-Python/blob/main/Correlation%20between%20CPI%20Categories%20and%20General%20Index.png)

---

## 📂 Files in the Repository

- `Consumer Price Index Analysis with Python.ipynb` – Jupyter notebook with complete EDA
- `cpi.csv` – Dataset used for analysis
- `Dataset Glossary.txt` – Column-wise explanation
- `images/` – Folder with all saved PNG visualizations
- `README.md` – Project documentation

---

## 💡 Key Findings

-Overall Inflation Trend: There has been a steady increase in the CPI over the past decade, with inflation particularly rising after 2020.

-Minimal Seasonal Effect: The seasonal decomposition shows minimal seasonal fluctuations, indicating that CPI trends are mainly driven by long-term factors.

-Rural vs. Urban Impact: Inflation levels are consistent across rural, urban, and combined sectors, suggesting uniform price changes in these regions.

-Sectoral Correlations: High correlations are observed between sectors like housing, transport, and miscellaneous, indicating their significant impact on overall inflation, while categories like eggs 
 and vegetables show more independent price movements.

-Sector-Specific Trends: Fuel and light have experienced the steepest price increase, especially post-2020, while health and housing show steady inflation growth. Cereals and products display more 
 volatility.

-COVID-19 Impact (2020-2021): During the pandemic, fuel prices initially dropped due to lower demand, then surged in 2021. Health and housing sectors saw consistent price increases, reflecting 
 inflationary pressures on essential services during this period.
 
---

