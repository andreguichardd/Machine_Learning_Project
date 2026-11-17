# Insurance Customer Classification — Machine Learning

**Group project for the Executive Master in Big Data Science (Universidad de Navarra), Machine Learning module.**
Team: Federico Vargas, André Guichard, Exequiel, Jesús López, Marco Raudales.

---

## Problem

Insurance companies want to offer personalised products and premiums. The goal was to classify customers into product categories from their health-related and demographic attributes, so the insurer can tailor its offer to each profile.

---

## Approach

1. **Data cleaning** — missing values, types and outliers (PySpark + Pandas).
2. **Statistical analysis** — exploratory analysis (Sweetviz) and identification of non-significant variables.
3. **Feature engineering** — dropping weak variables, one-hot encoding of categoricals, scaling.
4. **Modelling** — multi-output classification with **Random Forest** and **XGBoost**.
5. **Evaluation** — accuracy, precision, recall, F1 and confusion matrices.

---

## Tech Stack

```
Python    Pandas · NumPy · PySpark · Scikit-learn · XGBoost · Sweetviz · Matplotlib · Seaborn · Plotly
```

---

## How to Run

```bash
pip install pandas numpy pyspark scikit-learn xgboost sweetviz matplotlib seaborn plotly
jupyter notebook Andre.ipynb
```

The dataset is not included in the repository.

---

## Project Structure

```
├── Andre.ipynb   # Cleaning, statistical analysis, feature engineering and modelling
└── README.md
```
