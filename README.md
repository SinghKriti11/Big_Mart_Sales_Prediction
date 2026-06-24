# 🛒 Big Mart Sales Prediction

## 📌 Overview

This project predicts product sales at Big Mart outlets using machine learning. It analyzes historical sales data and builds predictive models to estimate future sales.,     

---

## 🎯 Problem Statement

Predict **Item_Outlet_Sales** using features like:  
* Item type 
* Visibility
* MRP 
* Outlet characteristics 

---

## 📊 Dataset

* Big Mart Sales Dataset
* Includes product-level and outlet-level information    

---

## ⚙️ Technologies Used

* Python
* Pandas, NumPy
* Matplotlib, Seaborn
* Scikit-learn

---

## 🔄 Workflow

### 1. Data Preprocessing 
* Missing values handled:

  * Item Weight → Mean
  * Outlet Size → Mode (based on Outlet Type)

### 2. Exploratory Data Analysis (EDA)
* Distribution analysis
* Feature relationships
* Outlier detection

### 3. Feature Engineering
* Extracted Item_Type from Item_Identifier
* Normalized Item Visibility
* Encoded categorical variables

### 4. Model Building
* Linear Regression
* Random Forest
* XGBoost (recommended)

### 5. Model Evaluation
* R² Score
* Mean Absolute Error (MAE)

---

## 📊 Model Performance

| Model             | R² Score | MAE |
| ----------------- | -------- | --- |
| Linear Regression | XX       | XX  |
| Random Forest     | XX       | XX  |

---

## 🔍 Key Insights

* Higher MRP products tend to generate more sales
* Certain outlet types significantly outperform others
* Visibility impacts sales but not linearly

---

## 💡 Key Learnings

* Data preprocessing techniques
* Feature engineering importance
* Model evaluation strategies





