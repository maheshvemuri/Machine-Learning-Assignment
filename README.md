# Interpreting Black-Box Models using SHAP and XGBoost

##  Overview
This project demonstrates how SHAP (SHapley Additive Explanations) can be used to interpret machine learning models, specifically XGBoost, in a classification task.

The goal is to improve transparency in machine learning by explaining both global model behaviour and individual predictions.

---

##  Objectives
- Build a high-performance XGBoost classification model
- Apply SHAP to interpret predictions
- Compare traditional feature importance with SHAP explanations
- Analyse feature interactions using SHAP interaction values

---

##  Dataset
The project uses the Breast Cancer Wisconsin dataset from scikit-learn.

- Number of samples: 569
- Number of features: 30
- Target: Binary classification (malignant vs benign)

This dataset is widely used for medical diagnosis research and is suitable for interpretability analysis.

---

##  Technologies Used
- Python
- scikit-learn
- XGBoost
- SHAP
- Matplotlib
- Pandas
- NumPy

---

##  Visualisations Included
The notebook generates the following figures:

1. Feature Importance Plot  
2. SHAP Summary Plot  
3. SHAP Beeswarm Plot  
4. SHAP Dependence Plot  
5. SHAP Force Plot (HTML)  
6. SHAP Interaction Summary Plot  
7. Feature Interaction Plot  
