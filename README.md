# Myntra-Online-Retail-Customer-Segmentation
# 🛍️ Myntra Online Retail Customer Segmentation

## 📌 Project Overview  
This project performs *Customer Segmentation for Myntra Gifts Ltd.* using *RFM (Recency, Frequency, Monetary)* analysis and clustering algorithms.  
The goal is to group customers into meaningful segments for *targeted marketing, customer retention, and business growth*.

---

## 📊 Dataset  
*Source:* Myntra Gifts Ltd. Online Retail Data (Dec 2009 – Dec 2011)  
*Records:* 541,909 transactions  

### Key Columns:
- *InvoiceNo* – Unique invoice number  
- *StockCode* – Product code  
- *Description* – Product description  
- *Quantity* – Units purchased  
- *InvoiceDate* – Date of purchase  
- *UnitPrice* – Price per unit  
- *CustomerID* – Unique customer identifier  
- *Country* – Customer’s location  

---

## 🛠️ Tools & Technologies  
*Programming Language:* Python  
*Libraries:* Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn  

### Techniques:
- RFM Analysis  
- K-Means Clustering  
- Hierarchical Clustering (Agglomerative)  
- DBSCAN  
- Elbow Method & Silhouette Score for model selection  

---

## 🔍 Data Preprocessing  
- Removed duplicates and cancelled orders (InvoiceNo starting with *"C"*)  
- Handled missing values (Description, CustomerID)  
- Filtered negative quantities & prices  
- Created *Revenue = Quantity × UnitPrice*  
- Extracted *day, month, year, hour* from InvoiceDate  
- Scaled RFM values before clustering  

---

## 📈 Exploratory Data Analysis (EDA)
*Visualizations created:*
- Top 10 Most Sold Products  
- Top 10 Products by Revenue  
- Monthly Sales Trends  
- Customer Segmentation by Purchase Frequency  
- Sales by Country  
- Hourly Purchase Patterns  
- Sales by Day of Week  
- Hourly Purchases for Top 10 Countries  
- RFM Distribution Analysis  
- Cluster Distribution Visualization  

---

## 🤖 Machine Learning Models  

### 🔹 K-Means Clustering (Final Model)
- Optimal clusters determined using *Elbow Method & Silhouette Score (0.52)*  
- Segments customers into *high-value, **potential churners, and **occasional buyers*

### 🔹 Hierarchical Clustering  
- Validated relationships via *dendrograms*

### 🔹 DBSCAN  
- Identified *outliers* & *noise*

---

## 📊 Key Results  
- *3 optimal clusters* identified for targeted marketing campaigns  
- *High-value customers* account for ~20% of customers but ~60% of revenue  
- *Churn-prone customers* identified for re-engagement campaigns  

---

## 💡 Business Impact  
- Targeted marketing improves *retention by ~30%*  
- Proactive engagement reduces *churn risk*  
- Efficient marketing budget allocation improves *ROI*

---

## 🚀 Conclusion  
The segmentation model enables *Myntra* to personalize campaigns, increase retention, and optimize resource allocation.  
*K-Means clustering* proved to be the most efficient model for this dataset.

---
