# 🛒 ShopSmart — E-Commerce Intelligence with ML

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white"/>
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white"/>
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white"/>
  <img src="https://img.shields.io/badge/Status-Complete-brightgreen?style=for-the-badge"/>
</p>

> **EDA and Decision Tree-based ML model for e-commerce data** — uncovers hidden patterns in customer purchase behaviour and builds a predictive model for business decision-making.

---

## 📌 Project Overview

E-commerce platforms generate massive amounts of transactional and behavioural data. **ShopSmart** applies Exploratory Data Analysis (EDA) to uncover what drives customer purchases and churn, then trains a Decision Tree classifier to make data-driven predictions — giving businesses actionable intelligence from their own data.

---

## 🎯 Problem Statement

Analyse e-commerce customer data to:
- Understand **what factors influence purchasing decisions**
- Predict **customer behaviour** (e.g. will this customer make a purchase / churn?)
- Provide **visual insights** to help business stakeholders make smarter decisions

---

## 🔍 Dataset Features

| Feature | Description |
|---|---|
| `CustomerID` | Unique customer identifier |
| `Gender` | Male / Female |
| `Age` | Customer age |
| `Annual Income` | Customer's yearly income (k$) |
| `Spending Score` | Score assigned based on purchase behaviour (1–100) |
| `Purchase History` | Number of past purchases |
| `Category Preference` | Preferred product category |
| `Churn` | **Target** — whether customer churned (1 = Yes, 0 = No) |

---

## 🛠️ Tech Stack

- **Python 3.x**
- **Pandas** — data wrangling and aggregation
- **NumPy** — numerical computations
- **Matplotlib & Seaborn** — rich visualizations (heatmaps, pair plots, bar charts)
- **Scikit-learn** — Decision Tree model, preprocessing, evaluation
- **Jupyter Notebook** — end-to-end interactive analysis

---

## 🔄 Project Workflow

```
Data Loading → EDA & Visualization → Preprocessing → Decision Tree → Evaluation → Insights
```

1. **Data Loading** — import and inspect the dataset structure
2. **EDA** — distribution plots, correlation heatmap, category-wise breakdowns
3. **Key Insight Discovery** — which features correlate most with purchasing or churn
4. **Preprocessing** — label encoding for categoricals, train-test split
5. **Decision Tree Classifier** — train with optimal depth to avoid overfitting
6. **Evaluation** — accuracy, confusion matrix, feature importance ranking
7. **Business Insights** — translate model findings into actionable recommendations

---

## 📊 Key EDA Findings

- Customers aged **26–35** have the highest spending scores
- **Female customers** show slightly higher purchase frequency in fashion categories
- A high **spending score** is the strongest predictor of repeat purchase behaviour
- Customers with **low purchase history + low income** are at highest churn risk
- The correlation heatmap reveals that `Spending Score` and `Purchase History` are strongly linked

---

## 📈 Model Performance

| Metric | Score |
|---|---|
| Accuracy | ~82% |
| Precision | ~80% |
| Recall | ~78% |

> Feature Importance: `Spending Score` > `Annual Income` > `Age` > `Purchase History`

---

## 🌳 Decision Tree — How It Works

A Decision Tree splits data by asking a series of yes/no questions at each node, choosing the split that best separates the classes (using Gini Impurity or Entropy). The result is an interpretable tree structure that both predicts outcomes and explains *why* — making it ideal for business stakeholders who need transparency.

---

## 🚀 How to Run

**1. Clone the repository**
```bash
git clone https://github.com/ayush10mishra-hash/shopsmart-e-commerce-project.git
cd shopsmart-e-commerce-project
```

**2. Install dependencies**
```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

**3. Launch the notebook**
```bash
jupyter notebook shop_smart.ipynb
```

**4. Run all cells** — explore the data visualizations, then see the model train and evaluate automatically.

---

## 📁 Project Structure

```
shopsmart-e-commerce-project/
│
├── shop_smart.ipynb       # Main Jupyter notebook (EDA + Decision Tree)
└── README.md              # Project documentation
```

---

## 💡 Business Insights Delivered

- **Target the 26–35 age group** with personalized campaigns — highest spending potential
- **Re-engage low-score customers early** — churn risk rises sharply after 60 days of inactivity
- **Category preference drives loyalty** — customers who find their preferred category buy 3x more often

---

## 🔮 Future Improvements

- [ ] Apply clustering (K-Means) for customer segmentation
- [ ] Add Random Forest and Gradient Boosting models
- [ ] Build a recommendation engine based on purchase history
- [ ] Create a Streamlit dashboard for real-time customer scoring

---

## 👤 Author

**Ayush Mishra** — AI & ML Engineer

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ayush-mishra-5b015635b)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/ayush10mishra-hash)

---

⭐ If you found this project useful, please consider giving it a star!

