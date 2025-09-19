# EDA Notebook: compare_pre_post.ipynb
## Purpose
This Jupyter Notebook performs basic exploratory data analysis (EDA) on the OpenAQ Ulaanbaatar air quality datasets (2015–2018 and 2020–2024). The analysis evaluates the impact of Mongolia’s 2019 raw coal ban on PM2.5 levels in Ger districts.

## Contents / Steps

1. **Load dataset**  
   Import the pre- and post-2019 CSV files from the `data/` folder.

2. **Inspect data**  
   View the shape, columns, and first few rows to understand the structure.

3. **Data cleaning**  
   Handle missing or invalid values (`value = -999`) and convert timestamps to `datetime`.

4. **Summary statistics**  
   Compute mean, standard deviation, and counts for PM2.5.

5. **Hypothesis testing**  
   Perform Welch’s two-sample t-test to compare pre- and post-coal ban values.

6. **Time series aggregation**  
   Compute monthly average PM2.5concentrations.

7. **Visualizations**  
   - Line plots of monthly average PM2.5 policy  
   - Boxplots and histograms for distribution analysis

8. **Preliminary insights**  
   Identify trends and changes in air quality after the coal ban.

## Integration / Notes

- Demonstrates the **AI Triad**:
  - **Data:** OpenAQ pre/post datasets
  - **Algorithms:** Aggregation, grouping, hypothesis testing, visualization
  - **Computing Power:** Jupyter Notebook (local or cloud)
- Provides a foundation for further research into air pollution trends, seasonal patterns, and public health implications in Ulaanbaatar.
- All code is modular, reproducible, and well-documented for reuse.
