# 📊 Sales Advertising Data Science Project

Analyze how TV, Radio, and Newspaper advertising affect sales using regression models.  
**Key findings:** TV and Radio have the strongest impact on sales, while Newspaper is minimal. The models help forecast sales and guide advertising strategy.

---

## 🗂️ Overview

- **Dataset:** `advertising.csv`
- **Techniques Used:**
  - Exploratory Data Analysis (EDA)
  - Linear Regression
  - Polynomial Regression
  - Ridge & Lasso Regression

---

## 🔑 Key Findings

- TV and Radio ads have the highest impact on sales.
- Newspaper advertising has minimal effect.
- Regression models accurately predict sales and guide ad budget allocation.

---

## 🚀 Project Steps

1. **Data Loading & Cleaning**
   - Import and inspect data for missing values.
2. **Visualization**
   - Use pairplots and correlation heatmaps to highlight feature relationships.
3. **Modeling**
   - Build and evaluate multiple regression models.
4. **Feature Importance**
   - Analyze which advertising channel influences sales the most.

---

## 💡 Recommendations

- Focus on TV and Radio for better ROI.
- Consider reducing Newspaper ad spending.
- Use models for sales forecasting and strategy optimization.

---

## 🛠️ How to Run

1. Clone this repository.
2. Open `Sales_Advertising_.ipynb` in Jupyter Notebook or Google Colab.
3. Upload `advertising.csv` when prompted.
4. Run all cells to reproduce analysis and results.

---

## 📦 Requirements

- Python 3
- `pandas`, `numpy`, `matplotlib`, `seaborn`
- `scikit-learn`

---

## 📈 Results

| Model                  | R² Score |
|------------------------|----------|
| Linear Regression      | ≈ 0.91   |
| Polynomial Regression  | ≈ 0.95   |
| Ridge/Lasso Regression | ≈ 0.91   |

---