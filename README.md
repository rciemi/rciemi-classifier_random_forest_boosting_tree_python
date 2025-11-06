# ❤️ Heart Attack Classifier

This project builds a **Heart Attack (Stroke) Risk Classifier** in Python.  
It includes a single Jupyter notebook (`zajecia_2.ipynb`) and two CSV data files.

## 📘 Description
The goal of this project is to predict the risk of a heart attack (or stroke) based on patient health features.  
Three classification models were compared:
- **Decision Tree**
- **Random Forest**
- **Boosting (XGBoost / Gradient Boosting)**

## 🧠 Methods
- Data loaded from CSV files  
- Exploratory Data Analysis (EDA)  
- One-Hot Encoding for categorical variables  
- No standardization applied to numeric features (not required for tree-based models)  
- Model selection based on **sensitivity (recall)**

## 📊 Visualizations
The notebook includes:
- Feature distribution plots  
- Decision Tree visualization (`plot_tree`)  
- Confusion Matrix (`seaborn.heatmap`)  
- ROC and AUC curves  
- Feature importance plots  

## 🚀 How to Run
1. Open the notebook:
   ```bash
   jupyter notebook zajecia_2.ipynb
