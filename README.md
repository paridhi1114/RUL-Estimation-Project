# 🚀 Remaining Useful Life (RUL) Prediction for Turbofan Engines

This project focuses on predicting the Remaining Useful Life (RUL) of turbofan engines using a combination of traditional machine learning and deep learning models. Built entirely from scratch, it leverages the NASA C-MAPSS FD004 dataset and compares the performance of CNN-LSTM, Random Forest, and XGBoost regressors.

## 📂 Dataset

- Dataset: NASA C-MAPSS FD004 (Complex operating conditions & multiple fault modes)
- Features: Sensor readings, operational settings
- Target: Remaining Useful Life (RUL)

## 🧠 Models Used

| Model         | Description |
|---------------|-------------|
| CNN-LSTM      | Captures spatial and temporal patterns in multivariate time series |
| XGBoost       | Boosted decision tree regressor for tabular data |
| Random Forest | Ensemble model leveraging multiple decision trees |

## 📈 Evaluation Metrics

- MAE (Mean Absolute Error)
- RMSE (Root Mean Squared Error)
- R² Score
- ±10 Cycles Accuracy (custom metric)

## 📊 Visualizations Included

- Correlation matrix
- Feature heatmaps
- Training vs. validation loss curve
- Prediction vs. actual RUL comparison
- Model performance heatmap

## 🛠️ Features

- Full preprocessing pipeline (normalization, sequence generation, RUL computation)
- Model training & evaluation for all three models
- Comparison dashboard with visualizations
- Model saving (.keras, .pkl formats)

## 🧪 Requirements

Install dependencies:

```bash
pip install -r requirements.txt
