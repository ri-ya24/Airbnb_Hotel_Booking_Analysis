#  Airbnb Data Analysis & Business Insights

An end-to-end Data Analytics project performing Exploratory Data Analysis (EDA) on 100k+ NYC Airbnb listings to uncover pricing dynamics, geographic trends, host behavior, and customer ratings.

---

## 🛠️ Tech Stack & Tools

* **Language:** Python 3
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn
* **Environment:** Google Colab, GitHub

---

## 🔄 Project Workflow

`Raw Data Load` ➔ `Data Cleaning & Typo Fixes` ➔ `Statistical Health Check` ➔ `EDA & Visualizations (Q1-Q9)` ➔ `Business Insights & Recommendations`

---

## 🔍 Key Questions & Findings

1. **Property Types:** Entire Home/Apts (~52%) & Private Rooms (~45%) control >95% of supply.
2. **Location Density:** Manhattan (~42.7%) & Brooklyn (~40.8%) hold >83% of total NYC inventory.
3. **Pricing Variance:** Borough-level average prices are closely clustered between ~$622 - $630.
4. **Property Age:** Building construction year shows no linear correlation (r ≈ -0.0004) with room prices.
5. **Commercial Hosts:** Top property managers operate over 330+ listings on the platform.
6. **Service Fees:** Price and Service Fee have an extremely strong linear correlation (r ≈ 0.9978).
7. **Customer Ratings:** Average review ratings are consistent (~3.0 stars) across all borough clusters.
8. **Portfolio & Availability:** Multi-listing hosts (21+ properties) maintain modestly higher annual availability (~200+ days).

---

## 🎯 Key Recommendations

* **Geographic Expansion:** Incentive host onboarding in Queens, Bronx, and Staten Island to decentralize market risk.
* **Commercial Host Tools:** Provide enterprise features (bulk calendar sync, dynamic pricing APIs) for multi-property hosts.
* **Smart Pricing Guidance:** Align algorithmic pricing suggestions with seasonality and micro-location rather than property age.

---

## 📂 Project Structure

```text
Airbnb_Hotel_Data-Analysis/
│
├── Airbnb_Hotel_Booking_Analysis.ipynb
└── README.md
