# Funnel Analysis User Behaviors & Conversion Prediction
User Behavior Funnel Analysis using Python

## 📌 Project Overview

This project analyzes the **User Behaviors journey funnel** from sign-up to paid subscription and identifies key drop-off points. Additionally, a Machine Learning model is built to **predict whether a user will convert into a paid customer**.

---

## 🎯 Business Problem

A large number of users sign up for the free trial, but only a small percentage convert to paid subscriptions.

👉 Goal: Identify bottlenecks and improve conversion rate.

---

## 📂 Dataset

* Features include:

  * Session ID
  * User ID
  * Timestamp
  * Page Type
  * Device Type
  * Country
  * Referral Source
  * TimeOnePae_seconds
  * Item in Cart
  * Purchased
    

---

## 🛠️ Tech Stack

* Python
* Pandas, NumPy
* Matplotlib, Seaborn
* plotly
* Jupyter Notebook

---

## 📊 Exploratory Data Analysis (EDA)

* Analyzed user demographics and behavior
* Identified patterns in spending and engagement
* Visualized funnel stages and drop-offs

---

## 📉 Funnel Analysis

Key stages:

1. Sign up
2. Free Trial
3. Active Usage
4. Paid Conversion

📌 **Insight:** Major drop-off occurs at the Free Trial → Paid stage.

---

## 🤖 Machine Learning Model

### Model Used:

* RandomForestClassifier 

### Objective:

Predict whether a user will convert (1) or not (0)

### Features Used:

* Age
* Total Spend
* Engagement Metrics
* Membership Type

---

## 📈 Model Performance

* Accuracy: 60%
* Precision: 60%

---

## 🔍 Key Insights

* High engagement users are more likely to convert
* Users with higher spending show better retention
* Certain membership types have higher conversion rates

---

## 💡 Business Recommendations

* Improve onboarding experience during free trial
* Provide personalized offers to high-engagement users
* Target specific cities with high conversion potential

---

## 📊 Visualizations

<img width="1559" height="411" alt="image" src="https://github.com/user-attachments/assets/523c8687-1c0e-4b1e-abdd-c745cc726aa1" />


---

## 🚀 Future Improvements

* Use advanced models (Random Forest, XGBoost)
* Deploy model using Flask
* Build a dashboard using Power BI

---

## 👨‍💻 Author

Vipul Khadgi
