# 📈 Stock Price Prediction using Regression Models

This quant finance project applies various regression models to predict Apple's (AAPL) stock price using historical price data and technical indicators.

---

## 🧠 Objective

- Predict AAPL stock prices using:
  - *OLS (Ordinary Least Squares)*
  - *Lasso Regression*
  - *Ridge Regression*
  - *ElasticNet Regression*
- Evaluate models based on accuracy and regression assumptions.
- Gain insight into real-world application of financial ML.

---

## 🧪 Techniques Used

- Feature Engineering:
  - Lag values (t-1)
  - 5-day Moving Averages
- Regression Model Building
- Statistical Assumption Testing:
  - Linearity
  - Homoscedasticity
  - Residual Normality
  - Multicollinearity (VIF)
  - Autocorrelation (Durbin-Watson)

---

## 📊 Performance Comparison

| Model       | R² Score | RMSE  |
|-------------|----------|-------|
| OLS         | 0.993    | 4.16  |
| Lasso       | 0.674    | 5.82  |
| Ridge       | 0.655    | 5.99  |
| ElasticNet  | 0.663    | 5.91  |

---

## 🛠 Tech Stack

- Python
- Jupyter Notebook
- yfinance
- scikit-learn
- statsmodels
- matplotlib, seaborn

---

## 📁 File Structure

- PROJECT1(QF).ipynb – Main notebook with all code, models, and visualizations

---

## ✅ Run It Yourself

1. Clone the repo:
   ```bash
   git clone https://github.com/abhinav3593/quanprojects.git
   cd quanprojects
