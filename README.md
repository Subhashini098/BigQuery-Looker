# BigQuery-Looker
Utilized Global Surface Summary of the Day (GSOD) dataset present in BigQuery Public Dataset. The dataset is a collection of daily weather data collected by weather stations worldwide. It includes information such as temperature, precipitation, wind speed, humidity, and atmospheric pressure, among others.
Employed SQL queries to format the data as needed, then linked it to Looker Studio for visualization purposes.

Link to the visualization-https://lookerstudio.google.com/reporting/62fc167b-f4aa-4a21-a6de-9db228f90b12

## 1. Average Temperature Trends over the years.
Created average_temperature View using the following query.
![Screenshot (1092)](https://github.com/Subhashini098/BigQuery-Looker/assets/109629881/ad98284e-56c4-46d2-96ac-3c36f9fb92c8)


## 2.Comparing the Average Temperature between US and UK
Created temperature_trendsin_selected_countries View using the following query.
![Screenshot (1094)](https://github.com/Subhashini098/BigQuery-Looker/assets/109629881/b8587e3e-8e6c-4b36-8ff3-f1c4913a4fb3)



## 3.Average Temperature across the globe for different Periods
Created a datetime_mean_temp Table using the following query.
![Screenshot (1089)](https://github.com/Subhashini098/BigQuery-Looker/assets/109629881/0332adfb-d623-4e80-854d-8c829c011fa3)

