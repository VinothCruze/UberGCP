# UberGCP

## Introduction
Data Engineer Project for learning GCP, Mage
Created the project by extracting the raw data using API call, transforming into fact and dimenisons with the help of MAGE tool. Finally visualizing it in [Looker dashboard](https://lookerstudio.google.com/reporting/66a4ae84-62e2-4b0e-8ed0-3c8492976ee5).

The project is based on the below architecture
<img src="architecture.jpg">

## Technology Used
- Programming Language - Python

Google Cloud Platform
1. Google Storage
2. Compute Instance 
3. BigQuery
4. Looker Studio

## Dataset Used
TLC Trip Record Data
Yellow and green taxi trip records include fields capturing pick-up and drop-off dates/times, pick-up and drop-off locations, trip distances, itemized fares, rate types, payment types, and driver-reported passenger counts. 

Here is the dataset used in the video - [Uber Data](https://github.com/VinothCruze/UberGCP/blob/main/Data/uber_data.csv)

More info about dataset can be found here:
1. Website - https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page
2. Data Dictionary - https://www.nyc.gov/assets/tlc/downloads/pdf/data_dictionary_trip_records_yellow.pdf

## Data Model
<img src="data_model.jpeg">

## Mage Pipeline
<img src="Mage Files/Mage Pipeline Front end.png">

## GBQ data
<img src ="GCP Big Query.png">

## Looker Dashboard Visualization
![image](https://github.com/VinothCruze/UberGCP/assets/68219125/c535c3eb-fe25-4855-893a-72465afff9df)



