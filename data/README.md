# Dataset: Ulaanbaatar Particulate Matter Sensor Data (subset)

**Description (100–150 words)**  
This dataset is a subset of the publicly available “Ulaanbaatar Particulate Matter Sensor Data (2015–2018)” dataset from Kaggle. To make the dataset manageable for classroom analysis, only the first 5,000 rows of the original CSV were included. The subset contains air quality measurements from multiple monitoring stations across Ulaanbaatar, Mongolia, including PM2.5 and PM10 concentrations. Key columns include timestamps in UTC and local time, the pollutant parameter, measurement location, value, units, city, source attribution, geographic coordinates, country, source name, source type, and mobile availability. This subset is intended for exploratory data analysis, visualization, and teaching purposes. The original dataset remains publicly available on Kaggle for users who need full temporal coverage or complete dataset distribution.  

---

## Data dictionary
| name         | type      | description |
|--------------|-----------|-------------|
| date         | string    | Timestamp information in UTC and local time (`{utc=..., local=...}`) |
| parameter    | string    | Pollutant measured (e.g., `pm25` or `pm10`) |
| location     | string    | Name of monitoring station or location |
| value        | float     | Measured value of the pollutant in µg/m³ |
| unit         | string    | Measurement unit (e.g., `µg/m³`) |
| city         | string    | City where measurement was taken (Ulaanbaatar) |
| attribution  | string    | Source attribution, often a list of agencies or URLs |
| coordinates  | string    | Latitude and longitude of monitoring station |
| country      | string    | Country code (MN for Mongolia) |
| sourcename   | string    | Name of the data source |
| sourcetype   | string    | Type of source (if available) |
| mobile       | string    | Indicates mobile station if applicable |

---

## Reflection on replicability & reuse
This subset was created by taking the first 5,000 rows of the full dataset to keep the repository lightweight and suitable for classroom use. While this reduces the temporal coverage and may limit some analyses, it preserves the core structure and key variables for exploratory data analysis and teaching. The original dataset is publicly available on Kaggle, and users can reproduce or expand this subset by downloading the full data and applying a similar subsetting procedure.
