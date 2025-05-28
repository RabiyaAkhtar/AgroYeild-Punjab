# AgroYeild-Punjab
ML Models for Wheat Production Forecasting in Punjab


# Author: [Dr. Rabiya Akhtar]
# Date: [May 28th, 2025]

"""
Data Sources:
1. Wheat Yield Data: 'production-and-yield-of-wheat-by-districts-punjab.csv'
   - Source: Punjab Agriculture Department
   - Contains: Annual wheat production and yield by district from 2007-2021
   - Format: District, Year, Yield (kg/hectare)

2. Rainfall Data: 'rainfall-at-selected-stations-the-punjab-pakistan-2010-2021.csv'
   - Source: Pakistan Meteorological Department
   - Contains: Monthly rainfall measurements at selected stations
   - Format: Station/District, Year, Monthly rainfall (mm)

3. Temperature Data: 'temperature-at-selected-centre-the-punjab-pakistan-2021.csv'
   - Source: Pakistan Meteorological Department
   - Contains: Daily mean maximum temperatures at selected centers
   - Format: Station/District, Year, Monthly mean max temp (°C)

Methodology:
1. Data Collection: Gather wheat yield, rainfall and temperature data
2. Data Cleaning: Handle missing values, standardize district names
3. Feature Engineering: Create seasonal aggregates and derived features
4. Data Merging: Combine all datasets into a unified dataframe
5. Exploratory Analysis: Visualize relationships between variables
6. Modeling: Train and evaluate machine learning models
7. Prediction: Generate yield predictions with uncertainty estimates
"""
