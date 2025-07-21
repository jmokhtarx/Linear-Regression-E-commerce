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


Where:
- `Y`: Predicted Yearly Amount Spent  
- `β₀` to `β₄`: Model coefficients

### 📌 Learned Coefficients

| Feature               | Coefficient |
|-----------------------|-------------|
| Avg. Session Length   | 25.72       |
| Time on App           | 38.60       |
| Time on Website       | 0.46        |
| Length of Membership  | 61.67       |

The **Length of Membership** and **Time on App** have the highest influence on spending.

---

## 📈 Model Evaluation

| Metric         | Value       |
|----------------|-------------|
| MAE            | 8.426091641 |
| MSE            | 103.9155413 |
| RMSE           | 10.19389726 |

### 🔹 Predicted vs Actual Plot

<img width="565" height="454" alt="image" src="https://github.com/user-attachments/assets/40bf6c8f-ef5a-468e-bbda-f1a8a766bd96" />


Residuals are roughly normally distributed, indicating a good fit.

---

## 💡 Insights

- **Length of Membership** is the strongest predictor of customer spending.
- **Time on App** is more influential than **Time on Website**.
- The company should consider investing more in **improving the mobile app experience** rather than the website.

---

## 🧰 Tools & Libraries

- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Scikit-learn



