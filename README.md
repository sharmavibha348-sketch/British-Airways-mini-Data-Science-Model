# ✈️ British Airways Customer Booking Prediction

## 📌 Project Overview

This project was completed as part of the **British Airways Data Science Virtual Experience Program (Forage)**.

The objective is to build a machine learning model that predicts whether a customer will complete a flight booking based on historical booking information. The project includes data exploration, preprocessing, model development, evaluation, and interpretation of feature importance to generate actionable business insights.

---

## 🎯 Business Objective

British Airways aims to proactively identify customers who are likely to complete a booking before they travel. By leveraging historical booking data and predictive analytics, the airline can better target marketing campaigns and improve customer conversion rates.

The goal of this project is to:

- Explore customer booking behavior
- Build a predictive machine learning model
- Evaluate model performance
- Identify the most influential booking features

---

## 📂 Dataset

The dataset contains **50,000 customer booking records** with **14 features**, including:

- Number of passengers
- Sales channel
- Trip type
- Purchase lead
- Length of stay
- Flight hour
- Flight day
- Route
- Booking origin
- Extra baggage preference
- Preferred seat selection
- In-flight meal preference
- Flight duration

**Target Variable**

- `booking_complete`
  - 0 = Booking not completed
  - 1 = Booking completed

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

## 📊 Exploratory Data Analysis

The analysis included:

- Dataset overview
- Missing value analysis
- Statistical summary
- Booking completion distribution
- Purchase lead distribution
- Flight hour distribution
- Sales channel analysis
- Trip type analysis
- Top booking origins

Key observations:

- No missing values were present.
- Approximately 15% of customers completed their booking.
- Most bookings were made through the Internet.
- Round-trip bookings dominated the dataset.
- Australia contributed the highest number of bookings.

---

## 🤖 Machine Learning Model

A **Random Forest Classifier** was used to predict booking completion.

### Workflow

- Data preprocessing
- One-hot encoding of categorical variables
- Train-test split (80:20)
- Random Forest model training
- 5-fold Cross Validation
- Model evaluation
- Feature importance analysis

---

## 📈 Model Performance

### Test Accuracy

**85%**

### Cross Validation Accuracy

**73.56% (Average)**

### Classification Metrics

- Precision
- Recall
- F1-score
- Confusion Matrix

The model performed well in identifying customers who did not complete bookings but showed lower recall for completed bookings due to class imbalance.

---

## 🔍 Top Predictive Features

The most influential variables were:

1. Purchase Lead
2. Flight Hour
3. Length of Stay
4. Number of Passengers
5. Flight Duration
6. Booking Origin (Malaysia)
7. Wants In-Flight Meals
8. Booking Origin (Australia)
9. Wants Preferred Seat
10. Wants Extra Baggage

---

## 💼 Business Insights

- Purchase lead is the strongest predictor of booking completion.
- Flight timing and trip duration significantly influence customer booking behavior.
- Customer preferences such as baggage, meals, and seat selection also contribute to booking likelihood.
- Geographic booking origin impacts booking completion rates.

These insights can help British Airways improve customer targeting and optimize marketing campaigns.

---

## 🚀 Future Improvements

- Handle class imbalance using SMOTE or class weighting.
- Tune Random Forest hyperparameters.
- Compare additional models such as XGBoost, LightGBM, and Logistic Regression.
- Perform feature engineering for improved predictive performance.

## 📚 Skills Demonstrated

- Exploratory Data Analysis (EDA)
- Data Cleaning
- Feature Engineering
- Machine Learning
- Random Forest Classification
- Model Evaluation
- Cross Validation
- Feature Importance Analysis
- Business Insight Generation

---

## 🙏 Acknowledgement

This project was completed as part of the **British Airways Data Science Virtual Experience Program** hosted on **Forage**.
