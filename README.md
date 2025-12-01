📊 K-Means vs Hierarchical Clustering on Indonesia Sugarcane Data

This project performs a comparative clustering analysis on Indonesia's sugarcane dataset (2010–2024) using K-Means and Hierarchical Clustering. The goal is to identify meaningful patterns in production, productivity, and regional performance while evaluating which algorithm provides more stable and accurate clustering results.

🚀 Project Overview

- Conducted exploratory data analysis (EDA) on sugarcane production data across Indonesian regions.

- Implemented K-Means and Agglomerative Hierarchical Clustering using Scikit-learn.

- Standardized features to ensure fair comparison between algorithms.

- Evaluated clustering performance using:

  - Silhouette Score

  - Davies-Bouldin Index

- Visualized cluster distribution using scatter plots and dendrograms.

🧠 Key Findings

- K-Means achieved higher stability and better-defined cluster boundaries, with a Silhouette Score > 0.8.

- Hierarchical Clustering provided interpretable structure via dendrograms but showed lower performance on high-dimensional features.

- Overall, K-Means outperformed Hierarchical Clustering in both accuracy and cluster separation.

📁 Tech Stack

- Python

- Pandas

- NumPy

- Scikit-learn

- Matplotlib

📜 Conclusion

This project demonstrates how different clustering methods behave on agricultural datasets and highlights why K-Means is often preferred for larger, multi-feature datasets due to its efficiency and strong performance metrics.
