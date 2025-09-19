# WHO Air Quality Analysis

Analyze WHO Air Quality data with **EDA, PCA, Regression, and Classification**.
Predict PM2.5 levels and classify regions into **High vs Low pollution risk**.

## Features

* **EDA**: PM2.5 distribution, correlation heatmap
* **PCA**: Dimensionality reduction & visualization
* **Regression**: Linear Regression for PM2.5 prediction
* **Classification**: Logistic Regression (High vs Low PM2.5)
* **Metrics & Plots**: R², RMSE, MAE, Confusion Matrix, ROC Curve

## Setup

```bash
git clone https://github.com/your-username/air-quality-analysis.git
cd air-quality-analysis
pip install -r requirements.txt
```

## Run

```bash
python analysis.py
```

Outputs (plots + metrics) will be saved in the `outputs/` folder and displayed in console.

## Outputs

* `eda_distribution_pm25.png`
* `eda_correlation.png`
* `pca_scatter.png`
* `regression_true_vs_pred.png`
* `classification_confusion_matrix.png`
* `classification_roc_curve.png`

## References

* [WHO Air Quality Database](https://www.who.int/publications/m/item/who-ambient-air-quality-database-(update-jan-2024))

