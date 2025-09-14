# Exploratory Data Analysis: Ulaanbaatar Air Pollution

## Overview
This Jupyter Notebook (`eda_air_pollution.ipynb`) performs **exploratory data analysis (EDA)** on the Ulaanbaatar Particulate Matter dataset (2015–2018), focusing on **PM2.5 and PM10 concentrations**. The analysis emphasizes **Ger districts**, where air pollution is highest due to household coal use. The EDA provides insights into temporal trends, seasonal patterns, and potential policy impacts, particularly the 2019 raw coal ban.

## Key Steps in the Notebook

1. **Dataset Download**
   - Programmatically download the dataset from Kaggle using the Kaggle API.
   - Extract the files to the `data/` folder.

2. **Data Loading and Cleaning**
   - Load CSV into a Pandas DataFrame.
   - Convert `timestamp` column to datetime.
   - Filter for Ger district stations (subset of all stations).

3. **Exploratory Data Analysis**
   - Summary statistics of PM2.5 and PM10.
   - Check for missing values and handle accordingly.
   - Visualize temporal trends of PM2.5 and PM10.
   - Seasonal decomposition for PM2.5 to examine yearly cycles.

4. **Visualization**
   - Line plots for PM2.5 and PM10 trends.
   - Seasonal decomposition plots for cyclic behavior.

5. **Saving Processed Data**
   - Filtered Ger district subset saved as `ulb_pm_ger_districts.csv` for further modeling.

## Requirements
- Python 3.x
- pandas
- matplotlib
- seaborn
- statsmodels
- kaggle (for dataset download)

## Purpose
This notebook serves as the foundation for analyzing the impact of Mongolia’s 2019 **raw coal ban** on air pollution in Ulaanbaatar. Cleaned and visualized data will be used for predictive modeling, counterfactual simulations, and policy evaluation.
