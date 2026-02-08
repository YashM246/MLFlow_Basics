# MLFlow Basics

A learning repository for exploring [MLFlow](https://mlflow.org/) — an open-source platform for managing the end-to-end machine learning lifecycle.

## Topics Covered

The [Learning_Notebook.ipynb](Learning_Notebook.ipynb) walks through:

1. **Binary Classification** — Creating an imbalanced dataset with scikit-learn and training multiple models (Logistic Regression, Random Forest, XGBoost)
2. **Handling Class Imbalance** — Using SMOTETomek to resample training data
3. **Experiment Tracking** — Logging parameters, metrics (accuracy, recall, F1), and model artifacts to MLFlow
4. **Comparing Models** — Tracking multiple runs within a single MLFlow experiment
5. **Model Registry** — Registering a chosen model and loading it back for inference

## Libraries Used

- scikit-learn
- xgboost
- imbalanced-learn
- mlflow
- numpy

## Setup

```bash
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
```

## Running the MLFlow UI

```bash
mlflow ui --workers 1
```

Then open http://127.0.0.1:5000 in your browser.