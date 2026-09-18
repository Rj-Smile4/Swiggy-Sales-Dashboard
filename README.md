# 🍽️ Swiggy Sales & Performance Analysis Dashboard (Jan – Aug 2025)

An end-to-end data analytics and dashboard project analyzing real Swiggy order transactions across 28 Indian cities. The project covers data cleaning, KPI aggregation, cuisine/food type segmentation, and an interactive executive Excel dashboard.

---

## 📌 Project Overview

This project analyzes **197,430 transactions** recorded between **January 1, 2025, and August 31, 2025**. It evaluates core business performance drivers including gross merchandise value (GMV), ticket sizes (AOV), user ratings, and regional dining preferences.

### Key Objectives
* Track monthly and quarterly revenue momentum across major markets.
* Evaluate customer spending behavior between Vegetarian and Non-Vegetarian orders.
* Benchmark operational health using average customer ratings and review volume.
* Identify top-performing cities and distribution across local restaurant hubs.

---

## 📊 Executive KPI Summary

| Key Metric | Value |
| :--- | :--- |
| **Total Revenue** | ₹53,012,505.77 (~₹5.30 Cr) |
| **Total Orders** | 197,430 |
| **Average Order Value (AOV)** | ₹268.51 |
| **Average Customer Rating** | 4.34 / 5.0 |
| **Total Ratings Count** | 5,591,574 |
| **Timeframe** | Jan 1, 2025 – Aug 31, 2025 |

---

## 📅 Monthly Performance Breakdown (2025)

| Month | Orders | Revenue (INR) | Average Order Value (AOV) | Avg. Rating | Total Ratings |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **January** | 25,398 | ₹6,825,186.03 | ₹268.73 | 4.34 | 719,529 |
| **February** | 23,296 | ₹6,269,105.67 | ₹269.11 | 4.34 | 660,607 |
| **March** | 24,402 | ₹6,573,530.07 | ₹269.38 | 4.35 | 680,341 |
| **April** | 24,588 | ₹6,594,515.00 | ₹268.20 | 4.34 | 689,885 |
| **May** | 25,190 | ₹6,793,558.40 | ₹269.69 | 4.34 | 722,193 |
| **June** | 24,385 | ₹6,514,183.19 | ₹267.14 | 4.34 | 677,496 |
| **July** | 24,940 | ₹6,650,965.51 | ₹266.68 | 4.34 | 711,904 |
| **August** | 25,231 | ₹6,791,461.90 | ₹269.17 | 4.34 | 729,619 |
| **Total** | **197,430** | **₹53,012,505.77** | **₹268.51** | **4.34** | **5,591,574** |

---

## 🥗 Food Type & Segment Analysis

| Food Type | Total Orders | Total Revenue (INR) | Share of Revenue | AOV (INR) |
| :--- | :--- | :--- | :--- | :--- |
| **Veg** | 139,546 | ₹34,180,397.94 | 64.48% | ₹244.94 |
| **Non-Veg** | 57,884 | ₹18,832,107.83 | 35.52% | ₹325.34 |

* **Key Takeaway:** While Vegetarian orders drive the bulk of volume (**~70.7% of all orders**), Non-Vegetarian orders deliver a significantly higher ticket size (**₹325.34 vs. ₹244.94**, a **+32.8% premium**).

---

## 🏙️ Top Revenue Contributing Cities

| City | Total Orders | Total Revenue (INR) | Average Ticket Size (INR) |
| :--- | :--- | :--- | :--- |
| **Bengaluru** | 20,077 | ₹5,456,798.41 | ₹271.79 |
| **Lucknow** | 10,192 | ₹3,117,359.65 | ₹305.86 |
| **Hyderabad** | 10,309 | ₹3,021,711.62 | ₹293.11 |
| **Mumbai** | 10,507 | ₹3,015,573.35 | ₹286.91 |
| **New Delhi** | 10,191 | ₹2,829,180.60 | ₹277.62 |
| **Ahmedabad** | 10,185 | ₹2,817,836.02 | ₹276.67 |
| **Chandigarh** | 10,065 | ₹2,809,440.69 | ₹279.13 |
| **Kolkata** | 10,046 | ₹2,662,801.76 | ₹265.06 |

---

## 🛠️ Data Architecture & Workbook Structure

The workbook consists of three primary layers:

1. **`Swiggy Data` (Data Lake Layer):**
   * Raw transaction logs with columns: `State`, `City`, `Order Date`, `Day`, `Quarter`, `Week Number`, `Restaurant Name`, `Location`, `Category`, `Dish Name`, `Food Type`, `Price (INR)`, `Rating`, and `Rating Count`.
2. **`Analysic` (Transformation & Modeling Layer):**
   * Multi-condition classification logic for dish categorization (e.g., matching keywords like `chicken`, `biryani`, `kebab`, `egg` for Veg/Non-Veg tagging).
   * Pivot summary tables for monthly runs, quarterly splits, and KPI metric aggregations.
3. **`Swiggy_Dashboard` (Presentation Layer):**
   * Executive reporting interface equipped with timeline slicers, category drilldowns, and summary scorecards.

---

## 💻 Tech Stack & Analytical Techniques

* **Software:** Microsoft Excel (Advanced)
* **Formulas & Logic:** `SUM`, `AVERAGE`, `COUNT`, `SEARCH`, `ISNUMBER`, nested `IF/OR` conditionals
* **Techniques:** Pivot Tables, Pivot Charts, Slicers, Data Cleansing, Categorical Normalization, Dashboard Architecture

---
## 👤 Author

* **Portfolio / LinkedIn:** [Raju Raidas](https://www.linkedin.com/in/rajuraidas6253/)
* **GitHub:** [@Rj-Smile4](https://github.com/Rj-Smile4)

## 🙏 Acknowledgements

Special thanks and sincere gratitude to **Satyam Mishra Sir** for his guidance, mentorship, and continuous support throughout the development of this project, and to the **Data Tutorials** YouTube channel for the insightful learning resources and practical tutorials.

## 📂 Repository File Structure

```text
├── Swiggy Raw Data Excel.xlsx    # Full dataset, pivot models, and interactive dashboard
└── README.md                     # Project documentation and summary report
