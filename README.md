# 🛍️ Customer Segmentation with K-Means

This project segments customers using K-Means clustering based on demographic and purchasing behavior from a marketing dataset.

## 📂 Dataset
- File: `marketing_campaign.csv` (tab-separated, 2240 records)
- Features: Age, Income, Marital Status, Product Purchases, Campaign Responses

## 🧪 Process
1. **Data Cleaning**: Filled missing values, converted dates
2. **Feature Engineering**: Created `Age`, `Children`, `TotalSpent`
3. **Scaling**: Used `StandardScaler` on selected features
4. **Clustering**: Applied K-Means after finding optimal `k` via Elbow method
5. **Visualization**: Used PCA to reduce dimensions for cluster plotting

## 📊 Features Used for Clustering
- `Income`, `Age`, `Children`, `Recency`, `TotalSpent`

## 📁 Files
- `customer_segmentation.ipynb`: Main notebook
- `marketing_campaign.csv`: Dataset

## ▶️ How to Run
```bash
jupyter notebook customer_segmentation.ipynb
```

## 📌 Output
- Customers grouped into clusters
- Visual cluster representation (2D PCA)
