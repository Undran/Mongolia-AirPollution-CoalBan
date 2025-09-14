# EDA Notebook: eda_pm25.ipynb

**Purpose:**  
This Jupyter Notebook performs basic exploratory data analysis (EDA) on the `ulaanbaatar_pm25_subset.csv` dataset, which contains the **5,000 highest PM2.5 measurements** in Ulaanbaatar.

**Contents / Steps:**
1. **Load dataset:** Import the CSV from `data/`.
2. **Inspect data:** View the shape, columns, and first few rows.
3. **Summary statistics:** Compute descriptive statistics for numeric columns.
4. **Missing data check:** Identify columns with missing values.
5. **Categorical exploration:** Examine value counts for key categorical variables like `parameter`, `location`, `city`, and `sourcename`.
6. **Visualizations:**
   - Histogram of PM2.5 values.
   - Boxplot of PM2.5 by location.

**Integration / Notes:**
- The notebook uses a subset of the Kaggle dataset to keep performance high while analyzing extreme pollution events.
- This analysis supports further research into high pollution patterns, temporal trends, and spatial distribution of PM2.5 in Ulaanbaatar.
- Demonstrates the **AI Triad** by combining data exploration, visualization, and domain knowledge in environmental studies.
