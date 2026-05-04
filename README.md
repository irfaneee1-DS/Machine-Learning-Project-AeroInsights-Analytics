# Flight Price Prediction using Machine Learning

## Project Overview

This project analyses flight booking data from EaseMyTrip to understand pricing behaviour and predict ticket prices using machine learning models.

The study explores key factors such as airline, travel class, booking time (days_left), duration, and stops, and evaluates their impact on ticket pricing.

---

## Dataset

* Source: EaseMyTrip flight dataset
* Records: ~300,000+ entries
* Features:

  * Airline
  * Source & Destination City
  * Class
  * Duration
  * Stops
  * Days Left (Booking Time)
  * Price (Target Variable)

---

## Methodology

* Data Cleaning & Preprocessing
* Exploratory Data Analysis (EDA)
* Hypothesis Testing (ANOVA)
* Feature Engineering & Encoding
* Train-Test Split (80/20)

---

## Models Used

* Ridge Regression
* Random Forest Regressor

---

## Model Evaluation

Models were evaluated using:

* R² Score
* RMSE
* RMSLE
* MAPE

Random Forest outperformed Ridge Regression by capturing non-linear relationships more effectively.

---

## 📊 Key Insights

* Airline and class significantly influence ticket prices
* Booking time (days_left) has a strong impact
* Prices increase as departure date approaches
* Business class tickets are significantly higher

---

## Business Implications

* Airlines can implement dynamic pricing strategies
* Travel platforms can provide price prediction alerts
* Customers can save money by booking earlier

---

## Repository Contents

* Dataset file
* Python code (analysis & models)
* Final report (PDF)

---

## Author

**Irfan Ali**
Machine Learning Project – Arden University
