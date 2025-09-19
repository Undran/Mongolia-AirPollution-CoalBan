# EDA Notebook: compare_pre_post.ipynb

**Purpose:**  
This Jupyter Notebook performs basic exploratory data analysis (EDA) on the OpenAQ Ulaanbaatar air quality datasets (2015–2018 and 2020–2024) to evaluate the impact of the 2019 raw coal ban on PM2.5 and PM10 levels.

**Contents / Steps:**
Load dataset: Import the pre- and post-2019 CSV files from data/.

Inspect data: View the shape, columns, and first few rows.

Data cleaning: Handle missing/invalid values (value = -999), convert timestamps to datetime.

Summary statistics: Compute mean, standard deviation, and counts for PM2.5 and PM10.

Hypothesis testing: Perform Welch’s two-sample t-test to compare pre- and post-coal ban values.

Time series aggregation: Compute monthly average PM2.5 and PM10 concentrations.

Visualizations:

Line plots of monthly average PM2.5 and PM10 pre/post policy

Boxplots and histograms for distribution analysis

Preliminary insights: Identify trends and changes in air quality after the coal ban.

**Integration / Notes:**

The notebook demonstrates the AI Triad:

Data: OpenAQ pre/post datasets

Algorithms: Aggregation, grouping, hypothesis testing, visualization

Computing Power: Jupyter Notebook (local or cloud)

This analysis provides a foundation for further research into air pollution trends, seasonal patterns, and public health implications in Ulaanbaatar.

All code is modular, reproducible, and well-documented for reuse.
