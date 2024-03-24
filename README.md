# Uber Data Analytics 

## Introduction

This project focuses on analyzing Uber data by leveraging a modern data engineering stack on the Google Cloud Platform (GCP). Utilizing Python, GCP Storage, Compute Engine, BigQuery, Looker Studio, and the Mage Data Pipeline Tool, we aim to provide insights into the Uber dataset through a comprehensive data analytics process.

## Architecture

The project's architecture follows a data pipeline model where raw data is ingested, processed, and analyzed:
![p](https://github.com/rohan8399/Uber_ETL/assets/127540229/c23ffe5c-f08c-4718-97b0-38b4de34f397)



1. **Data Ingestion**: Raw data from the TLC Trip Record Data is stored in Google Cloud Storage.
2. **Data Processing**: The Mage Data Pipeline Tool is used to transform raw data into a structured format suitable for analysis. This step involves data cleaning, normalization, and preparation.
3. **Data Storage**: Processed data is loaded into BigQuery, Google's serverless, highly scalable, and cost-effective multi-cloud data warehouse.
4. **Data Analysis and Visualization**: Using Looker Studio, dashboards are created to visualize and interpret the processed data, providing actionable insights.

## Technology Used

- **Programming Language**: Python
- **Google Cloud Platform**: Utilizes GCP's Storage, Compute Instance, and BigQuery services.
- **Looker Studio**: For creating interactive dashboards and reports.
- **Modern Data Pipeline Tool**: Mage ([Learn more](https://www.mage.ai/))

## Dataset Used

The project utilizes the TLC Trip Record Data, which includes detailed records of yellow and green taxi trips in New York City. The dataset encompasses fields such as pick-up and drop-off dates/times, locations, trip distances, fares, rate types, payment types, and passenger counts.

- **Dataset Source**: uber_data.csv - https://github.com/rohan8399/Uber_ETL/blob/main/uber_data.csv
- **Dataset Information and Data Dictionary**:
    - [NYC TLC Trip Record Data](https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page)
    - [Data Dictionary for Yellow Taxi Records](https://www.nyc.gov/assets/tlc/downloads/pdf/data_dictionary_trip_records_yellow.pdf)

## Data Model

![Data Model](https://github.com/rohan8399/Uber_ETL/assets/127540229/d046f501-4740-4569-af6b-4d09aab00409)

