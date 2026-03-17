# 🏠 Rental Price Prediction in Ho Chi Minh City

## 📌 Overview

This project aims to analyze and predict rental housing prices in **Ho Chi Minh City, Vietnam** using statistical methods and machine learning techniques.

With rapid urbanization and increasing housing demand, rental prices vary significantly across districts. This project provides a **data-driven approach** to understand key factors affecting rental prices and build predictive models.

---

## 🎯 Objectives

* Analyze factors affecting rental prices (area, district, etc.)
* Perform **descriptive and inferential statistics**
* Build a **regression model** for price prediction
* Provide insights into the housing market in HCMC

---

## 📊 Dataset

The dataset includes rental listings with the following features:

* `Price` (target variable)
* `Area` (m²)
* `District`
* `Address`
* `Published Date`
* `Title`

### ⚠️ Data Challenges

* Inconsistent formats (dates, area values)
* Presence of outliers
* Missing values
* Limited features (no amenities, rooms, etc.)

---

## 🔍 Methodology

### 1. Data Preprocessing

* Data cleaning (handling missing values, formatting)
* Removing outliers
* Feature selection

### 2. Exploratory Data Analysis (EDA)

* Bar charts (distribution across districts)
* Histograms (price distribution)
* Scatter plots (Area vs Price)

### 3. Statistical Analysis

* Confidence Intervals (95%)
* Hypothesis Testing (t-test, ANOVA)
* OLS Regression

### 4. Modeling

We used **Linear Regression with interaction terms**:

* Area effect varies by district
* District-specific price differences

Key model insight:

* Rental price increases with area
* Central districts (e.g., District 1, District 3) have higher prices

---

## 📈 Key Findings

* 📍 **Location matters**: Central districts have significantly higher prices
* 📏 **Area positively affects price**
* 📊 **Model is statistically significant** (F-test, p < 0.05)
* 🧠 Interaction effects improve model realism

---

## 🏗️ Project Structure

```
project/
├── config.py
├── data.py
├── model.py
├── train.py
├── predict.py
├── utils.py
├── main.py
├── notebook.ipynb
└── README.md
```

---

## 🚀 How to Run

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/rental-price-prediction.git
cd rental-price-prediction
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the project

```bash
python main.py
```

---

## 🧠 Model Example

The regression model:

> Price = 1.91 + 0.07 × Area

This shows:

* Each additional unit of area increases rental price
* However, the effect varies by district (interaction terms)

---

## ⚠️ Limitations

* Sensitive to outliers
* Limited dataset features
* Missing real-world factors (amenities, condition, location quality)

---

## 🔮 Future Improvements

* Add more features (rooms, facilities, location score)
* Use advanced models (Random Forest, XGBoost)
* Deploy as a web app
* Real-time data integration

---

## 👨‍💻 Authors

* Tran Quoc Bao
* Nguyen Hanh Dan
* Nguyen Thanh Phat
* Ho Chi Hieu
* Trinh Minh Tri

---

## 📚 References

* Linear Regression – Statistics by Jim
* Machine Learning Cơ Bản (Tiep Vu)

---

## ⭐ Final Note

This project demonstrates how **statistics and machine learning** can be applied to solve real-world problems in the real estate market.

---
