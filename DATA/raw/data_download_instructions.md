# Raw Data Download Instructions

The raw dataset used in this project is the NYC Yellow Taxi Trip Records.

Due to GitHub file size limitations, the raw dataset is not included in this repository.

To reproduce the analysis:

1. Visit the NYC Taxi and Limousine Commission data portal:

https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page

2. Download the dataset:

yellow_tripdata_2025_Q4.parquet

3. Place the file in:

DATA/raw/

4. Run the script:

SCRIPTS/01_data_cleaning.ipynb

This script will clean and aggregate the data into:

DATA/processed/hourly_taxi_data.csv
