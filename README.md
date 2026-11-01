# Stroke Prediction Using Machine Learning

## Overview
Developed a machine learning-based stroke prediction system using healthcare data to analyze patient health attributes and identify potential stroke risk factors.

## Tech Stack
- Python, Pandas, NumPy
- Matplotlib, Seaborn, Plotly
- Scikit-learn, XGBoost

## Key Features
- Performed data cleaning, missing value imputation, and feature engineering.
- Conducted EDA to analyze relationships between health attributes and stroke occurrence.
- Addressed class imbalance using random oversampling.
- Applied feature encoding and MinMax scaling.
- Trained and compared four classification models:
  - Extra Trees Classifier
  - Random Forest Classifier
  - XGBoost
  - Gradient Boosting

## Model Performance

| Model | Test Accuracy |
|---|---:|
| Extra Trees | 99.59% |
| Random Forest | 98.77% |
| XGBoost | 97.53% |
| Gradient Boosting | 99.02% |

*Reported results from the initial implementation; validation is required to rule out data leakage.*

## Evaluation Metrics
Accuracy, Precision, Recall, F1-Score, and Confusion Matrix.

## How to Run
```bash
git clone https://github.com/your-username/Stroke-Prediction-ML.git
pip install pandas numpy matplotlib seaborn plotly scikit-learn xgboost
```
Open `stroke_prediction.ipynb` in Jupyter Notebook or Google Colab and run the cells.

## Author
**Aniket Pratap Singh**
