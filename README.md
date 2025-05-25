# Churn2Price

Churn2Price is a machine learning-powered price prediction system designed for telecom and subscription-based businesses.  
It forecasts customer-specific pricing using behavioral, demographic, and service-related features that are commonly associated with churn.

The goal is to assist businesses in simulating or optimizing pricing strategies through data-driven insights.

---

## Overview

Churn2Price addresses the challenge of determining optimal price points tailored to individual customers.  
It leverages historical customer data, especially features correlated with churn, and applies a trained regression model to predict appropriate pricing for new users.

---

## Features

- Built on features known to influence customer churn such as tenure, contract type, payment method, and service usage.
- Predicts individualized prices using a trained linear regression model.
- Ensures input consistency through feature alignment and scaling.
- Handles user input securely to match the training-time feature structure.

---

## Included Files

| File Name                        | Description                                 |
|----------------------------------|---------------------------------------------|
| `price_lr_model.pkl`             | Trained price prediction model              |
| `scaler.pkl`                     | StandardScaler fitted on training data      |
| `feature_order.pkl`              | Ordered list of features from model training |
| `FIXED_PRICE_PREDICTION_NOTEBOOK.ipynb` | Jupyter notebook to run predictions        |

---

## Example Use Case

Telecom companies can input customer details such as:

- Tenure in months  
- Type of internet service  
- Subscription to streaming, security, or backup services  
- Billing and payment behavior  
- Contract duration and demographics  

The model then returns a price prediction aligned with past data and churn patterns.
