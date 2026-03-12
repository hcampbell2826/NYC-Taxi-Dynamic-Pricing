# Data Download Instructions

The datasets used in this project are too large to be hosted on GitHub.

## Raw Data

Download NYC Yellow Taxi trip data from:

https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page

Download the following files:

- yellow_tripdata_2025-09.parquet
- yellow_tripdata_2025-10.parquet
- yellow_tripdata_2025-11.parquet

Place them in:

DATA/raw/

## Processed Data

Run the script:

SCRIPTS/01_data_cleaning.ipynb

This will generate:

DATA/processed/cleaned_taxi_data.csv
