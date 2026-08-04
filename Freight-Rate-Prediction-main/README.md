# Freight-Rate-Prediction
Freight Rate Prediction using XGBoost with feature engineering, validation prediction, and December forecasting for the Spotter ML Engineer Assessment.
#  Freight Rate Prediction using XGBoost

##  Project Overview

This project predicts freight rates using historical shipment data for the Spotter Machine Learning Engineer Assessment.

The solution includes:

- Data Exploration
- Data Cleaning
- Feature Engineering
- XGBoost Regression Model
- Validation Prediction
- December Rate Prediction
- Score Validation

---

##  Dataset

- train-test.csv
- validation.csv
- december-chart-inputs.csv

---

##  Machine Learning Workflow

1. Import Libraries
2. Load Dataset
3. Exploratory Data Analysis
4. Data Cleaning
5. Feature Engineering
6. Categorical Encoding
7. Train/Test Split
8. XGBoost Model Training
9. Model Evaluation
10. Validation Prediction
11. December Prediction
12. Score Validation

---

##  Model

XGBoost Regressor

---

##  Evaluation

MAE : 144.36

RMSE : 554.54

R² Score : 0.8562

---

##  Run

Install dependencies

```bash
pip install -r requirements.txt
```

Run the notebook.

Generate

- validation_predictions.csv
- december_predictions.csv

Run scorer

```bash
python score.py --predictions validation_predictions.csv --december-predictions december_predictions.csv
```

---

##  Output

- validation_predictions.csv
- december_predictions.csv
- scorer_results/candidate_december.png
