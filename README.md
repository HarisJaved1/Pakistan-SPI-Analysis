# Pakistan-SPI-Analysis
Inflation in Pakistan is hitting record highs. I analyzed 3 years of weekly price data to find what’s really driving costs

# 📊 Pakistan SPI (Sensitive Price Index) Analysis (2023–2025)

This project analyzes Pakistan's **Sensitive Price Index (SPI)** data, covering weekly price changes across cities and commodities from **2023 to August 2025**.  
It provides insights into inflation drivers, city-level affordability, and commodity price volatility, with plans for interactive dashboards and forecasting.

---

## 🎯 Project Goals
- Identify **key inflation drivers** over time
- Compare **city-level affordability**
- Analyze **volatility vs. stability** of essential goods
- Build **dashboards and predictive models** for better decision-making

---

## 🗂️ Dataset Overview

| Column Name     | Description                                  |
|-----------------|----------------------------------------------|
| Date            | Weekly date of price observation             |
| City            | City where data was collected                |
| Item            | Commodity/item name                          |
| Avg_Price       | Average retail price                         |
| Min_Price       | Minimum price observed                       |
| Max_Price       | Maximum price observed                       |
| Unit            | Measurement unit (e.g., per kg, per dozen)   |

✅ **Rows:** ~XX,XXX  
✅ **Time Period:** 2023-01 to 2025-08  
✅ **Cities Covered:** XX  
✅ **Items Covered:** XX  

---

## 🧹 Data Collection & Cleaning

1. Collected SPI reports from **Pakistan Bureau of Statistics (PBS)**.  
2. Converted **PDF annexures to Excel**, then merged into a single CSV.  
3. Fixed date formatting, duplicate entries, and inconsistent item names.  
4. Standardized units and ensured dataset consistency.  

Result: A **clean, analysis-ready dataset**.

---

## 🔍 Exploratory Analysis

Key analysis performed:
- **Trend Analysis:** Month-over-month (MoM) and year-over-year (YoY) inflation
- **City Comparisons:** Ranking cities by overall affordability
- **Volatility Analysis:** Identifying items with extreme price fluctuations
- **Heatmaps & Charts:** Commodity and city-level visual insights

---

## 💡 Key Insights (Aug 2025)

1️⃣ **Luxury & Utility Costs Are Driving Inflation**  
- Ladies Sandal (Bata) prices surged **+52.5% YoY**  
- Gas Charges for Q1 rose **+38.3% YoY**

2️⃣ **Sugar & Protein Are Becoming Expensive**  
- Sugar (Refined): **+17.4% YoY**  
- Beef with Bone: **+14.7% YoY**

3️⃣ **Islamabad is the Most Expensive City; Quetta Needs Investigation**  
- Islamabad avg price: **₨646.7**  
- Quetta’s **₨33.9** avg suggests a **data anomaly**

4️⃣ **Energy Products Show Extreme Volatility**  
- Gas, LPG, Wheat Flour Bags, and Cooking Oil fluctuate **>₨600**

5️⃣ **Some Items Remain Price-Stable**  
- Telephone charges, electricity, salt, and matchboxes remain stable

---

## 🚀 Next Steps

🔹 Build an **interactive Power BI dashboard** with filters and trendlines  
🔹 Add **time-series forecasting** for volatile commodities  
🔹 Publish final insights as a **LinkedIn article** and GitHub project  

---

## 🛠️ Tech Stack

- **Python:** pandas, matplotlib, seaborn  
- **Jupyter Notebook:** Analysis & visuals  
- **Power BI:** Dashboard (planned)  
- **Data Source:** [Pakistan Bureau of Statistics](https://www.pbs.gov.pk/)  

---

## 📷 Sample Visuals

_(Screenshots of your key charts will go here — add once you’ve exported visuals from your notebook!)_

---

## 📌 About This Project

This project was built as part of a **data analytics internship** and extended as a **portfolio project** to demonstrate:  
- Data wrangling and cleaning skills  
- Advanced analysis and visualization techniques  
- Real-world relevance by focusing on Pakistan’s economy

