# Walmart Demand Forecasting using XGBoost

## Business Problem
Retail demand forecasting is critical for inventory optimization, revenue maximization, and supply chain efficiency.  
This project builds a **business-safe, explainable ML system** to predict weekly demand at store–department level using historical Walmart sales data.

---

## Project Highlights
- Time-series aware train/validation/test split (no data leakage)
- XGBoost regression with regularization
- Feature pruning based on SHAP & permutation importance
- Model explainability using SHAP (global + local)
- Business-safe modeling decisions (generalization > overfitting)

---

## Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- XGBoost
- SHAP
- Matplotlib / Seaborn
- Streamlit (planned)

---

## Model Performance (Final)
| Split | MAE | RMSE | R² |
|------|-----|------|----|
| Train | 2702 | 4648 | 0.962 |
| Validation | 6654 | 11071 | 0.656 |
| Test | 6615 | 10007 | 0.741 |

> Note: Performance prioritizes stability and generalization on noisy retail time-series data.

---

## Repository Structure
