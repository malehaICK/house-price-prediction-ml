<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,100:1e293b&height=200&section=header&text=Housing%20Price%20Prediction&fontSize=35&fontColor=ffffff" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/R²%20Score-0.9945-brightgreen?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Best%20Model-XGBoost-red?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Status-Completed-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Type-Regression-orange?style=for-the-badge" />
</p>

<p align="center">
A machine learning system for accurate housing price prediction using advanced regression models
</p>

---

## Overview

This project predicts housing prices using supervised machine learning models based on structural and property-related features.

It provides a data-driven solution to support decision-making for buyers, sellers, and investors.

---

## Project Workflow

<p align="center">
Load Dataset → Clean Data → Feature Engineering → Train Models → Evaluate → Compare
</p>

---

## Key Features

* Data preprocessing (missing values, encoding, scaling)
* Feature engineering (HouseAge, RemodelAge, LotAreaPerRoom)
* Multiple model training and comparison
* Evaluation using standard regression metrics
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
* R² Score (model performance indicator)
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

* XGBoost achieved the highest performance (R² = 0.9945)
* Ensemble model produced the lowest MAE (most consistent predictions)
* Linear Regression struggled with non-linear relationships
* Feature engineering significantly improved results

---

## Why This Matters

* Helps buyers avoid overpaying
* Helps sellers price competitively
* Supports real estate decision-making
* Useful for financial institutions and investors

---

## Dashboard (Interactive)

The project includes a web-based dashboard where users can:

* Input property features
* Get predicted house prices
* Compare model performance visually

---

## Tools & Technologies

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" />
  <img src="https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" />
  <img src="https://img.shields.io/badge/XGBoost-AA0000?style=for-the-badge&logo=xgboost&logoColor=white" />
  <img src="https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Seaborn-4C72B0?style=for-the-badge" />
  <img src="https://img.shields.io/badge/HTML-FF6F00?style=for-the-badge&logo=html5&logoColor=white" />
  <img src="https://img.shields.io/badge/CSS-264DE4?style=for-the-badge&logo=css3&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
</p>

---

## Challenges

* Handling missing and inconsistent data
* Feature selection and multicollinearity
* Model overfitting and generalization
* Computational cost of advanced models

---

## Future Improvements

<p align="center">
[ Location Features ] → [ Real-Time Data ] → [ Backend API ] → [ Production Dashboard ]
</p>

---

## Conclusion

Machine learning provides a powerful solution for housing price prediction.
XGBoost and Ensemble methods demonstrated the strongest performance and are suitable for real-world applications.


## Repository Structure

```text
house-price-prediction-ml/
├── notebooks/
│   └── Final_code.ipynb       # cleaning, feature engineering, training, evaluation
├── data/
│   └── HousePricePrediction(Sheet1).csv   # housing dataset
├── dashboard/
│   └── index.html             # interactive prediction dashboard
├── Housing price estimation using supervised learning_B.pdf   # written report
├── LICENSE
└── README.md
```

## Tools and Technologies

Python, Jupyter Notebook, pandas, NumPy, scikit-learn, XGBoost, HTML/CSS/JavaScript (dashboard).

## How to Run

Step 1. Clone the repository:

```bash
git clone https://github.com/malehaICK/house-price-prediction-ml.git
cd house-price-prediction-ml
```

Step 2. Install the dependencies:

```bash
pip install pandas numpy scikit-learn xgboost matplotlib jupyter
```

Step 3. Open the notebook:

```bash
jupyter notebook notebooks/Final_code.ipynb
```

The notebook was written in Google Colab and reads the dataset from `/content/HousePricePrediction(Sheet1).csv`. To run it locally, change the `file_name` line in the data loading cell to `../data/HousePricePrediction(Sheet1).csv`. In Colab, upload the CSV from the `data/` folder to `/content/`.

Step 4. To view the dashboard, open `dashboard/index.html` in a web browser.

## Report

The full write-up, covering methodology, evaluation and results, is in `Housing price estimation using supervised learning_B.pdf`.

## Author

Maleha Israt Chowdhury. [Portfolio](https://malehaisratchowdhury.netlify.app/)

## License

Released under the MIT License. See the `LICENSE` file.
