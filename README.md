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

