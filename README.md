# Air Pollution Data Analysis Using Python 

#Project Overview

This project analyzes global air-pollution data (PM2.5, PM10, NO₂) using Python. It includes data cleaning, exploratory analysis, visualizations, and AQI calculation based on Indian standards. The goal is to understand pollution patterns across cities and years.

# Dataset Summary

Key fields include:
•	Country, City, Year
•	PM2.5, PM10, NO₂ levels
•	Temporal coverage for each pollutant
•	Updated Year
Dataset size: 7,800+ rows, multiple countries & cities.

# Data Cleaning

•	Removed duplicates
•	Standardized column names
•	Converted pollutant columns to numeric
•	Filled missing values using mean
•	Ensured valid year and pollutant entries

# Analysis Performed

•	City-wise & year-wise pollutant averages
•	Identification of most polluted & cleanest cities
•	Trend analysis for PM2.5, PM10, NO₂
•	Correlation analysis between pollutants
•	Categorized air quality levels

# Visualizations

•	Distribution plots (PM2.5)
•	Bar charts (Top polluted/clean cities)
•	Yearly trend line graphs
•	Heatmaps (correlations)
•	Pie charts (air-quality categories)
•	Interactive charts (Plotly, Altair)
•	Bokeh dashboards for AQI & city-wise pollution

# AQI Calculation

AQI computed using Indian AQI formula:
AQI = max(PM2.5 Index, PM10 Index, NO₂ Index)
Interactive dashboard shows yearly AQI trends per city.

# Tools Used

Python, Pandas, NumPy, Matplotlib, Seaborn, Plotly, Altair, Bokeh, MySQL.

# Conclusion

The project provides clear insights into pollution patterns, highlights highly polluted cities, and shows pollutant trends over time. Interactive dashboards enhance understanding of AQI behaviour across locations.

