#  House Price Prediction

Predicting house prices using regression models trained on the Kaggle dataset.

# Features
- Data Cleaning and Preprocessing
- One-hot Encoding
- Log-transformed target
- Ridge, Lasso, XGBoost models
- Cross-validation and RMSE evaluation

# How to Run
1. Open `01_modeling.ipynb` in Google Colab
2. Mount Google Drive
3. Place `train.csv` and `test.csv` in your Drive folder
4. Run all cells

# Model Evaluation

- **Cross-Validation RMSE**: ~ 0.13512381775167578


The model performs well in predicting log-transformed sale prices and generalizes effectively across validation folds.

# Conclusion

This project demonstrates:
- Data cleaning and preprocessing of real-world housing data
- Feature engineering and one-hot encoding
- Training and evaluating XGBoost regression models
- Interpreting feature importance and model performance metrics

Further improvements could include hyperparameter tuning, ensemble blending, and advanced feature selection.


# License
MIT License
