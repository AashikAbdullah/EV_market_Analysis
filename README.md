# 🚗 INDIAN ELECTRIC VEHICLE (EV) MARKET ANALYSIS (2001–2024)

## 📌 PROJECT OVERVIEW
This project presents a complete analysis of **India’s Electric Vehicle (EV) market from 2001 to 2024** using state-wise sales data, vehicle type segmentation, and clustering methods. The objective is to identify EV adoption trends, seasonality patterns, state-wise performance, and market clusters to assist businesses and policymakers in understanding the Indian EV landscape.

---

## 📊 OBJECTIVES
- Analyze **year-wise and month-wise EV sales trends**.
- Study **state-wise EV adoption patterns**.
- Explore **vehicle-type preferences** (2W, 3W, 4W, Buses).
- Identify **seasonality effects** on EV sales.
- **Cluster states** based on sales and growth using **K-Means clustering**.
- Provide **marketing recommendations** using the **4Ps framework**.

---

## 🗂️ DATASET DESCRIPTION
- **Source**: EV_India.csv (real-world EV sales data).
- **Time Period**: 2001–2024.
- **Columns Included**:
  - `Year`, `Month_Name`, `Date`, `State`, `Vehicle_Class`, `Vehicle_Category`, `Vehicle_Type`, `EV_Sales_Quantity`.
- **Scope**: Monthly EV sales by state and vehicle segmentation.

---

## 📈 PROJECT FLOW
1. **Data Cleaning & Preprocessing**: Removing null values, correcting data types, and filtering years.
2. **Feature Engineering**: Adding growth rates, cumulative sales, and market share columns.
3. **Exploratory Data Analysis (EDA)**: Yearly, monthly, state-wise, and category-wise sales visualizations.
4. **Clustering (K-Means)**: State-wise segmentation using total sales and growth rates, with PCA visualization.
5. **4Ps Marketing Strategy**: Product, Price, Place, Promotion strategy tailored to clusters.
6. **Final Conclusion & Recommendations**.

---

## 📂 PROJECT STRUCTURE
EV_market_Analysis/
├── EV_Market_Analysis.ipynb # Jupyter Notebook with full analysis
├── EV_India.csv # Dataset with EV sales from 2001–2024
└── README.md # Project summary and documentation
---

## 📌 KEY FINDINGS
- EV sales in India **increased rapidly after 2019**.
- **2W segment dominates**, especially in Tier 2 and Tier 3 cities.
- **3W vehicles dominate rural markets**, particularly in **Uttar Pradesh** and **Bihar**.
- **4W sales are concentrated in metro areas**, especially in **Delhi** and **Maharashtra**.
- Clear **seasonality effects**, with peaks during **festive seasons (October–November)**.
- From clustering:
  - **Cluster 0**: Low Sales & Growth (e.g., Bihar, Jharkhand) — focus on awareness and infrastructure.
  - **Cluster 1**: High Sales but Low Growth (e.g., Uttar Pradesh, Maharashtra) — focus on retention and upgrades.
  - **Cluster 2**: Medium Sales, High Growth (e.g., Assam, Uttarakhand) — ideal for aggressive market expansion.

---

## 💡 FUTURE IMPROVEMENTS
- Add **forecasting models** to predict EV demand.
- Integrate **charging infrastructure datasets** to analyze accessibility impact.
- Build a **dashboard (PowerBI/Tableau)** for interactive visualizations.
- Include **policy impact assessment** for more comprehensive insights.

---

## 📝 AUTHOR
**Aashik Abdullah**  
📎 [GitHub Profile](https://github.com/AashikAbdullah)

---
