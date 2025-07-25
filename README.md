# Master-Thesis
# 📊 Predicting Workplace Hospitalization using Machine Learning

This repository contains the full code and research for my MSc thesis:  
**"Comparative Analysis of Machine Learning Models for Predicting Workplace Accident Severity"**

## 📘 Thesis Summary

This research uses machine learning models (Logistic Regression, Decision Tree, Random Forest, and XGBoost) to predict whether a workplace injury will result in hospitalization. The project is based on real data from the **OSHA Severe Injury Reports** and applies data preprocessing, feature engineering (including TF-IDF text analysis), and model optimization.

🔍 **Best Model:** XGBoost  
🎯 **Accuracy:** 92.6%  
📈 **AUC Score:** 0.967  
🧠 **Top Features:** Fracture injuries, finger injuries, geographic coordinates, "struck by person" event type

## 💻 Code and Tools

- Python, Pandas, Scikit-learn, XGBoost
- SHAP for model interpretability
- TF-IDF for processing injury narrative text
- Flask (for deployment demo)

## 📁 Contents

- `thesis.pdf` – Full written thesis
- `notebook.ipynb` – Code for training and evaluating models
- `shap_analysis/` – SHAP visualizations
- `data/` – Sample or processed data (if allowed)
- `api/` – Optional deployment script (Flask)

## 📊 Dataset

The data comes from the public OSHA Severe Injury Reports:
🔗 [https://www.osha.gov/severeinjury](https://www.osha.gov/severeinjury)

## 📄 License

This project is for academic use only. Contact me for permission to reuse the code or content.

## 🙋‍♀️ Author

**Fatemeh Radboy**  
MSc in Data Science and Artificial Intelligence  
Radtrade.2018@gmail.com
