# 🛍️ Personalized Product Recommendation System for User Needs and Budget

This project presents a machine learning-based web platform designed to recommend the most suitable products to users based on their preferences and **budget constraints**. The system mimics a smart personal shopping assistant where users can input a query like _“I need a table under ₹5000”_ and receive intelligent, ranked product suggestions.

---

## 🚀 Project Overview

- 📊 Created a synthetic dataset of 10,000+ user-product interactions
- 🧠 Applied regression-based machine learning models to predict **Affinity Score**
- 🛠️ Built with Python, scikit-learn, XGBoost, and visualized using Seaborn & Matplotlib
- 🧪 Evaluated using R², MSE, RMSE and validated with k-fold cross-validation
- 🌐 Web-ready logic for integration with e-commerce frontend (future scope)

---

## 📁 Dataset Features

The dataset includes a mix of user demographics, product metadata, and behavioral features:

| Feature              | Description                                          |
|----------------------|------------------------------------------------------|
| Age                  | User's age in years                                  |
| Income               | Annual income (in INR)                               |
| Brand Loyalty        | Likelihood of sticking to a specific brand (0-1)     |
| Discount Sensitivity | Likelihood of responding to product discounts (0-1)  |
| Product Views        | No. of times the product is viewed                   |
| Cart Additions       | No. of times added to cart                           |
| Time on Site         | Session time in seconds                              |
| Product Rating       | Avg. rating (1 to 5 scale)                           |
| Review Count         | Number of user reviews                               |
| Product Price        | Price of the product                                 |
| Affinity Score       | Target variable: suitability (0-1)                   |

---

## 🔍 Machine Learning Pipeline

### ✅ Data Preprocessing
- Missing value imputation
- Outlier removal using IQR/Z-score
- Feature scaling (MinMax)
- Label encoding for categorical data

### 📊 Exploratory Data Analysis
- Univariate, Bivariate, and Multivariate Analysis
- Correlation heatmaps, histograms, and pair plots

### 📉 Dimensionality Reduction
- Principal Component Analysis (PCA) to reduce noise and complexity

### 🧠 ML Models Used
- Linear Regression
- Ridge & Lasso Regression
- Random Forest Regressor
- XGBoost Regressor

### 📈 Model Evaluation
- R² Score, MSE, RMSE
- Feature importance visualization
- Gradient descent visualization (for educational purposes)
- 5-Fold Cross Validation

---

## 📊 Sample Results

| Model               | R² Score | RMSE  |
|--------------------|----------|-------|
| Linear Regression  | 0.865    | 0.11  |
| Ridge Regression   | 0.865    | 0.11  |
| Lasso Regression   | 0.863    | 0.11  |
| Random Forest      | 0.887    | 0.10  |
| XGBoost Regressor  | 0.880    | 0.10  |

🎯 **Random Forest** and **XGBoost** achieved the highest accuracy and generalization.

---

## 📂 Project Structure

