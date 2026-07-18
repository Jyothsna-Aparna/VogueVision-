# VogueVision 👗✨
### AI-Powered Fashion Intelligence System

An end-to-end machine learning project combining **price prediction, recommendation systems, computer vision, and time-series forecasting** on real-world retail data from the H&M Personalized Fashion Recommendations dataset (Kaggle).

## 🎯 Overview
VogueVision demonstrates how AI/ML can be applied across the fashion retail value chain — from predicting prices and recommending products, to classifying styles from images and forecasting demand trends.

## 🧩 Modules

| Module | Technique | Goal |
|---|---|---|
| Price Prediction | Random Forest Regression | Predict product price from attributes |
| Recommendation System | TF-IDF + Cosine Similarity | Suggest similar products |
| Style Classification | CNN (Transfer Learning - MobileNetV2) | Classify products by category from images |
| Demand Forecasting | Exponential Smoothing (Time Series) | Forecast future sales by category |

## 🛠️ Tech Stack
- **Language:** Python
- **Data Handling:** Pandas, NumPy
- **ML:** scikit-learn
- **Deep Learning:** TensorFlow / Keras
- **Time Series:** statsmodels
- **Visualization:** Matplotlib, Seaborn

## 📊 Dataset
[H&M Personalized Fashion Recommendations](https://www.kaggle.com/competitions/h-and-m-personalized-fashion-recommendations) — includes 100K+ articles, customer data, and 31M+ transaction records.

## 📈 Results
*(Update this section after running the notebook)*
- Price Prediction MAE: `TODO`
- Demand Forecast MAE: `TODO`
- Image Classification Accuracy: `TODO`

## 🚀 How to Run
1. Open `VogueVision.ipynb` in Google Colab
2. Get a Kaggle API key (`kaggle.json`) from your Kaggle account settings
3. Run cells top to bottom — dataset downloads automatically via Kaggle API

## 💡 Key Learnings
- Handling large-scale real-world retail data (sampling strategies for memory efficiency)
- Combining multiple ML paradigms (regression, similarity search, CV, time series) in one coherent project
- Building recommendation logic from unstructured product descriptions

## 🔮 Future Improvements
- Deploy as an interactive Streamlit web app
- Add collaborative filtering (using customer purchase history) alongside content-based recommendations
- Expand image classification to more fine-grained style attributes
-
