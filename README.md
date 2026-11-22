# MLOps Zoomcamp: Coursework

My notebooks and homework for the [DataTalksClub MLOps Zoomcamp](https://github.com/DataTalksClub/mlops-zoomcamp).
The running example is a model that estimates NYC green taxi rides from the TLC trip record data.

| Module | Contents |
|---|---|
| [`01-intro`](01-intro) | Data exploration, feature engineering and a baseline regression model |
| [`02-experiment-tracking`](02-experiment-tracking) | Experiment tracking and model registry with MLflow, hyperparameter tuning with Hyperopt and XGBoost |

## Running locally

```bash
cd 02-experiment-tracking
pip install -r requirements.txt
mlflow ui --backend-store-uri sqlite:///mlflow.db   # optional: tracking UI on http://127.0.0.1:5000
jupyter notebook
```
