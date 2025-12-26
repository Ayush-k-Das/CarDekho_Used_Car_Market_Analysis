---

# 🚗 CarDekho Used Car Market Analysis Dashboard

## 📌 Project Overview

This project focuses on **exploratory data analysis (EDA), dashboarding, and machine learning–based price prediction** using a used car dataset sourced from the **CarDekho platform**.
The goal is to extract meaningful market insights, visualize trends in Excel, and build a regression model to predict car selling prices.

---

## 📂 Dataset Information

* **Source:** CarDekho (public dataset)
* **Records:** 4,340 used cars
* **Features:**

  * name
  * year
  * selling_price
  * km_driven
  * fuel
  * seller_type
  * transmission
  * owner
  * brand (derived from name)

---

## 🔍 Exploratory Data Analysis (EDA)

Performed in **Jupyter Notebook** using Python.

### Key EDA Steps:

* Data cleaning and type conversion
* Brand extraction from car name
* Univariate and bivariate analysis
* Outlier detection and treatment
* Distribution analysis of price and mileage
* Trend analysis by year, fuel type, seller type, and transmission

### Libraries Used:

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn

---

## 📊 Excel Dashboard

An **interactive Excel dashboard** was created to visualize market insights clearly and effectively.

### Dashboard Highlights:

* **KPIs**

  * Average Selling Price
  * Most Common Brand Sold
  * Most Common Fuel Type
* **Charts**

  * Average Price by Fuel Type
  * Average Price by Seller Type
  * Average Price by Transmission Type
  * Top 10 Brands by Average Selling Price
  * Year vs Average Selling Price
  * KM Driven by Seller Type
* **Slicers**

  * Fuel Type
  * Seller Type
  * Transmission Type

---

## 🤖 Machine Learning Model

A regression model was built to **predict car selling price**.

### Models Tried:

* Linear Regression
* Ridge Regression
* Lasso Regression
* **Random Forest Regressor (Best Performing)**

### Best Model Performance:

* **Model:** Random Forest Regressor
* **R² Score:** ~0.71
* **Mean Squared Error:** ~2.15 × 10¹⁰

### Techniques Applied:

* One-Hot Encoding for categorical variables
* Feature alignment to avoid prediction mismatches
* Train-test split
* Model comparison and evaluation

---

## 🛠️ Tools & Technologies

* **Python**
* **Jupyter Notebook**
* **Excel (Dashboard & Visualization)**
* **Scikit-learn**
* **Pandas, NumPy**
* **Matplotlib, Seaborn**

---

## 📈 Key Insights

* Diesel cars have a higher average selling price than petrol cars.
* Automatic transmission vehicles are priced significantly higher.
* Car prices show a strong upward trend for newer manufacturing years.
* Brand plays a major role in determining resale value.
* Random Forest captures non-linear pricing patterns better than linear models.

---

## 📌 Project Use Cases

* Used car price prediction
* Market trend analysis for dealerships
* Buyer decision support
* Data analytics and ML portfolio project

---
---

## 👤 Author

**Ayush Das**
Computer Science Undergraduate
Data Analytics & Machine Learning Enthusiast

---
