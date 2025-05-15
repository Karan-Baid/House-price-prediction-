# House-price-prediction

# 🌲 Random Forest Regressor with Hyperparameter Tuning and MLflow Tracking

This project demonstrates the use of **Random Forest Regression** along with **GridSearchCV** for hyperparameter tuning and **MLflow** for experiment tracking. It includes model training, evaluation, and logging using a local MLflow server.

## 🚀 Features

- Train a Random Forest Regressor on a dataset to predict a target (`Price`)
- Perform hyperparameter tuning using `GridSearchCV`
- Log experiments, parameters, metrics, and models using **MLflow**
- Supports model registration and artifact tracking
- Uses `infer_signature` for auto-detection of input/output schema

## 🛠️ Tech Stack

- Python
- Scikit-learn
- MLflow
- Pandas, NumPy
- RandomForestRegressor
- GridSearchCV

## 📦 Installation

```bash
git clone https://github.com/your-username/rf-mlflow-regression.git
cd rf-mlflow-regression
pip install -r requirements.txt

🧠 Workflow

    Load and split the dataset into features and target.

    Define a hyperparameter grid for Random Forest.

    Use GridSearchCV to find the best combination of parameters.

    Log metrics, parameters, and models using MLflow.

    Register the model or save with infer_signature.

📈 Example Metrics Logged

    Best Hyperparameters:

        n_estimators

        max_depth

        min_samples_split

        min_samples_leaf

    Evaluation Metric:

        Mean Squared Error (MSE)
