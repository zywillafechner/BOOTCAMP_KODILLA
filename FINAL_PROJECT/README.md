# Bicycle Rental Demand Forecasting

This project focuses on forecasting bicycle rental demand for a bicycle rental company. The goal is to optimize the number of bicycles prepared at each station, minimizing costs associated with overstocking and lost profits due to insufficient stock.

## Business Context
- Logistics operations are planned one week in advance. After each day (e.g., Monday), a forecast is made for the same day of the following week.
- The cost of insufficient bicycles at a station is PLN 10 per lost rental.
- The cost of keeping excess bicycles at a station is PLN 1 per unused bicycle per day.

## Data
The dataset, `bikerides_day.csv`, contains daily bicycle rental data from Oslo, Norway.

## Project Scope
The project includes:
1. **Data preprocessing**: Cleaning and preparing the dataset for analysis.
2. **Visualization**: Exploratory analysis to understand key patterns in the data.
3. **Modeling**: Comparison of three models:
   - Baseline model,
   - Decision Tree,
   - Random Forest.

This analysis aims to improve forecasting accuracy and support data-driven decision-making in the company’s logistics processes.
