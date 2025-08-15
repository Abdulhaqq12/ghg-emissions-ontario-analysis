# ghg-emissions-ontario-analysis
Data-driven analysis of Ontario’s public sector GHG emissions (2012–2023) using descriptive, diagnostic, predictive, and prescriptive analytics to identify major emitters, forecast trends, and recommend strategies for emission reduction through renewables and efficiency improvements.
# Reducing GHG Emissions in Ontario: A Data-Driven Approach

## 📌 Overview
This project analyzes greenhouse gas (GHG) emissions data across Ontario’s public sectors from **2012 to 2023**. Leveraging **Python**, **machine learning models**, and **data visualization tools**, we identify emission hotspots, forecast future trends, and simulate policy interventions such as renewable energy adoption.  

The work was completed as part of the **BIA-5450 Capstone Project** at Humber College.

---

## 🎯 Objectives
- Identify high-emission sectors and regions in Ontario.
- Determine key drivers of elevated GHG emissions.
- Forecast future emissions based on historical trends.
- Evaluate renewable energy adoption and operational improvement strategies.
- Provide actionable policy recommendations.

---

## 📊 Data Sources
- Publicly available Ontario **Public Sector Energy Use and GHG Emissions** datasets (2012–2023).
- Energy metrics: Electricity consumption (kWh), Natural gas consumption, CO₂ emissions (kg).
- Operational attributes: Facility type, sector, location, and operational details.

---

## 🛠 Tools & Technologies
- **Python** (Pandas, NumPy, Scikit-learn, XGBoost, Matplotlib, Seaborn)
- **Power BI** (Interactive dashboards and visualizations)
- **Excel** (Initial cleaning and data integration)
- **Jupyter Notebook** (Exploratory Data Analysis & Modeling)

---

## 📈 Methodology
1. **Data Preparation**
   - Cleaning, normalization, and integration of multi-year datasets.
   - Feature engineering (energy intensity, emissions intensity).
   - One-hot encoding of categorical variables.

2. **Analytics**
   - **Descriptive:** Trends, hotspots, and sector comparisons.
   - **Diagnostic:** Correlation analysis to find emissions drivers.
   - **Predictive:** Regression models (Linear Regression, Random Forest, XGBoost) for forecasting.
   - **Prescriptive:** Cost-benefit analysis for solar adoption scenarios.

3. **Visualization**
   - Time-series trends
   - Heatmaps of sectoral emissions
   - RMSE & R² model performance charts
   - Clustering analysis

---

## 🚀 Key Findings
- **Hospitals** and **Post-secondary institutions** are major contributors to emissions in multiple cities.
- **Random Forest** outperformed other models with **R² = 0.98**.
- Solar adoption scenarios reveal potential for significant emission reduction, though anomalies highlight areas for model refinement.
- COVID-19 restrictions in 2020–2021 coincided with a notable drop in emissions.

---

## 📌 Recommendations
1. Prioritize renewable energy investments in high-emission sectors.
2. Improve data governance with real-time monitoring systems.
3. Integrate more granular facility-level data for accurate forecasting.
4. Enhance regulatory frameworks to incentivize energy efficiency.

---

