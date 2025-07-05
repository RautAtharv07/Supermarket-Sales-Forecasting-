# 🛒 Supermarket Daily Revenue Prediction

A regression-based machine learning project to forecast **daily revenue** for a supermarket chain using transaction-level sales data from the [Kaggle Supermarket Sales Dataset](https://www.kaggle.com/datasets/aungpyaeap/supermarket-sales).

## 📌 Problem Statement

Retail businesses often struggle to anticipate their daily revenue, leading to overstocking, understaffing, or missed opportunities. This project builds a predictive model that can help supermarket managers forecast **total daily revenue** using sales features like product line, payment method, and customer type.

---

## 🧠 Project Highlights

- 🧹 Preprocessed and cleaned raw transactional data
- 🔍 Engineered features like day of week, month, and customer behavior
- 📈 Trained and tuned **Linear Regression** and **Decision Tree** models
- 📊 Visualized trends, residuals, and feature importance
- ✅ Achieved an R² score of **92%** on unseen data

---

## 🗃️ Dataset

- Source: [Kaggle Supermarket Sales Dataset](https://www.kaggle.com/datasets/aungpyaeap/supermarket-sales)
- Size: ~1,000 transactions from 3 branches
- Key columns used:
  - `branch`, `product_line`, `customer_type`, `payment_method`
  - `quantity`, `unit_cost`, `rating`, `date`
  - Target: `revenue` (or `gross_income`)

---

## ⚙️ Tech Stack

- **Language**: Python
- **Libraries**: pandas, NumPy, matplotlib, seaborn, scikit-learn
- **Models**: Linear Regression, Decision Tree Regressor





