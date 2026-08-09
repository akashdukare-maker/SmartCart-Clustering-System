<!-- ========================= BANNER ========================= -->
<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Orbitron&size=30&duration=3000&pause=1000&color=00F7FF&center=true&vCenter=true&width=900&lines=SmartCart+Customer+Segmentation+System;AI+%7C+Machine+Learning+%7C+Clustering;Transforming+Data+into+Business+Insights" />
</p>

<h1 align="center">🛒 SmartCart Customer Segmentation System</h1>

<p align="center">
  🚀 AI/ML Project | Unsupervised Learning | Clustering  
  <br>
  📊 Transforming raw customer data into actionable business insights
</p>

---

## 📌 Problem Statement

SmartCart is a growing e-commerce platform with **2240 customers and 22 features**, including demographics, purchasing behavior, and engagement data. :contentReference[oaicite:0]{index=0}  

Currently, the platform uses **generic marketing strategies**, leading to:
-  Inefficient marketing campaigns  
-  Poor customer retention  
-  Inability to identify high-value or churn-prone customers  

👉 **Goal:**  
Build an **AI-powered customer segmentation system** using **unsupervised machine learning** to group customers into meaningful clusters. :contentReference[oaicite:1]{index=1}  

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

## 🔬 Project Workflow

```mermaid
graph TD
A[Raw Dataset] --> B[Data Cleaning]
B --> C[Feature Engineering]
C --> D[Scaling]
D --> E[Clustering Model]
E --> F[Evaluation]
F --> G[Visualization]
G --> H[Business Insights]

