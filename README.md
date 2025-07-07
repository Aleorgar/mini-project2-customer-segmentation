# 🎯 Mini-Project 2 – Customer Segmentation Analysis

> Data Science Mini-Project | Synthetic Data

---

## 💡 Project Overview

This mini-project focuses on **customer segmentation** using synthetic data designed for educational purposes. The goal is to identify distinct groups of customers based on behavioral and demographic features to support personalized marketing strategies and improve business decision-making.

A combination of classical statistical methods and machine learning algorithms was used to explore the data and extract meaningful clusters.

---

## 📂 Project Files

- `Ortuno_Alejandro_CAM_C101_Week_6_Mini-project.ipynb` → Jupyter notebook containing the entire analysis, visualizations, and clustering results.

---

## 🔎 Project Steps

1. **Data Preparation & Feature Engineering**
   - Original dataset included:
     - Order ID
     - Customer ID
     - Order Date
     - Delivery Date
     - Unit Cost
     - Total Revenue
   - Engineered key features for clustering:
     - Frequency (number of purchases)
     - Recency (days since last purchase)
     - CLV (Customer Lifetime Value)
     - Avg_Unit_Cost (average product cost)
     - Age (customer age)

2. **Exploratory Data Analysis (EDA)**
   - Boxplots and descriptive statistics for each feature.
   - Analyzed distributions and potential outliers.

3. **Dimensionality Reduction**
   - Applied PCA to visualize customer data in 2D space.
   - Used t-SNE for non-linear dimensionality reduction and cluster separation visualization.

4. **Clustering Techniques**
   - **K-Means Clustering**
     - Tested multiple k-values.
     - Used Elbow Method and Silhouette Score to determine optimal k = 5.
   - **Hierarchical Clustering**
     - Constructed dendrograms to explore cluster distances and merging patterns.

5. **Visualization**
   - PCA scatter plots colored by cluster.
   - t-SNE scatter plots for cluster visualization.
   - Boxplots showing feature distribution per cluster.
   - Elbow curve and silhouette analysis.
   - Dendrogram for hierarchical clustering insights.

---

## 📊 Key Insights

- **Cluster 1** → High-frequency, high-CLV customers; loyal and valuable segment.
- **Cluster 2** → Lower average unit cost, moderate spending behavior.
- **Cluster 3** → Younger customers with lower purchasing engagement.
- **Cluster 0** → Older customers, low frequency and low CLV.
- **Cluster 4** → Customers purchasing high unit-cost products but with lower transaction frequency.

Each cluster revealed **distinct spending patterns and customer profiles**, providing actionable insights for potential marketing strategies.

---

## 🚫 Confidentiality Note

> This project uses **synthetic data only** and does **not contain any proprietary or confidential information.**  
> Safe to include in public portfolios and repositories.

---

## 🛠️ Technologies Used

- Python 3.9
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 👨‍💻 Author

Alejandro Ortuño  
[LinkedIn](https://www.linkedin.com/in/alejandro-ortuno-garcia-1bb778171/) | [GitHub](https://github.com/aleorgar)
