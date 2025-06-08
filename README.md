# 🛍️ Customer Segmentation and Prediction Project

This project focuses on segmenting customers based on their purchasing behavior and predicting their spending scores using machine learning.

---

## 🎯 Objective

To perform customer segmentation using **K-Means clustering** and predict future buying patterns with a **Decision Tree Regressor**.

---

## 📂 Dataset

- Dataset Used: `Mall_Customers_sample.csv`
- Source: [Kaggle – Customer Segmentation Dataset](https://www.kaggle.com/datasets)
- Features:
  - `CustomerID`
  - `Gender`
  - `Age`
  - `Annual Income (k$)`
  - `Spending Score (1-100)`

---

## 🧠 Workflow

### 1. Data Cleaning
- Checked for missing values and duplicates
- Encoded categorical features (e.g., Gender)

### 2. Feature Engineering
- Used existing features like Age, Income, and Spending Score
- Scaled data for clustering

### 3. Customer Segmentation
- Applied **K-Means Clustering**
- Used Elbow Method to choose optimal `k=3`
- Visualized clusters using a scatter plot

### 4. Prediction Model
- Trained a **Decision Tree Regressor** to predict `Spending Score`
- Evaluated with **RMSE = 29.77**

### 5. Business Insights
| Cluster | Customer Type             | Income Level | Spending Score | Strategy                  |
|---------|---------------------------|--------------|----------------|----------------------------|
| 0       | High Income, Low Spend    | High         | Low            | Upsell via premium offers  |
| 1       | Low Income, Low Spend     | Low          | Low            | Discounts & budget deals   |
| 2       | High Spend, Medium Income | Medium       | High           | Personalized promotions    |

---

## 📈 Tools & Libraries

- 🐼 Pandas
- 📊 Matplotlib, Seaborn
- 🧮 Scikit-learn
- 📁 Google Colab

---

## 📌 Results

- ✅ Segmented customers into 3 actionable groups
- ✅ Built a model to predict spending behavior
- ✅ Provided marketing recommendations per segment

---

## 📎 How to Run

1. Open the notebook in Google Colab or Jupyter.
2. Upload the dataset (`Mall_Customers_sample.csv`).
3. Run each cell to view the results.

---

## 📬 Contact

**Gunjan Gangarapu**  
Data Analytics & AI Enthusiast  
[LinkedIn](https://www.linkedin.com/) | [GitHub](https://github.com/)

---

