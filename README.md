# 🔍 K-Means Clustering - Task 8

## 📌 Objective
Use K-Means for unsupervised clustering of Mall Customers based on their income and spending score. Understand Elbow Method, clustering logic, and evaluation via Silhouette Score.

---

## 📚 Dataset
- **File**: `Mall_Customers.csv`
- **Source**: Local file
- **Columns used**: 
  - Annual Income (k$)
  - Spending Score (1-100)

---

## 🚀 What I Did

1. Loaded the dataset using Pandas.
2. Selected 2 numerical features.
3. Standardized the data.
4. Applied **Elbow Method** to choose the best value for `K`.
5. Performed KMeans clustering.
6. Visualized clusters and centers.
7. Evaluated clustering using **Silhouette Score**.

---

## 🔧 Tools & Libraries
- Python
- Scikit-learn
- Matplotlib
- Pandas
- Seaborn

---

## 📊 Results

- Optimal `K` was found using Elbow Method.
- Clusters visualized using a 2D scatter plot.
- Silhouette Score used to validate separation quality.

---
