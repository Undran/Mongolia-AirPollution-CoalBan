# Evaluating the Impact of Mongolia’s 2019 Raw Coal Ban on Air Pollution in Ulaanbaatar

## Abstract
Abstract:
This project investigates changes in air pollution in Ulaanbaatar before and after the 2019 raw coal ban using two OpenAQ datasets (2015–2018 pre-ban and 2020–2024 post-ban). The analysis focuses on basic exploratory data analysis (EDA), and time series analysis including visualizations and summary statistics for PM2.5. By comparing air quality pre- and post-policy, the study provides preliminary insights into the effectiveness of the coal ban and its potential public health implications, particularly in Ger districts. The project follows FAIR & CARE principles to ensure reproducibility, transparency, and ethical use of open-access data.

## System Configuration
- **Local Setup:** Python 3.10, Jupyter Notebook, pandas, matplotlib, seaborn, numpy, statsmodels
- **Cloud Setup:** Google Colab

## Research Framework & AI Triad Integration
```mermaid
graph TD
    A[OpenAQ Datasets: 2015-2018 & 2020-2024] --> B[Data Cleaning & Basic EDA]
    B --> C[Compare PM2.5 Pre/Post Coal Ban]
    C --> D[Time Series Visualization (Monthly Avg PM2.5/PM10)]
    D --> E[Preliminary Insights on Air Quality Changes]
