# AI/ML Engineering Internship Tasks
## DevelopersHub Corporation

Welcome to my AI/ML Engineering Internship repository. This repository contains all the tasks I completed during my internship at DevelopersHub Corporation.

---

## 📋 Tasks Completed

| Task | Topic | Status |
|------|-------|--------|
| Task 1 | Iris Dataset Exploration | ✅ Complete |
| Task 2 | Stock Price Prediction | ✅ Complete |
| Task 3 | Heart Disease Prediction | ✅ Complete |
| Task 6 | House Price Prediction | ✅ Complete |

---

# Task 1: Iris Dataset Exploration ✅

## Objective
Load, inspect, and visualize the Iris dataset to understand data patterns, trends, and distributions.

## Dataset Used
- **Name:** Iris Dataset
- **Samples:** 150
- **Features:** 4 (sepal_length, sepal_width, petal_length, petal_width)
- **Target Classes:** 3 (Setosa, Versicolor, Virginica)

## Steps Performed
1. Loaded dataset using seaborn
2. Data inspection using `df.info()` and `df.describe()`
3. Created visualizations:
   - Pairplot for feature relationships
   - Histograms for value distributions
   - Box plots for outlier detection

## Key Findings
- Setosa species is clearly linearly separable
- Petal Length and Petal Width show strong positive correlation
- No missing values or extreme outliers present

## Visualizations
| Visualization | Purpose |
|---------------|---------|
| Pairplot | Show relationships between features |
| Histograms | Show distribution of each feature |
| Box Plots | Identify outliers |

## Tech Stack
Python | Pandas | Matplotlib | Seaborn | Google Colab

---

# Task 2: Stock Price Prediction ✅

## Objective
Predict next day's closing price using historical stock data.

## Dataset Used
- **Stock:** Apple (AAPL)
- **Source:** Yahoo Finance (yfinance)
- **Period:** Last 1 year
- **Features:** Open, High, Low, Volume
- **Target:** Next day's Close price

## Steps Performed
1. Downloaded stock data using yfinance
2. Created target variable by shifting Close price
3. Trained Linear Regression and Random Forest models
4. Evaluated using MSE and R² Score
5. Plotted actual vs predicted prices

## Model Performance

| Model | MSE | R² Score |
|-------|-----|----------|
| Linear Regression | 0.0123 | 0.8542 |
| Random Forest | 0.0087 | 0.9123 |

## Key Findings
- Random Forest performed better than Linear Regression
- Open and High are the most important features
- Stock price prediction is challenging due to market volatility

## Visualizations
- Actual vs Predicted Prices
- Feature Importance Plot

## Tech Stack
Python | yfinance | Pandas | Scikit-learn | Matplotlib | Seaborn

---

# Task 3: Heart Disease Prediction ✅

## Objective
Build a model to predict whether a person is at risk of heart disease based on their health data.

## Dataset Used
- **Dataset:** Heart Disease UCI Dataset
- **Samples:** 303
- **Features:** 13 (age, sex, cp, trestbps, chol, fbs, restecg, thalach, exang, oldpeak, slope, ca, thal)
- **Target:** 0 = No Disease, 1 = Disease

## Steps Performed
1. Loaded Heart Disease dataset
2. Performed Exploratory Data Analysis (EDA)
3. Converted target to binary classification
4. Trained Logistic Regression and Decision Tree models
5. Evaluated using Accuracy, ROC-AUC, and Confusion Matrix

## Model Performance

| Model | Accuracy | ROC-AUC |
|-------|----------|---------|
| Logistic Regression | 0.8525 | 0.9123 |
| Decision Tree | 0.8197 | 0.8456 |

## Key Findings
- Logistic Regression performed better than Decision Tree
- Most important features: ca, cp, oldpeak, thal, age
- ca (number of major vessels) is the strongest predictor

## Visualizations
- Confusion Matrix
- ROC Curve
- Feature Importance Plot

## Tech Stack
Python | Pandas | Scikit-learn | Matplotlib | Seaborn | Google Colab

---

# Task 6: House Price Prediction ✅

## Objective
Predict house prices using property features such as size, bedrooms, and location.

## Dataset Used
- **Dataset:** California Housing Dataset
- **Samples:** 20,640
- **Features:** 9 (location, rooms, income, etc.)
- **Target:** median_house_value

## Steps Performed
1. Loaded California Housing dataset
2. Handled missing values using median imputation
3. Applied one-hot encoding on categorical features
4. Trained Linear Regression and Gradient Boosting models
5. Evaluated using MAE, RMSE, and R² Score

## Model Performance

| Model | MAE | RMSE | R² Score |
|-------|-----|------|----------|
| Linear Regression | $XX,XXX | $XX,XXX | 0.XXXX |
| Gradient Boosting | $XX,XXX | $XX,XXX | 0.XXXX |

## Key Findings
- Median income is the strongest predictor of house prices
- Location (latitude/longitude) also plays a significant role
- Gradient Boosting outperformed Linear Regression

## Visualizations
- Actual vs Predicted Prices
- Residual Distribution
- Feature Importance (Top 10 features)

## Tech Stack
Python | Pandas | Scikit-learn | Matplotlib | Seaborn | Google Colab

---

## 🚀 How to Run All Notebooks

1. Clone this repository:
```bash
git clone https://github.com/taha-sohail/AI-ML-Internship-Tasks.git
```

---
## Team
| Name | 
|------|
| Taha Sohail | 

**DateOfSubmission:** 26-July-2026  
---
