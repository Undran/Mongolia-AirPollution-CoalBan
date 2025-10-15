# Evaluating the Impact of Mongolia’s 2019 Raw Coal Ban (RCB) on Air Pollution in Ulaanbaatar Using Machine Learning

## Project Title and Abstract
This project evaluates the environmental and social impact of Mongolia’s 2019 Raw Coal Ban (RCB) on urban air quality in Ulaanbaatar using machine learning and causal-inference methods. By combining Interrupted Time Series (ITS) analysis, exploratory data analysis (EDA), and counterfactual prediction models (Random Forest, Gradient Boosting, XGBoost), the study estimates how the RCB influenced fine particulate matter (PM₂.₅) levels. Complementary natural-language-processing (NLP) methods map global research trends on air-pollution policy. Together, these approaches provide a reproducible framework for evaluating environmental interventions and advancing sustainable, data-driven policymaking aligned with SDG 3 (Health), SDG 7 (Clean Energy), SDG 11 (Sustainable Cities), and SDG 13 (Climate Action).

## Authors and Roles
Author: Undran Enkhbaatar
Conceptualization and design of research framework
Data collection and preprocessing (OpenAQ datasets)
Statistical and machine-learning modeling (ITS, Random Forest, XGBoost)
Visualization and result interpretation
Documentation, poster, and final report preparation

## Disclaimer 
This repository supports the final research proposal submitted to STATS 201: Machine
Learning for Social Science, instructed by Prof. Luyao Zhang at Duke Kunshan
University in Autumn 2025.

## Acknowledgments
I would like to thank Prof. Luyao Zhang for her guidance and feedback, and Enkhjin Purevsukh for insightful comments on data sourcing and methodology refinement. I also acknowledge the OpenAQ platform for providing open-access air-quality data, and the open-source communities behind Python libraries such as pandas, scikit-learn, matplotlib, seaborn, and XGBoost. Generative AI tools (ChatGPT and Hugging Face Transformers) were used responsibly to assist with code optimization and literature summarization.

## Statement of Growth
Through this project, I developed advanced technical and analytical skills at the intersection of machine learning and social science. I learned to design reproducible research workflows, perform causal inference, and apply predictive modeling to real-world environmental data. The process deepened my understanding of ethical AI practices, interdisciplinary collaboration, and data transparency. Most importantly, it enhanced my ability to connect technical analysis with societal impact, shaping my growth as a socially responsible data scientist.

## Table of Contents
Code
Data

## Research Framework & AI Triad Integration
```mermaid
graph TD
    A["OpenAQ Datasets: 2015-2018 & 2020-2024"] --> B["Data Cleaning & Basic EDA (PM2.5)"]
    B --> C["Compare PM2.5 Levels Pre/Post Coal Ban"]
    C --> D["Descriptive Statistics & Hypothesis Testing"]
    D --> E["Time Series Analysis & Visualization (Monthly Avg PM2.5)"]
    E --> F["Counterfactual Analysis & Policy Impact Estimation"]

    A --> G["Machine Learning: Model Explanation"]
    G --> H["Machine Learning: Prediction"]


