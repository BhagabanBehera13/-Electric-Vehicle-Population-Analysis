# ⚡-Electric-Vehicle-Population-Analysis

## Overview

The **Electric Vehicle Population Analysis** is a Python-based Exploratory Data Analysis (EDA) project that analyzes the Electric Vehicle Population dataset to generate insights into EV adoption trends, manufacturers, models, geographic distribution, and vehicle range.

The project transforms raw EV registration data into clear visualizations that help understand the growth of electric vehicles over time, popular makes/models, and regional adoption patterns.

---

# 📂 Dataset

Dataset: **Electric Vehicle Population Data** (Washington State Department of Licensing)
Source: https://catalog.data.gov/dataset/electric-vehicle-population-data

Key columns used: `Make`, `Model`, `Model Year`, `Electric Vehicle Type`, `Electric Range`, `Base MSRP`, `County`, `City`, `Electric Utility`, `CAFV Eligibility`.

---

# 🎯 Objectives

- Analyze EV registration growth over the years.
- Identify top EV manufacturers and models.
- Compare Battery Electric Vehicles (BEV) vs Plug-in Hybrid Electric Vehicles (PHEV).
- Analyze EV distribution across counties.
- Study the distribution of electric range across vehicles.
- Analyze Clean Alternative Fuel Vehicle (CAFV) eligibility status.
- Identify top electric utilities serving EV owners.

---

# 📊 Analysis Included

- EV registrations by Model Year (trend line)
- Top 10 EV manufacturers
- Top 10 EV models
- EV Type distribution (BEV vs PHEV) — pie chart
- Top 10 counties by EV registrations
- Electric range distribution (histogram)
- CAFV eligibility breakdown
- Top 10 electric utilities
- Summary statistics (total vehicles, unique makes/models, average range, etc.)

---

# 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| Python | Data Analysis & EDA |
| Pandas | Data Cleaning & Manipulation |
| NumPy | Numerical Analysis |
| Matplotlib | Data Visualization |
| Seaborn | Statistical Visualization |

---

# ▶️ How to Run

1. Download the dataset CSV from the source link above and place it in the project folder as `Electric_Vehicle_Population_Data.csv`.
2. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn
   ```
3. Run the script:
   ```bash
   python ev_population_analysis.py
   ```
4. Generated charts (`.png`) and `summary_statistics.txt` will be saved in the project folder.

---

# 📊 Business Insights

- Growth trend of EV adoption year over year.
- Which manufacturers and models dominate the EV market.
- BEV vs PHEV adoption share.
- Regions with highest EV concentration.
- Typical electric range offered across vehicles.
- CAFV eligibility trends relevant to incentives/policy.

---

# 💼 Business Value

This analysis can help:

- Policy makers understand EV adoption trends for infrastructure planning.
- Utilities forecast electric grid demand from EV charging.
- Manufacturers identify competitive positioning by range and market share.
- Researchers study regional clean-energy transition patterns.

