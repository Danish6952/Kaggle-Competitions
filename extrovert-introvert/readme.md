# 🧠 Extrovert vs Introvert Predictor

This repository contains my solution to a Kaggle binary classification competition. The goal was to predict whether a person is an **extrovert** or **introvert** based on behavioral or survey-based features.

> 🏆 **Top 75%** out of 4329 participants on the public leaderboard.

---

## 🚀 Overview

- **Problem Type:** Binary Classification  
- **Target Variable:** Personality Type (Extrovert = 1, Introvert = 0)  
- **Main Model Used:** XGBoost Classifier  
- **Libraries:** Python, Pandas, NumPy, Scikit-learn, XGBoost, Matplotlib, Seaborn

---

## ⚙️ Model Details

- 80/20 stratified train-validation split  
- Early stopping after 20 rounds (based on AUC score)  
- Core hyperparameters:
  - `n_estimators=300`
  - `learning_rate=0.06`
  - `max_depth=7`
  - `subsample=0.8`
  - `colsample_bytree=0.8`
  - `gamma=0.1`
  - `min_child_weight=3`

---

## 📈 Results (Validation)

| Metric     | Score |
|------------|-------|
| Accuracy   | 0.97% |

