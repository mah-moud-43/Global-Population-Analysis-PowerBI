# 🌍 Global Population Analysis - Power BI Project

This project is a **Power BI** dashboard analyzing the **world population** across different countries based on growth projections for **2025** and **2050**.

---

## 📊 Dataset Description

The dataset includes the following columns:

- `country`: Country name  
- `pop2025`: Estimated population in 2025  
- `pop2050`: Estimated population in 2050  
- `area`: Total area of the country  
- `landAreaKm`: Land area in square kilometers  
- `cca2`: 2-letter country code  
- `cca3`: 3-letter country code  
- `density`: Population density  
- `growthRate`: Annual growth rate (%)  
- `worldPercentage`: Country’s population as a percentage of world population  
- `rank`: Population rank  
- `growthRateCategory`: Categorized growth rate (e.g. High, Medium, Low)

---

## 🧹 Data Cleaning

- The data was cleaned and pre-processed using **Google Colab**.
- Missing values were handled.
- We discovered that:
  - The `cca2` column has only **one unique null/empty value**.
  - The **average population growth rate** was computed and used for visualization.

---

## 🌟 Key Insights

- Countries with the **highest population**:  
  - 🇮🇳 India  
  - 🇨🇳 China  
  - 🇺🇸 United States  
  - 🇮🇩 Indonesia  
  - 🇵🇰 Pakistan

- Categories were created to classify countries by **growth rate**.
- Used **Power BI slicers** for interactive filtering:
  - Year (2025/2050)
  - Country
  - Growth Rate Category
  - Density Range
  - Continent (if added later)
  - Top 10 Population
  - Growth % range
  - Area or Land Area range

---

## 📁 Files Included

- `GlobalPopulation.pbix`: The Power BI dashboard file
- `population_data.csv`: The dataset used
- `README.md`: Project description and insights

---

## 🧠 Author

Mahmoud Hani  
AI Student | Data Analyst | Power BI Developer  
