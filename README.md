#  Advanced Analytics & Dashboard Design – Achievement 6

**Project Title:** Interactive Analysis & Visualization with Python and Tableau  
**Role:** Data Analyst  
**Tools:** Python, Pandas, Matplotlib, Seaborn, Scikit-learn, Statsmodels, Tableau Public

##  Project Summary

This project focuses on performing advanced exploratory and statistical analysis on a real-world dataset, and presenting key findings through an interactive dashboard. The goal is to uncover meaningful insights through supervised and unsupervised learning, geospatial analysis, and time series forecasting—then visualize those insights for stakeholders using Tableau.

##  Objectives

- Opensource dataset used: World University Rankings
- Perform the following types of analysis:
  - Exploratory data visualization
  - Regression modeling
  - Clustering analysis
  - Time series forecasting
  - Geospatial visualization

- Build an **interactive Tableau dashboard** to summarize findings.
- Document all Python analysis and code on GitHub.

##  Research Questions

- What patterns or trends exist in the dataset?
- Are there geographic differences in behavior or outcomes?
- Can variables predict a target outcome using regression?
- Are there natural clusters in the data?
- What does the time-based behavior look like?

##  Analyses Conducted

- **Exploratory Analysis:** Correlation heatmaps, pairplots, histograms, and categorical plots.
- **Geospatial Analysis:** Choropleth map using shapefile + Python (GeoPandas or Plotly).
- **Regression Analysis:** Linear regression with train/test split, evaluation metrics (R², RMSE).
- **Cluster Analysis:** K-means clustering with Elbow Method; visualized clusters and descriptive summaries.
- **Time Series Forecasting:** Decomposition, Dickey-Fuller test, differencing for stationarity, ACF/PACF plots.

##  Tableau Dashboard

An interactive Tableau dashboard was created to summarize the curated results from the analyses and communicate insights effectively to stakeholders.

 **[View Dashboard on Tableau Public](provided in future)**  

## 📁 Repository Structure


achievement6-dashboard/
│
├── data/                      # Raw and cleaned datasets
│   └── ...
│
├── scripts/                   # Jupyter Notebooks for analysis
│   ├── 01_exploration.ipynb
│   ├── 02_geospatial.ipynb
│   ├── 03_regression.ipynb
│   ├── 04_clustering.ipynb
│   ├── 05_timeseries.ipynb
│
├── outputs/                   # Visuals and exported datasets
│   └── ...
│
├── README.md                  # This file
└── requirements.txt           # Python environment dependencies (optional)
