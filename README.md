# 🏠 House Price Prediction

> A Machine Learning project that predicts house prices based on size, bedrooms and location — built with Python, Scikit-Learn and Matplotlib.

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?logo=scikit-learn&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-11557c)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![ML](https://img.shields.io/badge/ML-Linear_Regression-9cf)

---

## 📌 About this project

This is my first end-to-end Machine Learning project. I built a model that can predict the selling price of a house when given three inputs — the size of the house, the number of bedrooms, and the location quality score.

I built this project to apply what I learned from the **Machine Learning Specialization** taught by **Andrew Ng** on Coursera.

---

## 🎯 Problem Statement

```
Given:
  → Size of house (sqft)
  → Number of bedrooms
  → Location score (1 to 10)

Predict:
  → Estimated price of the house (USD)
```

---

## 🗂️ Dataset

I created a realistic dataset of 20 houses. No external dataset was used.

| Feature | Type | Description |
|---------|------|-------------|
| `size_sqft` | int | Size of house in square feet |
| `bedrooms` | int | Number of bedrooms |
| `location_score` | int | Location quality from 1 (poor) to 10 (excellent) |
| `price_usd` | float | House price in USD — this is what we predict |

---

## 🔄 Project Workflow

```
1. Create Dataset
       ↓
2. Explore and Understand Data
       ↓
3. Visualize with Charts
       ↓
4. Split into Train and Test sets (80/20)
       ↓
5. Train Linear Regression Model
       ↓
6. Evaluate Performance (R² Score, MSE)
       ↓
7. Predict New House Prices
```

---

## 📊 Model Results

| Metric | Result |
|--------|--------|
| Algorithm | Linear Regression |
| R² Score | ~0.99 |
| Train set | 80% of data |
| Test set | 20% of data |

> **R² Score of 0.99** means the model explains 99% of the price variation — very high accuracy for this dataset.

---

## 🖼️ Visualizations included

- 📉 House Size vs Price — scatter plot
- 🛏️ Bedrooms vs Price — scatter plot
- 🎯 Actual Price vs Predicted Price — comparison chart

---

## 💡 Sample prediction

```python
predict_price(size=1500, bedrooms=3, location_score=7)

# ╔══════════════════════════════╗
# ║  House Price Prediction      ║
# ║  Size          : 1500 sqft   ║
# ║  Bedrooms      : 3           ║
# ║  Location Score: 7/10        ║
# ║  Predicted Price: $96,500    ║
# ╚══════════════════════════════╝
```

---

## 🛠️ Tech stack

| Tool | Version | Purpose |
|------|---------|---------|
| Python | 3.x | Programming language |
| NumPy | Latest | Numerical computation |
| Pandas | Latest | Data handling |
| Matplotlib | Latest | Charts and visualization |
| Scikit-Learn | Latest | ML model |
| Jupyter Notebook | Latest | Development environment |

---

## 🚀 How to run

**On Google Colab — no installation needed**
1. Open the `.ipynb` file in this repository
2. Click **Open in Colab**
3. Click **Runtime → Run all**

**On your local machine**
```bash
pip install numpy pandas matplotlib scikit-learn jupyter
jupyter notebook House_Price_Prediction.ipynb
```

---

## 📁 Repository structure

```
House-Price-Prediction/
├── House_Price_Prediction.ipynb   # main notebook
└── README.md                      # project documentation
```

---

## 🔮 What I plan to add next

- [ ] Use a real dataset from Kaggle with 1000+ houses
- [ ] Add more features — house age, garage, garden, floors
- [ ] Compare with Random Forest and XGBoost models
- [ ] Build a simple web interface using Flask
- [ ] Deploy the model online using Streamlit

---

## 🧠 What I learned

Before this project, I only knew the theory of Linear Regression. Building it end-to-end taught me how to prepare real data, train a model, measure its accuracy, and make actual predictions. It also taught me how important data visualization is — the charts made it easy to understand what the model was learning.

This project gave me the confidence to take on more complex ML problems.

---

## 🔗 Related

- 📂 [ML-Practice Repository](https://github.com/rayhan-uddin9/ML-Practice) — all my ML learning and practice notebooks
- 📂 [Python-Documentation](https://github.com/rayhan-uddin9/Python-Documentation) — my complete 30-class Python training course

---

> 🎓 **Rayhan Uddin** · Computer Science Student · Bangladesh
>
> *"Every expert was once a beginner. This project is one step in my journey."*
