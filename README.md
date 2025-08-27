# Soil-to-Solution-ML-Based-Crop-Suitability-Analysis
This notebook explores how machine learning can be used to analyze agricultural data and recommend suitable crops based on soil and environmental conditions. It combines regression and classification models with feature importance techniques to interpret the influence of variables like soil nutrients, temperature, humidity etc on crop suitability.
📌 Project Overview
This project explores how machine learning can be applied to agricultural data to recommend suitable crops based on soil and environmental conditions. Using regression and classification models, we analyze feature importance and evaluate predictive performance to support smarter farming decisions.

---

## 📊 Dataset
**Source**: [Crop Recommendation Dataset on Kaggle](https://www.kaggle.com/datasets/atharvaingle/crop-recommendation-dataset?resource=download)  
**Description**: The dataset was built by augmenting rainfall, climate, and fertilizer data from India.  
**Features**:
- `N`, `P`, `K`: Soil nutrient levels (Nitrogen, Phosphorus, Potassium)
- `temperature`: Temperature in °C
- `humidity`: Relative humidity in %
- `ph`: Soil pH value
- `rainfall`: Rainfall in mm
- `label`: Recommended crop type (target variable)

---

## 🔍 Exploratory Data Analysis (EDA)
- Distribution plots for all numerical features using KDE and histograms
- Correlation matrix to identify relationships between variables
- Visual inspection of feature distributions and outlier
