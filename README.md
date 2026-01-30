# Analyzing Reddit Mental Health Discussions

**Identifying Key Themes and Influential Contributors Using Unsupervised Machine Learning**

## Overview

This project analyzes Reddit mental health discussions to uncover thematic patterns, identify influential contributors, and track temporal shifts in community concerns. Using unsupervised learning techniques on over 1 million posts from 28 subreddits spanning 2018-2020.

---

## 📄 Full Project Details

**[View Complete Project Report (PDF)](Reddit_Mental_health_analysis.pdf)**

The comprehensive report includes:
- Problem statement and objectives
- Dataset overview and statistics
- Detailed methodology
- Exploratory data analysis
- Clustering analysis (GMM)
- Topic modeling (LDA)
- Social network analysis
- Temporal analysis
- All visualizations and results
- Conclusions and recommendations

---

## Key Highlights

### Objectives
1. Discover dominant themes in mental health discourse
2. Detect influential contributors shaping conversations
3. Examine temporal shifts in community concerns

### Dataset
- **1,107,302 posts** from 28 subreddits
- **Timeframes:** 2018 (control), 2019 (baseline), 2020 (mid-pandemic)
- **Users:** 177K-327K across different periods

### Methodology
1. Data preprocessing with GPU-accelerated RAPIDS cuDF
2. Exploratory data analysis
3. Clustering with Gaussian Mixture Models (10 clusters)
4. Topic modeling with Latent Dirichlet Allocation (10 topics)
5. Social network analysis (PageRank, Degree Centrality)
6. Temporal trend analysis

### Key Results
- **10 distinct thematic clusters** with clear separation
- **Top influential users:** Gmail, Mylogin101, Swim010
- **COVID-19 impact:** Significant spike in activity during 2020
- **Sentiment variation:** Cluster 9 (40% negative) vs Clusters 6&8 (90%+ neutral)
- Strong alignment between subreddits and mental health topics

---

## Technologies Used

- **Data Processing:** RAPIDS cuDF, Pandas, NumPy
- **Machine Learning:** Scikit-learn (GMM, KMeans), Gensim (LDA)
- **Network Analysis:** NetworkX
- **Visualization:** Matplotlib, Seaborn, Plotly, WordCloud
- **NLP:** NLTK, TF-IDF Vectorization
- **Sentiment Analysis:** VADER

---
