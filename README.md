## U.S. Gun Violence Analysis (2013–2018)

### 📌 Project Overview

This project explores over 260,000 recorded gun violence incidents in the United States between 2013 and 2018. The primary goal is to identify patterns, uncover relationships, and inform data-driven discussions around prevention strategies and public policy.

### 📊 Key Questions Explored

How have gun violence trends changed over time?

Do more guns involved in an incident correlate with more casualties?

Which states experience the most gun violence?

Can incidents be grouped into meaningful clusters?

What seasonal or time-based trends exist in the data?

### 🔍 Methods & Tools Used

Python: pandas, seaborn, folium, sklearn, statsmodels

Tableau: for final analytical storyboard/dashboard

Analysis Techniques:

Exploratory Data Analysis (EDA)

Linear Regression Modeling

K-Means Clustering

Time Series Decomposition & ADF Test

Geospatial Visualization with Folium

### 📂 Repository Structure

/Gun-Violence-Analysis
│
├── 01 Project Overview
│   └── TASK 6.1- SOURCING OPEN DATA.pdf
│
├── 02 Data
│   ├── Gun_Violence_Clean_Data(2013-2018).csv
│   ├── Gun_Violence_Clustered_Data(2013-2018).csv
│   └── us-states.json
│
├── 03 Notebooks
│   ├── TASK 6.1-Sourcing Open Data.ipynb
│   ├── TASK 6.2-Exploring Relationships.ipynb
│   ├── TASK 6.3-Geographical Visualizations.ipynb
│   ├── TASK 6.4-Regression Analysis.ipynb
│   ├── TASK 6.5-Clustering.ipynb
│   └── TASK 6.6-Time Series Analysis.ipynb
│
├── 04 Visualizations
│   ├── correlation_heatmap.png
│   ├── scatter_killed_vs_injured.png
│   ├── choropleth_map.html
│   ├── regression_line.png
│   ├── cluster_scatter.png
│   └── timeseries_decomposition.png
│
└── 05 Tableau Link
    └── Presentation.twb

### 📊 Tableau Dashboard

Explore the interactive dashboard: Tableau Storyboard

Key Features:

Correlation and regression visuals

State-level gun violence heatmap

Clustering breakdowns of incidents

Daily death trend analysis with decomposition

### 📄 Data Sources

Primary Dataset: Kaggle Gun Violence Data (2013–2018)

GeoJSON for Mapping: US States boundary file

### 🚀 Next Steps

Incorporate socioeconomic and demographic join data

Extend time series to present day

Integrate real-world policy event timelines

For more information, visit the GitHub repo and Tableau dashboard linked above.

