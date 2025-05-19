# Credit-risk-analysis

# Credit Risk Analysis Project

A machine learning model to predict loan default risk using financial data.

## Features
- **Exploratory Data Analysis (EDA)** for loan data.
- **Random Forest Classifier** (85% accuracy).
- **Risk Prediction Script** for new applicants.

## Installation
```bash
git clone https://github.com/your-username/credit-risk-analysis.git
pip install -r requirements.txt
```

## Usage
1. Train the model:
   ```bash
   python scripts/train_model.py
   ```
2. Predict risk:
   ```bash
   python scripts/predict_risk.py
   ```

## Results
| Model               | Accuracy | Precision | Recall |
|---------------------|----------|-----------|--------|
| Random Forest       | 0.85     | 0.83      | 0.82   |
| Logistic Regression | 0.78     | 0.75      | 0.74   |

## Future Improvements
- Deploy as a Flask API.
- Add SHAP for explainability.
- Use XGBoost for better performance.
