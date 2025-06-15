# 🌞 Summer Analytics 2025 - Hackathon Solution 🚀

This repository contains my solution to the **Summer Analytics First Hackathon 2025**, hosted on Kaggle. The task involved performing land cover classification using NDVI (Normalized Difference Vegetation Index) data.

🔗 [View the Kaggle Notebook](https://www.kaggle.com/code/harshitstark/code-for-summer-analytics-first-hackathon/notebook)

## 📌 Problem Statement

The goal was to classify different types of land cover based on satellite-derived NDVI data using machine learning. The dataset contains features derived from spectral bands and NDVI values, along with labeled land cover types.

## 📂 Dataset

The dataset was provided as part of the competition and includes:

- `train.csv`: Features + target labels
- `test.csv`: Features without labels
- `sample_submission.csv`: Format for final predictions

> 📎 Note: The dataset was provided on the competition page and may not be publicly available post-event.

## ⚙️ Approach

- **Data Preprocessing**:
  - Checked for missing/null values
  - Performed EDA to understand feature distributions and correlations

- **Feature Engineering**:
  - Created derived features from NDVI statistics
  - Normalized input features

- **Model Used**:
  - 🎯 **XGBoost Classifier** with hyperparameter tuning
  - Used Stratified K-Fold Cross-Validation

- **Evaluation Metric**:
  - Macro F1 Score

## 📈 Results

- Achieved a validation score of **F1 ≈ 0.84440**

## 📌 Key Highlights

- 📊 Clean and interpretable EDA
- 💡 Feature importance visualization
- 🧠 Optimized XGBoost model with early stopping and learning rate tuning
- 📤 Final predictions saved in submission-ready format

