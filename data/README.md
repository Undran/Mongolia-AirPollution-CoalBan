# Ulaanbaatar Particulate Matter Dataset (2015–2018)
import kagglehub
path = kagglehub.dataset_download("robertritz/ulaanbaatar-particulate-matter")
print("Path to dataset files:", path)

## Dataset Description
This dataset contains **hourly PM2.5 and PM10 measurements** from 18 air quality monitoring stations in Ulaanbaatar, Mongolia, covering the years 2015–2018. It provides crucial information on air pollution levels in the city, with a focus on **Ger districts**, where household coal burning is a major source of pollution. The dataset is sourced from OpenAQ and made available via Kaggle. It is suitable for analyzing temporal and spatial trends in air quality, evaluating policy interventions such as the **2019 raw coal ban**, and exploring the relationship between energy use and air pollution.

## Data Dictionary

| Column      | Description                                | Data Type |
|------------|--------------------------------------------|-----------|
| timestamp  | Date and time of measurement               | datetime  |
| station_id | Identifier for the monitoring station      | string    |
| pm25       | PM2.5 concentration (µg/m³)               | float     |
| pm10       | PM10 concentration (µg/m³)                | float     |
| latitude   | Latitude of the monitoring station         | float     |
| longitude  | Longitude of the monitoring station        | float     |

## Replicability and Reuse
The dataset is publicly accessible and can be programmatically downloaded using the Kaggle API. It supports reproducible analyses of air quality trends and policy impacts in Ulaanbaatar. Missing values may occur due to temporary station downtime; these should be handled during preprocessing. The data is structured for reuse in statistical modeling, machine learning, and visualization.
