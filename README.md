#  Weather Prediction using Ridge and Lasso Regression

##  Project Overview

This project uses machine learning techniques to predict temperature based on weather conditions such as humidity, wind speed, precipitation, and city information.

Two regularization models are used:

* Ridge Regression (L2)
* Lasso Regression (L1)

The main goal is to compare their performance and understand feature importance.

---

## Dataset

* Weather dataset (CSV format)
* Features include:

  * Temperature (target)
  * Humidity
  * Wind Speed
  * Precipitation
  * City
  * Weather Condition

---

##  Workflow

1. Data Loading
2. Data Cleaning
3. Feature Encoding (One-Hot Encoding)
4. Train-Test Split
5. Feature Scaling
6. Model Training (Ridge & Lasso)
7. Model Evaluation (RMSE, R²)
8. Feature Importance Analysis

---

##  Models Used

### Ridge Regression

* Handles multicollinearity
* Keeps all features but shrinks coefficients

### Lasso Regression

* Performs feature selection
* Removes irrelevant features by setting coefficients to zero

---

##  Results

* Lasso removed multiple irrelevant features
* Important features:

  * Precipitation
  * Wind Speed
  * Certain Cities
* Humidity had minimal impact (coefficient ≈ 0)

---

##  Visualization

Feature importance was visualized using bar plots to compare the impact of each variable.

---

##  How to Run

### 1. Clone the repository

```bash
git clone https://github.com/your-username/weather-ridge-lasso.git
cd weather-ridge-lasso
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Run notebook

```bash
jupyter notebook
```

---

## 📦 Requirements

* pandas
* numpy
* matplotlib
* scikit-learn

---

##  Key Learnings

* Importance of feature scaling in regularization
* Difference between Ridge and Lasso
* Lasso as a feature selection method
* Real-world data preprocessing

---

##  Author

Your Name

---

## ⭐ If you like this project, give it a star!
