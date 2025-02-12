# Module 19 Challenge - CryptoClustering

## Author: Jose Moncada  

### Overview  
This project focuses on clustering cryptocurrency market data using K-Means and Principal Component Analysis (PCA). The goal is to analyze the impact of dimensionality reduction on clustering results and compare performance between the original and PCA-transformed datasets.  

### Technologies Used  
- Python  
- Pandas  
- Scikit-Learn  
- hvPlot  
- Principal Component Analysis (PCA)  
- K-Means Clustering  

### Key Steps  
1. **Data Preprocessing:**  
   - Load and inspect the cryptocurrency market data.  
   - Normalize the data using `StandardScaler`.  

2. **K-Means Clustering (Original Data):**  
   - Determine the optimal number of clusters using the Elbow Method.  
   - Apply K-Means clustering to the scaled dataset.  
   - Visualize the clusters in a scatter plot.  

3. **Dimensionality Reduction with PCA:**  
   - Reduce the dataset to three principal components.  
   - Analyze explained variance to assess data retention.  

4. **K-Means Clustering (PCA Data):**  
   - Repeat the clustering process using the PCA-transformed dataset.  
   - Compare clustering results to the original dataset.  

5. **Visualizations & Analysis:**  
   - Generate Elbow curves for both datasets.  
   - Compare clustering results using scatter plots.  

### Key Findings  
- Using PCA reduced the number of features while preserving most of the variance.  
- Clustering on PCA-transformed data resulted in more well-defined and separable clusters.  
- The optimal **k** value remained the same before and after applying PCA, indicating that the fundamental clustering structure was retained.  

### Conclusion  
Dimensionality reduction with PCA improves clustering efficiency while maintaining meaningful patterns in the data. This approach helps reduce noise and computational complexity, leading to more interpretable clustering results.  

---
📌 **Author:** Jose Moncada  
🚀 **Challenge:** Module #19 - CryptoClustering  
