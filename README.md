# borderdisaster

## Overview
The Border Disaster Project explores the relationship between natural disasters and U.S. border activity. Using publicly available datasets from FEMA (Federal Emergency Management Agency) and the Bureau of Transportation Statistics (BTS), this project investigates how federally declared disasters affect cross-border traffic flows (e.g., personal vehicles, trucks, buses, pedestrians) at U.S.–Canada and U.S.–Mexico borders.

The analysis combines spatial-temporal techniques, statistical modeling, and machine learning approaches to quantify disruptions and identify long-term patterns.

## Objectives
- Analyze how different types of disasters (hurricanes, floods, wildfires, biological events such as COVID-19) impact cross-border movements.
- Perform time-series forecasting to predict border traffic volumes under disaster and non-disaster scenarios.
- Use clustering and spatial analysis to group ports of entry with similar disaster response patterns.
- Provide interactive dashboards for visualizing trends across locations, time periods, and disaster categories.

## Data Sources
- FEMA Disaster Declarations Summary (1953–present):  Includes disaster types, declaration dates, affected counties/states, and response programs.
- Bureau of Transportation Statistics (BTS) – Border Crossing/Entry Data: Monthly inbound traffic statistics at U.S.–Canada and U.S.–Mexico border ports. Categories: trucks, trains, buses, personal vehicles, passengers, pedestrians, containers.

## Methodology
Data Preparation
- Data cleaning and transformation using Python (Pandas, NumPy).
- Merging FEMA disaster records with BTS border crossing data.
Exploratory Data Analysis (EDA)
- Identifying trends in border activity over time.
- Visualizing seasonal and disaster-related disruptions.
Modeling Approaches
- Statistical Forecasting: ARIMA/SARIMA for traffic prediction.
- Machine Learning Models: Random Forest, Gradient Boosting, or Poisson Regression for impact quantification.
- Clustering: K-Means/DBSCAN to identify border ports with similar response behaviors.

## Future Work
- Expand models to include macroeconomic factors (inflation, unemployment, gas prices).
- Incorporate climate projections to simulate future disaster impacts.
- Develop a real-time monitoring system for border disruptions during active disasters.
