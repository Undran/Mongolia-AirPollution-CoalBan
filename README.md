# Evaluating the Impact of Mongolia’s 2019 Raw Coal Ban on Air Pollution in Ulaanbaatar

## Abstract
This project investigates the effectiveness of Mongolia's 2019 raw coal ban in reducing air pollution in Ulaanbaatar, focusing on PM2.5 and PM10 concentrations from Ger districts. Using historical data from 2015–2018 and post-2019 measurements, we analyze trends, seasonal variations, and the policy's impact. Machine learning models will simulate counterfactual scenarios to estimate pollution levels without the ban, providing insights for policymakers and public health interventions.

## System Configuration
- **Local Setup:** Python 3.10, Jupyter Notebook, pandas, matplotlib, seaborn, numpy, statsmodels
- **Cloud Setup:** Google Colab

## Research Framework & AI Triad Integration
```mermaid
graph TD
A[Data: Air quality PM2.5 & PM10] --> B[Algorithms: Random Forest, Gradient Boosting]
B --> C[Predictive Modeling & Counterfactual Analysis]
A --> C
C --> D[Insights: Policy Evaluation]
