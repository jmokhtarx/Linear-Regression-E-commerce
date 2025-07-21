# 🛍️ E-commerce Customer Spending Prediction using Linear Regression

This project analyzes customer data from an e-commerce clothing store to **predict yearly customer spending** using a **Linear Regression** model. The goal is to help the company decide whether to improve the **mobile app experience** or the **website interface** to increase revenue.

---

## 📂 Dataset Overview

The dataset contains information about:

- Average Session Length
- Time on Website
- Time on App
- Length of Membership
- Yearly Amount Spent (Target)

These features are used to understand user behavior and predict spending patterns.

---

## 📊 Exploratory Data Analysis (EDA)

Visualizations were used to explore correlations between features and the target variable.

### 🔹 Pairplot of Key Features

*(Insert this plot here)*

### 🔹 Length of Membership vs Yearly Amount Spent

A strong positive correlation is observed between Length of Membership and Yearly Amount Spent.

*(Insert this scatter plot here)*

---

## 🧠 Model: Linear Regression

We trained a **multiple linear regression model** using the following equation:
Y = β₀ + β₁·Avg. Session Length + β₂·Time on App + β₃·Time on Website + β₄·Length of Membership

