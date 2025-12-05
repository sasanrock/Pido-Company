# Pido-Company

Pido Company is a mobile fuel-delivery service operating across six major districts in Tehran.
The fleet consists of 42 fuel trucks, each delivering gasoline directly to customers in high-demand locations.
The company collects daily operational data, including fuel sales, refueling events, locations, and profitability metrics.

This dataset represents one full operational week of Pido’s activity.

⸻

📊 Project Overview

This project analyzes Pido’s weekly operations using Python. The goal is to extract actionable insights, build performance metrics, and create a dashboard that supports data-driven decision-making.

The work includes:

✔ Data Cleaning
    •    Removing empty rows/columns
    •    Reconstructing corrupted date fields
    •    Fixing inconsistent labels
    •    Standardizing numeric columns

✔ Feature Engineering

Custom features built to enhance insights:
    •    Profit Margin
    •    Utilization
    •    Capacity Used
    •    Fuel Purchased vs Sold
    •    Profit per Liter
    •    Location Rank / Truck Rank
    •    Performance Score

✔ Aggregation & KPI Analysis
    •    Total liters sold
    •    Total profit
    •    Total sales value
    •    Total refueling events
    •    Daily sales and profit trends
    •    Truck-level weekly performance
    •    Area-level comparisons
    •    Heatmap of operations across dates and regions

⸻

📈 Dashboard Development

A full interactive-style dashboard was built using Python and HTML.
Visuals included:
    •    Daily Fuel Sales Trend
    •    Daily Profit Trend
    •    Sales per Truck
    •    Profit per Truck
    •    Sales by Area
    •    Profit by Area
    •    Area × Date Sales Heatmap
    •    Truck Utilization
    •    Performance Score Rankings
    •    Fuel Purchased vs Sold
    •    Profit Margin Distribution

All graphs were embedded into a single HTML dashboard that can be opened in any browser without Power BI.

⸻

🛠 Technologies Used
    •    Python
    •    pandas
    •    matplotlib
    •    seaborn
    •    HTML Dashboard Rendering (Base64 Embedded Images)
    •    Jupyter / VS Code


📦 Pido-Fuel-Analytics
├── Pido_Company_End.csv
├── notebooks/
│   ├── cleaning.ipynb
│   ├── feature_engineering.ipynb
│   └── analysis.ipynb
├── dashboard/
│   └── pido_full_dashboard.html
├── README.md

🧠 Key Insights
    •    The highest-performing trucks generated significantly higher profit due to area placement and refueling frequency.
    •    Certain regions showed consistently higher fuel demand.
    •    Profit margins varied based on utilization and selling volume.
    •    Operational inefficiencies can be identified through refueling patterns and capacity usage.

⸻

📌 Outcome

This project provides Pido with a clear, data-driven view of weekly operations, enabling:
    •    Optimized truck deployment
    •    Better profit forecasting
    •    Improved scheduling
    •    Identification of high-value areas
    •    Enhanced operational decision-making
