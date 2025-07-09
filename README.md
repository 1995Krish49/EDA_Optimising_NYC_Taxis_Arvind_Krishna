## **📌 Project Overview**
This project performs an in-depth Exploratory Data Analysis (EDA) on 2023 NYC Yellow Taxi trip data to uncover insights that help optimize routing, fleet distribution, pricing, and service efficiency for a hypothetical taxi operation.

## **🧠 Objectives**
Analyze trip data to identify peak demand hours, high-density zones, and revenue trends.

Understand passenger behavior, payment preferences, and tipping patterns.

Recommend data-driven strategies to optimize taxi allocation, minimize idle time, and increase profitability.

## **🧰 Tools & Techniques**
Python Libraries: Pandas, NumPy, Matplotlib, Seaborn, GeoPandas

File Formats: Parquet, CSV

Visualization: Heatmaps, bar plots, line charts, geospatial maps

Techniques: Outlier handling, feature engineering, correlation analysis, IQR filtering

## **🔍 Key Analyses**
Temporal Trends: Identified 14:00–19:00 as peak hours and January as the highest revenue month.

Zone-Based Analysis: Mapped high and low traffic areas using GeoPandas; JFK, LaGuardia, and Midtown were top zones.

Fare & Distance Correlation: Found a strong linear relationship (r = 0.947), enabling dynamic fare planning.

Tipping & Passenger Insights: Evening trips (5–9 PM) had highest tips; grouped rides showed lower per-passenger fares.

Vendor Comparison: Vendor 2 charged higher per-mile rates for short trips; Vendor 1 had steadier pricing.

## **💡 Key Insights & Recommendations**
Fleet Optimization: Deploy more taxis in high-demand areas during peak hours; reduce supply in low-traffic zones.

Zone Strategy: Use vehicle size allocation based on average passenger count (e.g., larger taxis in Ocean Parkway South).

Surge Pricing Strategy: Focus fare increases on peak evening hours instead of low-volume early mornings.

Airport Deployment: Maintain dedicated fleet presence at JFK and LaGuardia to manage high outbound traffic efficiently.

Encourage Group Travel: Introduce group fare incentives and tipping nudges in low-tip periods.

## **📈 Outcome** 
The final analysis supports data-driven decision-making for better fleet utilization, strategic pricing, and service improvement, directly contributing to enhanced passenger experience and operational efficiency.
