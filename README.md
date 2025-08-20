# Customer Segmentation using RFM and K-Means Clustering

##  Overview
This project applies **RFM (Recency, Frequency, Monetary) analysis** and **K-Means clustering** to segment customers into meaningful groups such as VIPs, Loyal Customers, and At-Risk Customers.  
The goal is to help businesses understand customer behavior and improve targeted marketing strategies.  

##  Dataset
The dataset is an e-commerce transactions dataset with columns:  
`InvoiceNo, StockCode, Description, Quantity, InvoiceDate, UnitPrice, CustomerID, Country`  

Preprocessing steps included:
- Removing missing Customer IDs  
- Filtering out returns (negative quantities)  
- Creating an RFM table per customer  

##  Methodology
1. **Data Cleaning** → Removed nulls & returns  
2. **Feature Engineering** → Computed Recency, Frequency, Monetary  
3. **Log Transformation & Scaling** → Handled skewness and normalized features  
4. **Clustering** → Applied K-Means with optimal *k* chosen using Elbow Method & Silhouette Score  
5. **Cluster Profiling** → Named segments based on behavior  

##  Results
- Segmented customers into **4 clusters**:  
  - **VIP Customers** → Recent, frequent, and high spenders  
  - **Loyal Buyers** → Fairly frequent and moderate spenders  
  - **At-Risk Customers** → Haven’t purchased in a long time  
  - **One-time/Low-Value Customers** → Very low engagement and spend  

- Evaluated clustering using:  
  - **Elbow Method (Inertia vs K)**  
  - **Silhouette Score vs K**  

##  Visualization
Created an interactive **Power BI dashboard** to visualize:  
- Customer distribution across clusters  
- Total Monetary by cluster  
- KPIs: % of High-Value Customers, Cluster counts, etc.  
- Clustering metrics (Elbow & Silhouette score)  

##  Tech Stack
- Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)  
- Power BI (Interactive dashboard)  

##  Contact
Author: Abdul Rafey  
🔗 [LinkedIn](https://www.linkedin.com/in/abdul--rafey/)  
🔗 [GitHub](https://github.com/Abdulrafey7)
