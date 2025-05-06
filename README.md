
## Notebooks Overview

1. **01_detailed_eda.ipynb**: In-depth exploratory data analysis to understand the dataset.
2. **02_preprocessing.ipynb**: Data cleaning, feature engineering, and preparation for modeling.
3. **03_baseline_models.ipynb**: Implementation of baseline models like Logistic Regression and Decision Trees.
4. **04_advanced_models.ipynb**: Advanced models including XGBoost, LightGBM, and ensemble methods.
5. **05_hyperparameter_tuning.ipynb**: Hyperparameter optimization using techniques like grid search and random search.
6. **06_business_impact_roi.ipynb**: Analysis of the business impact and return on investment (ROI) of the models.
7. **07_Class_Imbalance_Mitigation.ipynb**: Techniques to handle class imbalance in the dataset.

## Data

The dataset is located in the `data/` directory and includes:
- `bank.csv`: The original dataset.
- `X_train.csv`, `X_test.csv`: Training and testing features.
- `y_train.csv`, `y_test.csv`: Training and testing labels.

## Models

The `models/` directory contains saved models, including:
- `best_xgb_model.pkl`: The best-performing XGBoost model.

## Results

The `results/plots/` directory contains visualizations and plots generated during the analysis.

## Requirements

To install the required Python dependencies, run:

```bash
pip install -r requirements.txt
