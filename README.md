# 🛍️ Online Retail Customer Segmentation

A machine learning project for segmenting customers based on their purchasing behavior using RFM analysis and clustering techniques.

---

## 📚 Table of Contents

- [About the Project](#about-the-project)
- [Dataset Description](#dataset-description)
- [Project Pipeline](#project-pipeline)
- [Tech Stack](#tech-stack)
- [Results & Insights](#results--insights)
- [Visualizations](#visualizations)
- [Project Goals](#project-goals)
- [Contact](#contact)

---

## 📌 About the Project

This project aims to segment customers from an online retail store using unsupervised machine learning techniques such as **K-Means**, **DBSCAN**, and **Hierarchical Clustering**. The segmentation helps businesses identify different types of customers for targeted marketing and better decision-making.

---

## 📂 Dataset Description

The dataset is based on transactions from a UK-based online retail store and contains the following features:

| Column        | Description                              |
|---------------|------------------------------------------|
| InvoiceNo     | Invoice number (unique transaction ID)   |
| StockCode     | Product/item code                        |
| Description   | Product description                      |
| Quantity      | Number of items purchased                |
| InvoiceDate   | Date and time of purchase                |
| UnitPrice     | Price per item                           |
| CustomerID    | Unique ID for each customer              |
| Country       | Country name                             |

> 📝 Note: Dataset requires preprocessing to handle missing values and outliers.

---

## 🔁 Project Pipeline

1. **Data Cleaning & Preprocessing**
   - Remove null values
   - Handle returns (negative quantities)
   - Remove duplicates

2. **Feature Engineering**
   - Calculate Total Amount (`Quantity * UnitPrice`)
   - RFM (Recency, Frequency, Monetary) computation

3. **Clustering**
   - K-Means
   - DBSCAN
   - Hierarchical Clustering

4. **Model Evaluation**
   - Silhouette Score
   - Elbow Method

5. **Visualization & Insights**
   - Cluster distributions
   - Sales trends
   - Top products/customers

---

## 🛠️ Tech Stack

| Tool           | Purpose                          |
|----------------|----------------------------------|
| Python         | Programming language             |
| Pandas         | Data manipulation                |
| NumPy          | Numerical computations           |
| Matplotlib     | Plotting                         |
| Seaborn        | Statistical visualization        |
| Scikit-learn   | Clustering algorithms & metrics  |

---


## 📈 Results & Insights
- Clustered customers into meaningful segments.

- Identified high-frequency and high-monetary value customers.

- Visualized product demand and purchasing patterns.

- Evaluated clustering effectiveness using silhouette coefficient



📊 Visualizations

- RFM score distribution

- K-Means clusters (2D plot)

- Dendrogram (for hierarchical clustering)

- Sales trends over time

- Top 10 products and customers (bar plots)

🎯 Project Goals

- Understand and segment customer base

- Optimize marketing campaigns

- Improve customer retention and targeting

- Support data-driven retail strategies

### 📬 Contact

📧 **Nikhil Negi**  
🔗 [LinkedIn](https://www.linkedin.com/in/nikhil-negi-0bb166328)  
📁 [GitHub](https://github.com/Negi270804)



---


