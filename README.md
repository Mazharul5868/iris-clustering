# 🌸 Iris Dataset Clustering Project

This project explores unsupervised learning techniques to cluster species in the classic Iris dataset without prior labels. It compares multiple algorithms and highlights their strengths and limitations.

## 🔎 Project Overview
- **Goal:** Cluster iris flower species (Setosa, Versicolor, Virginica) using unsupervised learning  
- **Dataset:** Iris dataset 
- **Techniques Used:** K-Means, Hierarchical Clustering, DBSCAN  
- **Tools:** Python, Pandas, scikit-learn, Matplotlib, Seaborn  

## ⚙️ Workflow
1. Data preprocessing and feature scaling.  
2. Exploratory Data Analysis (EDA) with scatterplots, violin plots, and distributions.  
3. Dimensionality reduction with PCA for better cluster visualization.  
4. Applied clustering algorithms:  
   - **K-Means**  
   - **Hierarchical Clustering**  
   - **DBSCAN**  
5. Model evaluation with accuracy score, confusion matrix, and Adjusted Rand Index (ARI).  

## 📊 Results
- **K-Means**: Best performer with ~90% accuracy and ARI = 0.73.  
- **Hierarchical**: Moderate results (~82% accuracy, ARI = 0.59).  
- **DBSCAN**: Found 2 clusters + noise; correctly isolated Setosa but overlapped Versicolor and Virginica.  
