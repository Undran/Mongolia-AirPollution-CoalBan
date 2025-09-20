# Prediction – Machine Learning for PM2.5

This folder contains the code and results for Part III – Machine Learning for Prediction of PM2.5 levels in Ulaanbaatar, comparing pre- and post-2019 coal ban data.

---

## Dataset

- Source: [OpenAQ](https://openaq.org)  
- Pre-ban data: [`openaq_pre2019.csv`](https://raw.githubusercontent.com/Undran/Mongolia-AirPollution-CoalBan/refs/heads/main/data/openaq_pre2019.csv)  
- Post-ban data: [`openaq_post2019.csv`](https://raw.githubusercontent.com/Undran/Mongolia-AirPollution-CoalBan/refs/heads/main/data/openaq_post2019.csv)  

### Features
- Month, day-of-year, cyclical features (sin/cos)  
- Lagged PM2.5 (t-1, t-7)  
- 7-day rolling mean  
- Location encoding  

---

## Methods

Algorithms: Linear Regression, Random Forest, Gradient Boosting, XGBoost  
Evaluation: RMSE, MAE, R², MAPE  

---

## Results

| Model             | RMSE  | MAE   | R²    | MAPE (%) |
|-------------------|-------|-------|-------|----------|
| Linear Regression | ~168  | ~125  | 0.01  | ~38      |
| Random Forest     | ~154  | ~113  | 0.08  | ~32      |
| Gradient Boosting | ~154  | ~114  | 0.08  | ~33      |
| XGBoost           | ~154  | ~114  | 0.08  | ~33      |

---

## Visualizations

- Metric comparison barplots  
- Observed vs predicted scatterplots  
- Monthly trend plots  

---

## Discussion

- Ensemble models outperform linear regression due to nonlinear pollution patterns  
- Trade-off between accuracy and interpretability  
- Predictive ML can support coal ban evaluation and inform policy  

---

## Usage

Open the Jupyter Notebook:  
```bash
jupyter notebook ML_Prediction.ipynb

