# 🏡 Advanced House Price Prediction using Robust Regression Engine

<p align="center">

![Python](https://img.shields.io/badge/Python-3.10-blue?style=for-the-badge&logo=python)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange?style=for-the-badge&logo=scikit-learn)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-purple?style=for-the-badge&logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Scientific%20Computing-blue?style=for-the-badge&logo=numpy)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-green?style=for-the-badge)

</p>

## 📌 Project Overview

This project builds an **Advanced House Price Prediction System** using multiple Machine Learning regression algorithms. It compares various models and selects the best performer using **R² Score, MAE, RMSE, and Cross Validation**.

## 🎯 Objectives

- Predict house prices accurately
- Compare regression models
- Reduce overfitting using regularization
- Select the best model

## 🗂 Dataset

- **Rows:** 3800
- **Target:** `house_price_inr`

Main features:

- Area (sqft)
- Bedrooms
- Bathrooms
- Location Score
- Property Age
- Distance to City
- Near School
- Near Metro
- Crime Rate Index

## 🤖 Models Used

- Linear Regression
- Ridge Regression
- Lasso Regression
- Support Vector Regression (Linear, Polynomial, RBF)
- Decision Tree Regressor
- Random Forest Regressor

## 📊 Evaluation Metrics

- R² Score
- MAE
- RMSE
- MSE
- K-Fold Cross Validation
- Stratified K-Fold
- Time Series Split
- LOOCV

# 📸 Screenshots

## Dataset Overview

![](./screenshots/Data.png)

## Model Comparison

![](./screenshots/model_comparison.png)

## Ridge vs Lasso

![](./screenshots/ridge_vs_lasso.png)


## Decision Tree vs Random Forest

![](./screenshots/Tree.png)

## Cross Validation

![](./screenshots/cv_comparison.png)

## Summery

![](./Summary.png)

## 🏆 Best Model

| Model | R² |
|------|------:|
| Decision Tree | 0.8991 |
| ⭐ Random Forest | **0.9133** |

## 📂 Project Structure

```text
Advanced-House-Price-Prediction/
│
├── Adv_Regression_HousePrice.csv
├── robust_regression_engine.ipynb
├── README.md
└── screenshots/
```

## ▶ Run

```bash
pip install -r requirements.txt
jupyter notebook
```

Open `robust_regression_engine.ipynb` and run all cells.

## 📦 Requirements

- numpy
- pandas
- matplotlib
- scikit-learn
- jupyter

## 👨‍💻 Author

**Badshaa**  
Engineering Student | Machine Learning Enthusiast

---

⭐ If you like this project, don't forget to star the repository!
