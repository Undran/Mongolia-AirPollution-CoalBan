# Dataset: OpenAQ Air Quality Data for Ulaanbaatar

**Description (100–150 words)**  
This folder contains two open-access datasets from OpenAQ that provide air quality measurements for Ulaanbaatar, Mongolia. The datasets cover periods **pre-2019** (2015–2018) and **post-2019** (2020–2024) to analyze the impact of Mongolia's 2019 raw coal ban on air pollution in Ger districts. Both datasets include hourly and daily measurements of **PM2.5**, which is a key indicator of air pollution and public health risks. The data has been cleaned and merged to facilitate **descriptive analysis, hypothesis testing, and time series visualization**. The structure is suitable for replicable research and reuse, supporting FAIR principles (Findable, Accessible, Interoperable, Reusable) and CARE principles (Collective Benefit, Authority to Control, Responsibility, Ethics).


---

## Data dictionary
| Variable Name    | Description                                           | Type       | Units        | Notes / Missingness |
|-----------------|-------------------------------------------------------|-----------|-------------|-------------------|
| datetimeUtc     | Timestamp of measurement in UTC                       | datetime  | ISO 8601    | Some missing values handled in cleaning |
| location        | Monitoring station name                                | string    | N/A         | Station-level metadata |
| city            | City name (Ulaanbaatar)                               | string    | N/A         | Constant for all records |
| country         | Country code (MN)                                     | string    | N/A         | Constant for all records |
| parameter       | Pollutant measured (PM2.5 or PM10)                   | string    | N/A         | Filtered for PM2.5/PM10 only |
| value           | Measured pollutant concentration                      | float     | µg/m³       | Missing values omitted in analysis |
| unit            | Measurement unit                                     | string    | µg/m³       | Constant for filtered data |
| period          | Categorization as "pre-2019" or "post-2019"         | string    | N/A         | Created for comparative analysis |

---

## Replicability & Reuse
- Data are **open-access** via OpenAQ, ensuring reproducibility.  
- The cleaned subset in this folder includes only the variables needed for analysis.  
- Researchers can **reuse the datasets** for additional analyses such as time series modeling, seasonal trend analysis, or health impact studies.  
- Scripts in the `code/` folder show how to load, clean, and analyze these datasets.  
