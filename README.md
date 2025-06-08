# MLPP-2025
MLPP25 // Broadband accessibility and the digital divide.


# Broadband Accessibility and the Digital Divide

**Author**: Bhargav Pathuri  
**Course**: Machine Learning for Public Policy (MLPP 2025)  
**Year**: 2025  

---

##  Project Overview

This project investigates the **digital divide** in broadband access across U.S. counties by identifying the **socioeconomic factors** contributing to disparities. Using publicly available Census datasets and machine learning techniques, we quantify how factors such as income, education, and employment affect broadband accessibility.

---

##  Objectives

- Analyze **county-level geospatial and demographic data**
- Visualize patterns in broadband accessibility
- Use ML models to **predict and understand disparities**
- Identify key drivers of **digital inequality**

---

##  Methodology

### 1. **Data Collection**
- Data sourced from U.S. Census ACS (2019–2023) on:
  - Social Characteristics (DP02)
  - Economic Characteristics (DP03)
  - Demographic & Housing (DP05)
  - Population Estimates (S0201)
  - Internet & Computer Use (S2801)

### 2. **Preprocessing**
- Removed null/missing data (e.g., Puerto Rico rows)
- Imputed missing median income values
- Retained outliers to preserve real-world disparities

### 3. **Exploratory Data Analysis (EDA)**
- Median broadband usage: **85.27%**
- Income, education, and employment levels show **strong correlation** with broadband access

---

##  Machine Learning Models

###  **Classification – Random Forest Classifier**
- Target: Binary broadband access (above/below national median)
- Accuracy: **82%** | AUC: **0.90**
- Most important feature: **Median Income**

###  **Regression – Random Forest Regressor**
- Target: Poverty Rate  
- R² Score: **0.72**  
- Key insight: **Poverty is inversely correlated with broadband access**

###  **Clustering – K-Means**
- Clustered counties based on **Median Income**
- Revealed clear income-employment-poverty patterns affecting broadband access

---

##  Key Insights

- **Median income** is the strongest predictor of broadband availability
- The **income-employment-poverty triad** significantly shapes digital access
- Economic disparity—not technological infrastructure—is the primary barrier

---

##  Tools & Technologies

- Python (pandas, numpy, matplotlib, seaborn)
- scikit-learn (Random Forest, KMeans, GridSearchCV)
- Jupyter Notebook
- Geopandas / Geospatial Mapping

---

##  Future Work

- Include additional features (e.g., ISP availability, local policies)
- Explore temporal changes using broadband trends over years
- Investigate interventions to bridge the digital divide

---

##  Files Included

- `mlpp25_project_bpathuri.ipynb`: Complete code with explanations, extract it from WinRAR
- `MLPP 2025 Datasets`: All the datasets and files required for this project, downloaded from https://data.census.gov/
- Download the tl shape files from https://data.census.gov/
- `Broadband accessibility and the digital divide -Bhargav Pathuri.pptx`: Final project presentation

---

##  Contact

Feel free to connect:  
LinkedIn Profile Link :- www.linkedin.com/in/bhargav-pathuri-2486b61a7
Email: bpathuri@udel.edu

---

