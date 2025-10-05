# Evaluating the Impact of Mongolia’s 2019 Raw Coal Ban on Air Pollution in Ulaanbaatar

## Abstract
Abstract:
This project investigates changes in air pollution in Ulaanbaatar before and after the 2019 raw coal ban using two OpenAQ datasets (2015–2018 pre-ban and 2020–2024 post-ban). The analysis focuses on basic exploratory data analysis (EDA), and time series analysis including visualizations and summary statistics for PM2.5. By comparing air quality pre- and post-policy, the study provides preliminary insights into the effectiveness of the coal ban and its potential public health implications, particularly in Ger districts. The project follows FAIR & CARE principles to ensure reproducibility, transparency, and ethical use of open-access data.

I would like to thank Professor Luyao Zhang and my classmate Enkhjin Purevsukh for their constructive feedback. Their guidance helped me:

- Correctly source post-2019 air quality data using OpenAQ.
- Strengthen literature review and clarify novelty.
- Define variables, intervention, and controls precisely.
- Expand methodology and account for weather/economic factors.
- Improve reproducibility, documentation, and ethical framing.



## System Configuration
- **Local Setup:** Python 3.10, Jupyter Notebook, pandas, matplotlib, seaborn, numpy, statsmodels
- **Cloud Setup:** Google Colab 

## Research Framework & AI Triad Integration
```mermaid
graph TD
    A["OpenAQ Datasets: 2015-2018 & 2020-2024"] --> B["Data Cleaning & Basic EDA (PM2.5)"]
    B --> C["Compare PM2.5 Levels Pre/Post Coal Ban"]
    C --> D["Descriptive Statistics & Hypothesis Testing"]
    D --> E["Time Series Analysis & Visualization (Monthly Avg PM2.5)"]
    E --> F["Counterfactual Analysis & Policy Impact Estimation"]
    F --> G["Machine Learning: Model Explanation (PM2.5)"]
    G --> H["Machine Learning: Prediction of PM2.5 Levels"]



