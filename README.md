# 🏡 California Housing Price Predictor

[![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python&logoColor=white)](https://www.python.org/)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)
[![GitHub Repo Size](https://img.shields.io/github/repo-size/SatyamKumar457/California-Housing-Price-Predictor)](https://github.com/SatyamKumar457/California-Housing-Price-Predictor)

---

## 🔍 Project Overview

The **California Housing Price Predictor** is a **machine learning project** that predicts **median house values** across California districts using **housing, demographic, and geographical features**.  

By leveraging real-world data and predictive modeling, this project provides **data-driven insights** into California's housing market and highlights the most influential factors affecting property prices.  

Key features used:  

- 🏘️ **Housing Median Age**  
- 🛏️ **Total Bedrooms**  
- 🛋️ **Total Rooms**  
- 👥 **Population**  
- 🏡 **Households**  
- 💰 **Median Income**  
- 🌍 **Latitude & Longitude**  
- 🌊 **Ocean Proximity**  

---

## 🛠️ Technologies Used

- **Python** – Programming language  
- **Libraries:** `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`  
- **Jupyter Notebook** – Development & visualization environment  

---

## 🧠 Machine Learning Workflow

1. **Data Exploration:** Analyze trends and correlations in the California housing dataset.  
2. **Data Preprocessing:** Handle missing values, encode categorical features, scale numerical data.  
3. **Feature Engineering:** Create features like `rooms per household` for better predictions.  
4. **Model Training:** Train **Linear Regression**, **Decision Tree**, and **Random Forest Regressor** models.  
5. **Evaluation:** Measure model performance using **RMSE** and **R² Score**.  
6. **Prediction & Insights:** Predict house prices for new data and determine feature importance.  

---

## 📊 Visual Insights

![Feature Importance](path/to/feature_importance_graph.png)  
*Most influential features affecting housing prices.*

![Prediction vs Actual](path/to/prediction_vs_actual_graph.png)  
*Comparison of predicted vs actual median house values.*

![Geographical Distribution](path/to/geographical_distribution_graph.png)  
*Median house prices visualized across California districts.*

---

## 💡 Key Insights

- 💰 **Median income** strongly predicts house prices.  
- 🌊 Proximity to the **ocean** increases property value.  
- 🏘️ **Population density** and **rooms per household** also impact pricing.  
- 🛠️ Data preprocessing and feature engineering improve model performance.  

---

## 🚀 Future Enhancements

- Integrate **Deep Learning models** for higher accuracy.  
- Build a **Web Interface** using Flask or Streamlit for real-time predictions.  
- Add **Interactive Maps** with Plotly or Folium to explore price distributions.  
- Incorporate additional data like **school ratings** and **economic indicators**.  

---

## 📂 Repository Structure
California-Housing-Price-Predictor/
│
├─ data/ # Dataset files
├─ notebooks/ # Jupyter notebooks for EDA & modeling
├─ models/ # Saved ML models
├─ graphs/ # Visualization outputs
├─ README.md # Project documentation
└─ requirements.txt # Python dependencies
