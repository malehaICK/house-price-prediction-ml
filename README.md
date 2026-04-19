# Housing Price Estimation using Machine Learning

## Overview

This project focuses on predicting housing prices using supervised learning models based on property characteristics such as size, condition, and structural attributes. The goal is to build a reliable system that helps buyers, sellers, and investors make informed decisions.

---

## Project Workflow

```mermaid
flowchart LR
A[Load Dataset] --> B[Data Cleaning & Preprocessing]
B --> C[Feature Engineering & Selection]
C --> D[Train Models]
D --> E[Evaluate Performance]
E --> F[Compare Results]
```

---

## Key Features

* Data preprocessing (missing values, encoding, scaling)
* Feature engineering (HouseAge, RemodelAge, LotAreaPerRoom)
* Multiple model training and comparison
* Performance evaluation using standard regression metrics
* Interactive dashboard for predictions

---

## Models Used

* Linear Regression
* Decision Tree Regressor
* XGBoost Regressor
* Ensemble (Stacking Model)

---

## Evaluation Metrics

* RMSE (Root Mean Squared Error)
* MAE (Mean Absolute Error)
* R² Score (Model Accuracy)
* MAPE (Mean Absolute Percentage Error)

---

## Results

| Model             | RMSE     | MAE      | R² Score |
| ----------------- | -------- | -------- | -------- |
| Linear Regression | 30580.89 | 15701.19 | 0.8781   |
| Decision Tree     | 13426.56 | 1518.85  | 0.9765   |
| XGBoost           | 6509.66  | 2083.93  | 0.9945   |
| Ensemble Model    | 7007.30  | 1202.48  | 0.9936   |

---

## Performance Insights

* XGBoost achieved the highest accuracy (R² = 0.9945)
* Ensemble model produced the lowest MAE (best consistency)
* Linear Regression struggled with non-linear relationships
* Feature engineering significantly improved performance

---

## Why This Matters

* Helps buyers avoid overpaying
* Helps sellers price competitively
* Supports real estate decision-making
* Useful for banks and investors

---

## Dashboard (Interactive)

The project includes a web-based dashboard where users can:

* Input property features
* Get predicted house prices
* Compare model performance visually

---

## Tech Stack

* Python
* Scikit-learn
* XGBoost
* Pandas, NumPy
* Matplotlib
* HTML, CSS, JavaScript (Dashboard)

---

## Challenges

* Handling missing and inconsistent data
* Feature selection and multicollinearity
* Model overfitting and generalization
* Computational cost for advanced models

---

## Future Improvements

* Add location-based features
* Integrate real-time market data
* Deploy backend model (Flask / FastAPI)
* Improve UI for production-level dashboard



## Conclusion

Machine learning provides a powerful solution for housing price prediction. Among all models, XGBoost and Ensemble methods demonstrated the highest performance, making them suitable for real-world deployment.




