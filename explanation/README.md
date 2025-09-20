# Part II – Machine Learning for Explanation

## Purpose
This Jupyter Notebook performs machine learning-based explanation and exploratory analysis on scholarly literature related to **Ulaanbaatar air pollution**, **Mongolia coal ban**, and **air pollution policy**. Instead of predicting outcomes, this part focuses on uncovering patterns, relationships, and insights in existing research to inform the main project question: *How effective are interventions in reducing PM2.5 and air pollution in Mongolia?*

---

## Contents / Steps

### Part I: Query Literature
- Retrieve scholarly articles from online sources (arXiv, OpenAlex, etc.) using relevant queries:
  - `"Ulaanbaatar air pollution"`
  - `"Mongolia coal ban"`
  - `"Mongolia PM2.5"`
  - `"air pollution AND machine learning"`
  - `"air pollution policy"`
- Store metadata in a `pandas` DataFrame, including title, abstract, year, and venue.

### Part II: Natural Language Processing (NLP) Analysis
1. **Word Cloud Generation**  
   - Visualize the most frequent words in abstracts to identify recurring themes and key terminology.

2. **Sentiment Analysis**  
   - Assess the sentiment (positive, negative, neutral) of each abstract using `TextBlob`.
   - Explore tone around policy interventions and health outcomes.

3. **Network Visualization**  
   - Construct a term co-occurrence network from abstracts using `NetworkX` and `matplotlib`.
   - **Centrality Measures:** Identify the most influential terms in the literature.
   - **Clustering Coefficient:** Examine local clustering patterns of key terms.

### Part III: Exploratory Metadata Analysis
- **Publication Year Distribution:** Histogram of the number of papers published per year to observe temporal trends in research activity.

---

## Deliverables / Outputs
- **Word clouds** highlighting common terms in literature.
- **Sentiment scores** and plots showing polarity distribution.
- **Network diagrams** with nodes sized by centrality and colored by clusters.
- **Histograms** showing publication trends over time.

---

## Integration / Notes
- This analysis enriches the literature review by revealing **dominant themes, relationships, and research patterns**.
- Network and NLP analyses provide **interpretation and explanation** beyond descriptive counts, supporting deeper understanding of existing work.
- Findings help refine the research focus on **air pollution reduction** and inform subsequent data-driven analyses in the project.
- Demonstrates the **AI Triad** in practice:  
  - **Data:** Scholarly article abstracts and metadata.  
  - **Algorithms:** NLP, sentiment analysis, network analysis.  
  - **Computing Power:** Jupyter Notebook for reproducible analysis and visualization.

---

**Discussion**  
   - What topics dominate research?  
   - How are policies framed?  
   - Which studies are central and influential?  

## Expected Outcomes  

- Clearer understanding of **key themes** in the literature.  
- Identification of **sentiment trends** around air pollution and energy policy.  
- Recognition of **research leaders and gaps** to guide further analysis.  
