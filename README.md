# Ford GoBike Bike-Sharing Data — Exploratory Data Analysis

## Overview
This project analyzes 1.86M+ individual trip records from the Ford GoBike bike-sharing system (San Francisco Bay Area) across all 12 months of 2018. The goal is to uncover rider behavior patterns — trip duration, timing, station demand, and demographic trends — and translate them into actionable business recommendations for operations, marketing, and station planning.

## Dataset
- **Source:** [Ford GoBike System Data](https://www.fordgobike.com/system-data)
- **Period:** January – December 2018
- **Size:** 1,863,721 trips across 16 original features
- **Files:** 12 monthly CSV files, merged into a single dataset for analysis

## Objective
To identify key usage patterns and behavioral differences between Subscribers (members) and Customers (casual riders), enabling the business to:
- Improve bike availability and rebalancing during peak commute hours
- Design targeted campaigns to convert repeat Customers into Subscribers
- Prioritize station-level infrastructure investment based on actual demand

## Approach
- **Data Cleaning & Wrangling:** datetime conversion, duration unit conversion, feature engineering (hour/day/month), age derivation with outlier handling
- **Univariate Analysis:** trip duration, user type, gender, age, and program participation distributions
- **Bivariate Analysis:** trip duration vs. user type, trip patterns by day of week and hour
- **Multivariate Analysis:** hour × day-of-week heatmap, correlation heatmap, pair plot
- **15 visualizations total**, each with rationale, insight, and business-impact assessment

## Key Findings
- Subscribers account for ~85% of trips, with sharp commute-hour peaks (8 AM, 5 PM) on weekdays
- Customers take longer trips on average, concentrated on weekends and midday — consistent with leisure/tourist use
- Trip volume is highly concentrated at a small number of transit-adjacent stations
- Ridership grows steadily from winter into a fall peak, tapering off toward December

## Tools & Libraries
- Python, Pandas, NumPy
- Matplotlib, Seaborn
- Jupyter Notebook / Google Colab

## Files
- `Ford_GoBike_EDA_Capstone.ipynb` — full analysis notebook

## Author
Leshyatha — Data Analytics Intern, Labmentix
