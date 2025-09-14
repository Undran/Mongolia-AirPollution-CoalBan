# Exploratory Data Analysis: Ulaanbaatar Air Pollution

## Overview
This Jupyter Notebook (`eda_air_pollution.ipynb`) performs exploratory data analysis on the Ulaanbaatar Particulate Matter dataset (2015–2018), focusing on PM2.5 and PM10 levels, particularly in Ger districts. Analysis includes temporal trends, seasonal decomposition, and missing data checks.

## Key Steps
1. Download dataset from Kaggle via API.
2. Load CSV into a Pandas DataFrame.
3. Convert timestamp to datetime and filter Ger district stations.
4. Perform summary statistics and check missing values.
5. Plot PM2.5 and PM10 trends over time.
6. Seasonal decomposition of PM2.5 to understand yearly patterns.
7. Save filtered Ger district dataset for further analysis.

## Requirements
- Python 3.x
- pandas
- matplotlib
- seaborn
- statsmodels
- kaggle (for dataset download)

## Purpose
Provides a foundation for analyzing the impact of the 2019 raw coal ban on air quality in Ulaanbaatar. Cleaned and visualized data will be used for predictive modeling and counterfactual analysis.
