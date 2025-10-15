# Evaluating the Impact of Mongolia’s 2019 Raw Coal Ban (RCB) on Air Pollution in Ulaanbaatar Using Machine Learning

## Project Title and Abstract
This project evaluates the effect of Mongolia’s 2019 Raw Coal Ban on Ulaanbaatar’s PM₂.₅ levels using machine-learning and causal-inference methods. By combining Interrupted Time Series (ITS) analysis, exploratory data analysis (EDA), and counterfactual prediction models (Random Forest, Gradient Boosting, XGBoost), the study estimates how the RCB influenced fine particulate matter (PM₂.₅) levels. Complementary natural-language-processing (NLP) methods map global research trends on air-pollution policy. Together, these approaches provide a reproducible framework for evaluating environmental interventions and advancing sustainable, data-driven policymaking aligned with SDG 3 (Health), SDG 7 (Clean Energy), SDG 11 (Sustainable Cities), and SDG 13 (Climate Action).

<img width="113" height="113" alt="image" src="https://github.com/user-attachments/assets/585ef0aa-1d19-43c5-badb-bdc930cb24ba" />
<img width="113" height="113" alt="image" src="https://github.com/user-attachments/assets/988764b2-4bbc-47f7-9184-abdcd9e81b05" />
<img width="113" height="113" alt="image" src="https://github.com/user-attachments/assets/f0dbaf28-83c3-4e15-a83b-aa8629d33f0f" />
<img width="113" height="113" alt="image" src="https://github.com/user-attachments/assets/e5606777-32e1-470f-a42a-051adc3eef64" />

## Authors and Roles
Author: Undran Enkhbaatar

Roles:
- Conceptualization and design of research framework
- Data collection and preprocessing (OpenAQ datasets)
- Statistical and machine-learning modeling (ITS, Random Forest, XGBoost)
- Visualization and result interpretation
- Documentation, poster, and final report preparation

## Disclaimer 
This repository supports the final research proposal submitted to STATS 201: Machine
Learning for Social Science, instructed by Prof. Luyao Zhang at Duke Kunshan
University in Autumn 2025.

## Acknowledgments
I would like to thank Prof. Luyao Zhang for her guidance and feedback, and Enkhjin Purevsukh for insightful comments on data sourcing and methodology refinement. I also acknowledge the OpenAQ platform for providing open-access air-quality data, and the open-source communities behind Python libraries such as pandas, scikit-learn, matplotlib, seaborn, and XGBoost. Generative AI tools (ChatGPT and Hugging Face Transformers) were used responsibly to assist with code optimization and literature summarization.

## Statement of Growth
Through this project, I developed advanced technical and analytical skills at the intersection of machine learning and social science. I learned to design reproducible research workflows, perform causal inference, and apply predictive modeling to real-world environmental data. The process deepened my understanding of ethical AI practices, interdisciplinary collaboration, and data transparency. Most importantly, it enhanced my ability to connect technical analysis with societal impact, shaping my growth as a socially responsible data scientist.

### **Project Deliverables**
- [Code (Machine Learning Notebooks)](code/)
- [Data (OpenAQ Datasets)](data/)
- [Final Report (PDF)](docs/STATS201_Final.pdf)
- [Poster](docs/STATS201_Poster.pdf)
- [Field Trip Reflection](docs/Field_Trip_Reflection.pdf)
  
## Research Framework & AI Triad Integration
```mermaid
graph TD
    A["OpenAQ Datasets (Pre-Ban: 2015–2018, Post-Ban: 2020–2024)"] --> B["Data Cleaning & Exploratory Data Analysis (PM₂.₅)"]
    B --> C["Descriptive Statistics & Hypothesis Testing (t-test)"]
    C --> D["Interrupted Time Series (ITS) Analysis"]
    D --> E["Counterfactual Modeling & Policy Impact Estimation"]
    
    A --> F["Machine Learning for Explanation (NLP & Literature Mapping)"]
    F --> G["Network & Sentiment Analysis of Air-Pollution Studies"]
    
    D --> H["Machine Learning for Prediction (RF, GB, XGBoost)"]
    H --> I["Model Evaluation (RMSE, MAE, R², MAPE)"]
    I --> J["Counterfactual Forecasting of Post-Policy PM₂.₅"]

    subgraph AI_Triad["AI Triad Integration"]
        A["Data"] --> F
        F --> H
        H --> E
    end



