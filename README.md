# 🧠 Machine Learning Competition Project

This repository contains my solution for the **SOFTEC'26 Machine Learning Competition** on Kaggle.

## 📊 Results
- 🥇 Public Leaderboard Rank: **9 / 46**
- 🧪 Private Leaderboard Rank: **17 / 46**

The difference between public and private scores reflects generalisation performance on unseen data.

## 🚀 Approach

The solution is based on a structured machine learning pipeline:

- Data preprocessing and feature cleaning  
- Handling class imbalance using `scale_pos_weight`  
- Model training using **XGBoost**  
- Cross-validation with **Stratified K-Fold**  
- Threshold tuning to optimise **F1-score**  

## ⚙️ Model Details

- Model: XGBoost Classifier  
- Evaluation Metric: F1 Score  
- Validation Strategy: 5-Fold Stratified Cross-Validation  
- Optimisation: Threshold tuning on out-of-fold predictions  

## 📁 Files

- `train.csv` / `test.csv` → Dataset  
- `model.py` → Training and prediction pipeline  
- `submission.csv` → Final predictions  

## 📌 Key Learnings

- Importance of proper validation (CV vs leaderboard)  
- Handling imbalanced datasets effectively  
- Threshold tuning can significantly improve performance  
- Small improvements can impact leaderboard rankings  

## 🏁 Conclusion

This project demonstrates a practical end-to-end ML workflow, from preprocessing to model optimisation and evaluation in a competitive setting.

