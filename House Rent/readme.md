# 🏠 House Rental EDA Analysis

This project performs exploratory data analysis (EDA) on a dataset of house/apartment rentals in various Indian cities. It aims to uncover insights into rent patterns, locality impacts, furnishing trends, and other real estate features.

## 📊 Dataset Description

The dataset includes listings for rental properties with the following columns:

| Feature            | Description                                                                 |
|--------------------|-----------------------------------------------------------------------------|
| `BHK`              | Number of Bedrooms, Hall, and Kitchen                                        |
| `Rent`             | Monthly rent of the property                                                 |
| `Size`             | Area of the property in square feet                                          |
| `Floor`            | Floor information in format like "2 out of 5"                                |
| `Area Type`        | Type of area measurement (Super Area, Carpet Area, or Built Area)            |
| `Area Locality`    | Locality or neighborhood of the property                                     |
| `City`             | City where the property is located                                           |
| `Furnishing Status`| Furnishing condition: Furnished, Semi-Furnished, or Unfurnished              |
| `Tenant Preferred` | Type of tenants preferred (Family, Bachelors, etc.)                          |
| `Bathroom`         | Number of bathrooms in the property                                          |
| `Point of Contact` | Contact person or agency for the listing                                     |

---

🧰 Libraries Used
-> pandas

-> numpy

-> matplotlib

-> seaborn

-> jupyter

---

---

# 🏠 House Rental EDA Analysis

Exploratory Data Analysis on an Indian rental housing dataset. This project identifies trends in rent distribution, furnishing status, tenant preferences, and geographical factors influencing rental prices.

---

## 📌 Dataset Features

- **BHK** – Bedrooms, Hall, Kitchen
- **Rent** – Monthly rent
- **Size** – Size in square feet
- **Floor** – Format like “1 out of 4”
- **Area Type** – Super, Carpet or Built-up area
- **Locality** – Location of property
- **City** – City of listing
- **Furnishing Status** – Furnished / Semi / Unfurnished
- **Tenant Preferred** – Bachelors / Family / Company
- **Bathroom** – Number of bathrooms
- **Point of Contact** – Whom to contact

📄 [Dataset Glossary](https://github.com/MohithKumar8897/House-EDA-Analysis/blob/main/Dataset%20Glossary.txt)

---

## 📷 Visualizations

- 📊 **BHK vs City Rent**  
  ![BHK vs City](https://github.com/MohithKumar8897/House-EDA-Analysis/blob/main/BHK%20vs%20city.png?raw=true)

- 🧮 **Correlation between Rent, Size, BHK, Bathroom, Floor**  
  ![Correlation](https://github.com/MohithKumar8897/House-EDA-Analysis/blob/main/Correlation%20of%20rent%2Csize%2CBHKmbathroom%20and%20original_floor.png?raw=true)

- 🌆 **Average Rent by City**  
  ![City vs Rent](https://github.com/MohithKumar8897/House-EDA-Analysis/blob/main/Groupby%20city%20and%20rent.png?raw=true)

- 📈 **Histogram of Log Rent**  
  ![Histplot](https://github.com/MohithKumar8897/House-EDA-Analysis/blob/main/Histplot%20of%20log%20rent.png?raw=true)

- 👨‍👩‍👧‍👦 **Tenant Preference by City**  
  ![Tenant Preferred](https://github.com/MohithKumar8897/House-EDA-Analysis/blob/main/Tenant%20prefered%20vs%20city.png?raw=true)

---

## 📂 Files in the Repository

- `House EDA Analysis.ipynb` – Jupyter notebook with full analysis
- `House_Rent_Dataset.csv` – Dataset used
- `Dataset Glossary.txt` – Description of all columns
- Visualizations – Saved as PNGs
- `README.md` – Project documentation

---

## 💡 Key Findings

- Rent increases with the number of rooms (BHK) and size.
- Mumbai and Bangalore show significantly higher rents.
- Furnished properties demand more rent.
- Preferred tenants vary across cities.
- Outliers in rent were detected and log-transformed for better visualization.

---

