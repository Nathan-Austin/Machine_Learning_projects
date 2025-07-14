# Customer Churn Prediction

This project explores machine learning techniques to predict bank customer churn. The main notebook `bank_churn.ipynb` uses **PyCaret** to preprocess the data, compare multiple classification algorithms, and build a tuned model. Pretrained models are saved as `.pkl` files for later use.

## Contents
- `bank_churn.ipynb` – Model training and evaluation with PyCaret.
- `bank_churn.csv` – Dataset used for training.
- Saved models:
  - `saved_model_gbc.pkl`
  - `saved_balanced_model_rf.pkl`
  - `saved_xgboost_model.pkl`

Run the notebook to reproduce the analysis or load one of the saved models to make predictions on new data.
