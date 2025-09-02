# 🛒 E-Commerce Customer Segmentation & Recommendation System (WIP)

## 📌 Overview
This is a **work-in-progress Data Science/ML project** using the Instacart Online Grocery Shopping Dataset.  
Goals:  
1. Segment customers based on shopping behavior (RFM + clustering).  
2. Build a recommendation system to suggest relevant products.  

---

## 📂 Dataset
Using the **Instacart Online Grocery Shopping Dataset**, which includes:

| File                             | Description                                         |
|----------------------------------|-----------------------------------------------------|
| `orders.csv`                     | Order-level details (order_id, user_id, time info)  |
| `order_products__prior.csv`      | Products from customers’ prior orders               |
| `order_products__train.csv`      | Products from customers’ most recent orders         |
| `products.csv`                   | Product information                                 |
| `aisles.csv`                     | Aisle metadata                                      |
| `departments.csv`                | Department metadata                                 |

---

## 🛠️ Tech Stack
- **Python (3.10)**, Conda  
- **pandas, numpy, matplotlib, seaborn, scikit-learn, plotly**  
- **Recommenders:** scikit-surprise, implicit  
- **Optional Dashboard:** Streamlit/PowerBI/Tableau  

---

## 🚀 Workflow
1. Setup environment & load data  
2. Data cleaning & feature engineering (RFM, basket size, reorder rate)  
3. Customer segmentation (K-Means, Elbow, Silhouette)  
4. Recommendation system (Collaborative filtering)  
5. Evaluation (Precision@K, Recall@K)  
6. Visualization & business insights  

---

## 📁 Structure
