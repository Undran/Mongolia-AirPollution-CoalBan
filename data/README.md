# Dataset: Ulaanbaatar Particulate Matter Sensor Data (subset)

**Description (100–150 words)**  
This dataset is a subset of the publicly available “Ulaanbaatar Particulate Matter Sensor Data (2015–2018)” dataset from Kaggle. To make the dataset manageable for classroom analysis, only the first 5,000 rows of the original CSV were included. The subset contains measurements from multiple monitoring stations across Ulaanbaatar, Mongolia, including PM2.5 and PM10 concentrations, timestamps, and station identifiers. This smaller dataset is intended for exploratory data analysis, visualization, and teaching purposes. Users who need full temporal coverage or the complete dataset distribution should refer to the original dataset on Kaggle. The subset preserves the structure and key variables of the original data while significantly reducing file size, making it easier to load and analyze in Python or Jupyter Notebook. 

---

## Data dictionary (update types if needed)
| name       | type      | description |
|------------|-----------|-------------|
| datetime   | datetime  | Timestamp of measurement (local time) |
| station    | string    | Monitoring station identifier or name |
| PM2.5      | float     | PM2.5 concentration in µg/m³ |
| PM10       | float     | PM10 concentration in µg/m³ |
| unit       | string    | Measurement unit (µg/m³) |
| source     | string    | Original data source or notes |


---

## Reflection on replicability & reuse
This subset was created by taking the first 5,000 rows of the full dataset to keep the repository lightweight and suitable for classroom use. While this makes the dataset easy to work with and share, it may reduce replicability for analyses that require the full data distribution or complete temporal coverage. The original dataset is still publicly available on Kaggle, and users can recreate or expand this subset by downloading the full data and running a similar subsetting procedure.
