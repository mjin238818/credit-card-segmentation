# Credit Card Usage Segmentation

This capstone project aims to segment credit card customers into distinct groups based on their usage behavior using **K-Means** and **Agglomerative Clustering**. The goal is to help businesses tailor marketing strategies, risk mitigation, and optimize credit offerings.

## Tools & Technologies

- **Python** (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)
- **Machine Learning**: KMeans, Agglomerative Clustering, PCA, t-SNE
- **Power BI**: Dashboard to visualize cluster behaviors and key insights
- **Jupyter Notebook**: Data exploration and model building

## Methodology

1. Data Preprocessing
2. Dimensionality Reduction
3. Clustering Techniques
    - **K-Means Clustering**
      - Optimal k selected using Elbow & Silhouette methods
    - **Agglomerative Clustering**
      - Evaluated using dendrograms and silhouette scores
4. Cluster Profiling
    - Interpreted clusters using:
      - Spending patterns
      - Payment behavior
      - Credit usage
    - Cluster examples:
      - `Cluster 0`: Riskier, cash-focused customers
      - `Cluster 1`: High-spending, responsible payers

---

## Power BI Dashboard

The `.pbix` dashboard visually compares clusters on:
- Balance
- Purchasing behaviour
- Credit limit usage
- Repayment behavior

Business insights were drawn from the dashboard.

---

## Key Insights

- **Targeted Marketing**: High-value clusters can be offered premium services.
- **Risk Mitigation**: Risk-prone clusters can be monitored or offered secured products.
