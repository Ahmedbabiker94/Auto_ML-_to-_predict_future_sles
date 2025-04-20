# Auto_ML-_to-_predict_future_sles
a custom-built AutoML pipeline for time series sales forecasting, integrating both classical machine learning and deep learning models to deliver accurate future predictions.
The system automates data preprocessing, denoising, feature engineering, model training, hyperparameter tuning, and model selection.

The primary goal is to predict sales for the next 7 days using historical sales data.


Why XGBoost Outperformed Transformer?

In the current results, XGBoost outperformed the Transformer model in terms of MSE. This can be attributed to:

XGBoost's strength on tabular data with limited noise and engineered features.

Short training duration for Transformer (10 epochs during tuning).

Lack of sequence windowing or temporal attention optimization in Transformer setup.

Transformers typically require larger datasets and more epochs to generalize well.

Technologies Used:

Python

Pandas, NumPy

Scikit-learn

XGBoost

PyTorch (for Transformer)

Optuna (for hyperparameter tuning)

Matplotlib (for visualization)

