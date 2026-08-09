<!-- ========================= BANNER ========================= -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=0:0f2027,50:203a43,100:2c5364&height=180&section=header&text=SmartCart%20AI%20Platform&fontSize=40&fontColor=ffffff&desc=E-Commerce%20Customer%20Segmentation%20%7C%20AI%20Analytics&descAlign=50&descAlignY=70"/>
</p>

<h1 align="center">🛒 SmartCart Customer Segmentation System</h1>

<p align="center">
  🚀 AI/ML Project | Unsupervised Learning | Clustering  
  <br>
  📊 Transforming raw customer data into actionable business insights
</p>

---

## 📌 Problem Statement

SmartCart is a growing e-commerce platform with **2240 customers and 22 features**, including demographics, purchasing behavior, and engagement data. 

Currently, the platform uses **generic marketing strategies**, leading to:
-  Inefficient marketing campaigns  
-  Poor customer retention  
-  Inability to identify high-value or churn-prone customers  

👉 **Goal:**  
Build an **AI-powered customer segmentation system** using **unsupervised machine learning** to group customers into meaningful clusters. 

---

## 🎯 Objectives

- 🔍 Discover hidden patterns in customer behavior  
- 👥 Segment customers into meaningful groups  
- 📈 Improve marketing strategies  
- 💡 Enable data-driven decision making  
- 🎯 Identify high-value & churn-risk customers  

---

## 📂 Dataset Overview

Each row represents a **customer profile** with multiple attributes:

### 👤 Customer Demographics
- Year_Birth  
- Education  
- Marital_Status  
- Income  
- Kidhome, Teenhome  
- Dt_Customer  

### 🛍️ Purchase Behavior (Spending)
- MntWines  
- MntFruits  
- MntMeatProducts  
- MntFishProducts  
- MntSweetProducts  
- MntGoldProds  

### 🔁 Purchase Frequency
- NumDealsPurchases  
- NumWebPurchases  
- NumCatalogPurchases  
- NumStorePurchases  
- NumWebVisitsMonth  

### 📊 Customer Feedback
- Recency (days since last purchase)  
- Complain (0/1)  

---

## ⚙️ Tech Stack

- 🐍 Python  
- 📊 Pandas, NumPy  
- 📈 Matplotlib, Seaborn  
- 🤖 Scikit-learn  
- 📒 Jupyter Notebook  

---

# 📊 Data Analysis & Model Evaluation

## 🔍 Pairplot (Feature Relationships)

<p align="center">
  <img src="images/01_pairplot.png" width="700"/>
</p>

**Insights:**
- Strong relationships between spending categories  
- High spenders buy across multiple categories  
- Clear grouping patterns exist  

---

## 🔥 Correlation Heatmap

<p align="center">
  <img src="images/02_correlation_heatmap.png" width="700"/>
</p>

**Insights:**
- Spending features are positively correlated  
- Income strongly impacts spending  
- Useful for feature selection  

---

## 🧠 PCA 3D Projection

<p align="center">
  <img src="images/03_pca_3d_projection.png" width="700"/>
</p>

**Insights:**
- Reduced high-dimensional data to 3D  
- Visible cluster separation  
- Confirms clustering possibility  

---

## 📉 Elbow Method (WCSS)

<p align="center">
  <img src="images/04_elbow_wcss.png" width="700"/>
</p>

**Insights:**
- Optimal clusters at **K = 4**  
- Avoids overfitting  

---

## 📊 Silhouette Score

<p align="center">
  <img src="images/05_silhouette_score.png" width="700"/>
</p>

**Insights:**
- Measures cluster quality  
- Higher score → better clustering  

---

## 📊 Elbow + Silhouette Combined

<p align="center">
  <img src="images/06_elbow_silhouette_combined.png" width="700"/>
</p>

**Insights:**
- Confirms optimal K = 4  
- Strong validation  

---

## 🤖 K-Means 3D Clusters

<p align="center">
  <img src="images/07_kmeans_3d_clusters.png" width="700"/>
</p>

**Insights:**
- Clear separation of customer segments  
- High interpretability  

---

## 🔵 Agglomerative Clustering

<p align="center">
  <img src="images/08_agglomerative_3d_clusters.png" width="700"/>
</p>

**Insights:**
- Alternative clustering method  
- Similar results → robust model  

---

## 📊 Cluster Distribution

<p align="center">
  <img src="images/09_cluster_distribution.png" width="600"/>
</p>

**Insights:**
- Balanced clusters  
- No bias toward any group  

---

## 💰 Income vs Spending

<p align="center">
  <img src="images/10_income_vs_spending.png" width="700"/>
</p>

**Insights:**
- Higher income → higher spending trend  
- Some anomalies exist  
- Helps identify premium customers  

---
