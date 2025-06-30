🧠 Customer Segmentation Using K-Means Clustering

This repository contains a machine learning project focused on segmenting customers based on their behavior using the **K-Means Clustering** algorithm. The analysis is conducted in two phases — a basic model with two features, and an extended model with simulated behavioral features.

## 🔍 Project Overview

The project aims to identify distinct customer groups from mall customer data, which can then be used for targeted marketing strategies and customer experience optimization.

### 📌 Phase 1: Basic Clustering
- Features used:  
  - `Annual Income (k$)`  
  - `Spending Score (1-100)`
- Applied **StandardScaler** to normalize the data
- Used the **Elbow Method** to determine optimal number of clusters
- Visualized clusters and centroids

### 📌 Phase 2: Extended Clustering
- Additional features added:  
  - `Frequency of Purchase` *(simulated)*  
  - `Recency (days)` *(simulated)*  
  - `Average Transaction Value` *(simulated)*
- Performed re-scaling and clustering with extended features
- Improved granularity in customer segmentation

## 🛠️ Technologies Used
- Python
- Jupyter Notebook / Google Colab
- Libraries:
  - `pandas`
  - `numpy`
  - `scikit-learn`
  - `matplotlib`
  - `seaborn`

## 📈 Key Learnings
- Hands-on implementation of **unsupervised learning**
- Deep understanding of **K-Means Clustering** and **Elbow Method**
- Data preprocessing, scaling, and visualization techniques
- Real-world simulation of customer behavior for enriched insights

## 📁 Dataset
- `Mall_Customers.csv`: Structured dataset containing demographic and spending information of customers.


## 📊 Outputs
- Inertia plot showing optimal `k` (number of clusters)
- Cluster visualization before and after feature expansion
- Dataframe with cluster labels for each customer

