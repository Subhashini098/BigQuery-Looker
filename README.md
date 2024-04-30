# BigQuery-Looker
Utilized Global Surface Summary of the Day (GSOD) dataset present in BigQuery Public Dataset. The dataset is a collection of daily weather data collected by weather stations worldwide. It includes information such as temperature, precipitation, wind speed, humidity, and atmospheric pressure, among others.
Employed SQL queries to format the data as needed, then linked it to Looker Studio for visualization purposes.

Link for the visualization-https://lookerstudio.google.com/reporting/62fc167b-f4aa-4a21-a6de-9db228f90b12

## 1. Average Temperature Trends over the years.
Created average_temperature View using the following query.
![Screenshot (1092)](https://github.com/Subhashini098/BigQuery-Looker/assets/109629881/3cc93870-5d3e-46ed-8cb1-481d8c6a76a6)

## 2.Comparing the Average Temperature between US and UK
Created temperature_trendsin_selected_countries View using the following query.
![Screenshot (1094)](https://github.com/Subhashini098/BigQuery-Looker/assets/109629881/a0936367-f30a-4b9b-814d-2a8c98d08013)


## 3.Average Temperature across the globe for different Periods
Created a datetime_mean_temp Table using the following query.
![Screenshot (1089)](https://github.com/Subhashini098/BigQuery-Looker/assets/109629881/e0813a26-1bee-40ba-a941-3135303b31ab)
