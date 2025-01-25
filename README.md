# Wildfire Risk Prediction Project

## Overview
This project focuses on using machine learning techniques to predict **wildfire risks and behavior** in the United States. The goal is to develop a **predictive model** that can assist public agencies, environmental organizations, and local communities in **wildfire prevention and resource allocation**.

## Features
- **Data Collection & Cleaning**: Historical wildfire data (1992–2020) from FPARS, FIRIS, and the National Interagency Fire Center.
- **Exploratory Data Analysis (EDA)**: Identifies wildfire trends, seasonality, and geographic distribution.
- **Machine Learning Models**:
  - Clustering: K-means, Hierarchical, and Gaussian Mixture Models (GMM).
  - Classification: Random Forest, XGBoost.
  - Regression: Gradient Boosting, XGBoost, Random Forest, Decision Tree.
- **Geospatial Analysis**: GIS-based mapping for **high-risk wildfire zones**.
- **Visualization**: Interactive **dashboard in Power BI**.

## Dataset
The dataset includes **over 2.3 million wildfire records** with attributes like:
- **Fire size, duration, cause (natural, accidental, criminal, unknown)**.
- **Geographic attributes**: Latitude, longitude, and state-wise wildfire patterns.
- **Temporal attributes**: Seasonal trends, peak months, and discovery time.

## Results
- **Feature Engineering improved model accuracy significantly**.
- **Gradient Boosting Regression performed best** with **96% accuracy (R² = 0.9619)**.
- **Geospatial risk maps** highlight high-risk regions like **California, Texas, and Oregon**.
- **Power BI dashboard** provides real-time wildfire insights.

## Contributors
- **Vaidehi Patel**
- **Mohini Kathrotiya**
- **Omkar Aurangabadkar**
- **Yash Balwir**

## Future Work
- **Real-time data integration** for live wildfire risk assessment.
- **Deployment on cloud platforms** (AWS, GCP).
- **Improved interpretability using SHAP analysis**.

## References
- **Short, K.C. (2022)** - *Spatial wildfire occurrence data for the US (1992-2020)*.
- **Patil, S. (2023)** - *Forest fire prediction using ML*.
- **Garg, U. et al. (2023)** - *Random Forest for wildfire forecasting*.

---
