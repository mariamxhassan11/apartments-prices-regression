# Apartments Sale Price Regression

Real estate pricing model predicting residential apartment sale values across urban districts and finishing tiers.

## Project Structure

```text
08_Apartments_Prices_Regression/
├── apartments_prices_regression_data.csv
├── apartments_prices_regression_pipeline.ipynb
├── app.py
├── best_model.pkl
├── model_metadata.json
├── requirements.txt
└── README.md
```

## Dataset & Features

- **Dataset File:** `apartments_prices_regression_data.csv`
- **Task Type:** `Regression`
- **Target Variable:** `price_egp`
- **Numerical Features (4):** `area_sqm, bedrooms, bathrooms, floor`
- **Categorical Features (4):** `district, finishing, compound, payment_method`

## Model Evaluation Summary

- **Selected Best Model:** `Ridge`

| Metric | Score |
| :--- | :--- |
| `r2` | `0.9073` |
| `mae` | `482918.65` |
| `rmse` | `595868.93` |

## Quickstart & Deployment

1. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
2. Run the Streamlit web application:
   ```bash
   streamlit run app.py
   ```
