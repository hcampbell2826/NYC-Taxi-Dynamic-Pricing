# NYC-Taxi-Dynamic-Pricing

This repository contains a forecast-driven dynamic pricing analysis using NYC Yellow Taxi data. The project explores whether forecasting hourly taxi demand and adjusting prices based on predicted demand can generate higher revenue compared to a static pricing approach.

---

## Software and Platform

This project was completed using the following software and platform:

Platform:
MacOS

Programming Language:
Python

Development Environment:
Jupyter Notebook

Python Libraries Used:
pandas  
numpy  
matplotlib  
seaborn  
statsmodels  

These libraries are required to run the notebooks in the repository.

---

## Map of the Documentation

The repository is organized into the following folders:

NYC-Taxi-Dynamic-Pricing

DATA  
Contains instructions for downloading the NYC Taxi dataset. The raw dataset is not stored in this repository due to file size limits.

- data_download_instructions.md  
Provides instructions for downloading the Yellow Taxi dataset from the NYC TLC website.

OUTPUT  
Contains all figures and visualizations generated during the analysis.

Files include:
- demand_by_hour.png
- demand_distribution.png
- demand_forecast.png
- demand_heatmap.png
- distance_vs_fare.png
- fare_distribution.png
- forecast_vs_actual.png
- hourly_demand.png
- revenue_comparison.png
- weekend_vs_weekday_demand.png

SCRIPTS  
Contains the Jupyter notebooks used for the analysis.

- 01_data_cleaning.ipynb  
Loads the raw taxi dataset, cleans the data, converts timestamps, and aggregates trips into hourly demand.

- 02_EDA.ipynb  
Performs exploratory data analysis to understand patterns in taxi demand and trip characteristics.

- 03_demand_forecasting.ipynb  
Builds a time-series forecasting model to predict hourly taxi demand.

- 04_dynamic_pricing_simulation.ipynb  
Simulates a dynamic pricing strategy using forecasted demand and compares revenue to a static pricing model.

---

## Instructions to Reproduce the Results

Step 1: Download the NYC Taxi dataset

Follow the instructions provided in:

DATA/data_download_instructions.md

Download the Yellow Taxi dataset and place the file in the DATA folder as described in the instructions.

Step 2: Run the data cleaning notebook

Open and run:

SCRIPTS/01_data_cleaning.ipynb

This notebook loads the raw taxi data, cleans the dataset, converts timestamps, and aggregates the data into hourly taxi demand.

Step 3: Run the exploratory data analysis notebook

Open and run:

SCRIPTS/02_EDA.ipynb

This notebook generates visualizations showing demand patterns, fare distributions, and relationships between trip variables.

Step 4: Run the demand forecasting notebook

Open and run:

SCRIPTS/03_demand_forecasting.ipynb

This notebook builds a time-series model to forecast hourly taxi demand and produces forecast plots.

Step 5: Run the dynamic pricing simulation

Open and run:

SCRIPTS/04_dynamic_pricing_simulation.ipynb

This notebook simulates a dynamic pricing strategy using the predicted demand and compares the resulting revenue to a static pricing approach.

All generated visualizations and results will appear in the OUTPUT folder.
