# Ulaanbaatar Particulate Matter Subset (Ger Districts)

## Dataset Description
This dataset is a subset of the Ulaanbaatar Particulate Matter Pollution 2015–2018 dataset from OpenAQ, focusing on Ger district monitoring stations. It includes hourly PM2.5 and PM10 measurements from 10 key stations in Ger areas. The subset contains the first 2000 rows to make it manageable for analysis and visualization. It retains all columns from the original dataset, including date, parameter, location, value, unit, city, attribution, coordinates, country, sourcename, sourcetype, and mobile. This dataset can be used to evaluate air pollution trends in Ger districts and to explore the potential impact of energy transition policies, such as the 2019 raw coal ban.

## Data Dictionary

| Column       | Description |
|--------------|-------------|
| date         | Timestamp of measurement |
| parameter    | Pollutant type (PM2.5 or PM10) |
| location     | Monitoring station name |
| value        | Measured value of pollutant |
| unit         | Unit of measurement (µg/m³) |
| city         | City name (Ulaanbaatar) |
| attribution  | Data source attribution |
| coordinates  | Latitude and longitude of station |
| country      | Country code (MN) |
| sourcename   | Source organization name |
| sourcetype   | Type of source |
| mobile       | Boolean indicating if station is mobile |

## Replicability & Reuse
This dataset is derived from a publicly available dataset (OpenAQ) and can be reused for environmental, public health, and policy research. By sharing this subset along with processing code, researchers can reproduce analyses and adapt it for other temporal or spatial resolutions while respecting the FAIR principles (Findable, Accessible, Interoperable, Reusable) and CARE principles (Collective benefit, Authority to control, Responsibility, Ethics).
