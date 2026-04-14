# Blinkit Sales Performance Analysis 🛒

## 📋 Project Overview
This project provides a deep-dive analysis into Blinkit's sales data to identify key drivers of revenue. Using **Python**, I performed data cleaning, handled missing values, and visualized trends across different outlet types, locations, and item categories.

## 🎯 Business Problems Addressed
* How do Item Fat Content and Visibility affect sales?
* Which Outlet types (Tier 1, 2, or 3) are the most profitable?
* What is the impact of Outlet Size on total revenue?

## 🛠️ Tech Stack
- **Language:** Python
- **Libraries:** Pandas (Data Manipulation), Matplotlib & Seaborn (Visualization), NumPy

## 📊 Key Insights & Visualizations

### 1. Sales by Outlet Location
Tier 3 cities are outperforming other regions, indicating a strong market presence in developing urban areas.
![Sales by Location]

### 2. Item Fat Content Distribution
Standardized "LF", "low fat", and "Regular" labels to reveal that Low Fat items contribute to over 60% of total sales volume.
![Fat Content Chart]

### 3. Core Metrics (KPIs)
- **Total Sales:** $1.20M
- **Avg Sales per Item:** $141
- **Number of Items:** 8,523
- **Avg Customer Rating:** 4.0/5

## 📈 Methodology
1. **Data Wrangling:** Cleaned inconsistent categorical data and handled null values in `Item Weight` and `Outlet Size`.
2. **Exploratory Data Analysis (EDA):** Used `groupby` and `agg` functions to segment sales by year and location.
3. **Data Visualization:** Built distribution plots and bar charts to make the data understandable for stakeholders.

## 📂 Repository Structure
- `data/`: Contains the raw Blinkit dataset.
- `images/`: High-resolution charts for the analysis.
- `Blinkit_Analysis.ipynb`: The complete Python source code.
