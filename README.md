# 💊 Pharma Sales Data Analysis & Dashboard

## 📌 Project Overview
This project analyzes over 600,000 pharmaceutical sales transactions collected over a 6-year period (2014-2019) from a community pharmacy. The goal of the project is to provide a consolidated, interactive visual dashboard for a Pharmacy Operations Manager to track revenue drivers, seasonal trends, and inventory demands.

This was a collaborative university project where I acted as the **Team Leader** for a group of 6 students during the requirements gathering and data analysis phases, and **independently developed the Power BI dashboard**.

## 🎯 The Business Problem (The "Why")
**Target User:** Pharmacy Operations Manager
**Pain Point:** The manager previously lacked a consolidated, visual view of sales performance. Without this, they could not quickly identify which drug categories were driving revenue, whether sales followed predictable seasonal patterns, or which months underperformed. This made stock planning and staff scheduling highly inefficient.

**Solution:** An interactive Power BI dashboard that tracks 57 drugs classified across 8 Anatomical Therapeutic Chemical (ATC) categories, allowing the manager to drill down into yearly, monthly, daily, and hourly trends.

## 📊 The Dashboard (The "What")
*I independently designed and built this dashboard using Power BI to solve the defined business problem.*

<img width="825" height="512" alt="Screenshot 2026-05-02 164004" src="https://github.com/user-attachments/assets/c9b6096b-45fb-42aa-9bb2-c1f709e273ae" />


**Key Features:**
*   **KPI Cards:** Quick view of total units sold (127.60K).
*   **Time-Series Analysis:** Line charts tracking total quantity sold by year to spot macroeconomic trends and operational drops.
*   **Category Breakdown:** Bar charts and donut charts detailing the sales volume of different drug categories (e.g., N02BE, N05B, R03).
*   **Interactive Filters:** Slicers for date ranges to allow dynamic drill-downs.

## 💡 Key Insights & Recommendations
Based on the dashboard and data analysis, we identified the following critical insights:

1.  **Inventory Prioritization (Category N02BE):**
    Category N02BE (Analgesics and Antipyretics - primarily Paracetamol) accounts for **49.38%** of total sales volume. 
    *   **Actionable Recommendation:** The supply chain and inventory management must heavily prioritize N02BE. A stockout in this category would severely impact overall pharmacy revenue. Safety stock levels should be increased for this category.
2.  **Investigating Performance Drops:**
    The yearly trend line revealed significant drops in total quantity sold in **2017 (23.1% drop)** and **2019**. 
    *   **Actionable Recommendation:** Management must investigate the 2019 operational data to determine if this decline is due to external market shrinkage (e.g., a competitor opening nearby) or internal operational issues. 

## 📂 Dataset Information
*   **Source:** Real community pharmacy in Bosnia and Herzegovina (published on Kaggle by Milan Zdravkovic).
*   **Size:** Initially 600,000+ transactional records, resampled into hourly, daily, weekly, and monthly aggregations.
*   **Features:** Timestamp (Datum), Drug Categories (WHO ATC system standards like M01AB, N02BA, R06), Sold Quantity.

## 🤝 My Role & Team Collaboration
*   **Team Leadership:** Led a cross-functional student team of 6 to source data, define business problems, and structure the reporting logic.
*   **Data Visualization (Solo):** Translated the team's findings and requirements into a functional, interactive Power BI dashboard.

## 🛠️ Tools Used
*   **Data Visualization:** Power BI
*   **Data Source:** Kaggle / CSV 
*   **Project Management & Collaboration:** Team leadership & structured reporting
