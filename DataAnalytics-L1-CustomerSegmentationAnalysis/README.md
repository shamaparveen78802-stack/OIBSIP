# TASK 2 - Customer Segmentation Analysis | OIBSIP Data Analytics Internship

### Objective
Apply clustering algorithms to segment an e-commerce company's customer base into distinct groups based on purchasing behaviour, enabling targeted marketing strategies.

### Dataset
Online Retail Dataset from UCI (Kaggle) - E-commerce customer data containing InvoiceNo, StockCode, Quantity, InvoiceDate, UnitPrice, CustomerID.

### Tech Stack
- Python, pandas, numpy
- scikit-learn (KMeans, StandardScaler)
- matplotlib, seaborn
- Jupyter Notebook

### Workflow & Feature Checklist Completed

- [x] Load dataset and inspect structure; handle missing values and inconsistent data - Removed null CustomerID and cancelled orders
- [x] Descriptive statistics: calculated average purchase value, purchase frequency, customer lifetime value using RFM analysis
- [x] Feature selection: Selected 3 key behavioural features - Recency, Frequency, Monetary (RFM analysis)
- [x] Data normalisation/standardisation before clustering - Used StandardScaler
- [x] Apply K-Means clustering - Used Elbow Method to determine optimal K=4
- [x] Visualise clusters using scatter plots - Plotted Recency vs Monetary and Frequency vs Monetary
- [x] Profile each cluster: calculated mean feature values per cluster and described the customer type
- [x] Bar chart: number of customers per cluster
- [x] Insights section: marketing action recommended for each segment

### Key Insights from Clustering (K=4)

**Cluster 2 - Champions (High Value):** Recency 0-25 days, Monetary > 1 Lakh. Strategy: VIP loyalty program.

**Cluster 3 - Loyal Customers:** Recency 0-50 days, Monetary 20k-90k. Strategy: Upsell & Cross-sell.

**Cluster 0 - Potential / New Customers:** Recency 0-140 days, Monetary < 20k. Largest segment. Strategy: Engagement offers, BOGO.

**Cluster 1 - At-Risk / Lost:** Recency 150-375 days. Strategy: Re-activation campaign with win-back discounts.

### Project Structure
