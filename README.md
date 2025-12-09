# Dimensionality Reduction and Clustering Tutorial  
### PCA vs t-SNE vs UMAP on the Mall Customers Dataset

This repository contains the code and tutorial for a comparative study of three major dimensionality reduction techniques—**Principal Component Analysis (PCA)**, **t-Distributed Stochastic Neighbour Embedding (t-SNE)**, and **Uniform Manifold Approximation and Projection (UMAP)**—applied to the **Mall Customers dataset** from Kaggle.

The aim of this tutorial is to demonstrate how each method transforms high-dimensional data, how these transformations affect clustering performance, and why nonlinear manifold learning techniques (t-SNE, UMAP) often outperform linear methods (PCA) for uncovering structure in customer segmentation.

---

## 📌 Project Overview

This tutorial covers:

- Theoretical explanation of PCA, t-SNE, and UMAP  
- Data preprocessing and standardisation  
- 2D embeddings using each technique  
- K-Means clustering on each embedding  
- Evaluation using **silhouette scores**  
- Visual comparison of cluster separation and explained variance  

This repository includes:

- Jupyter Notebook (`notebook.ipynb`)
- Generated plots (in `/figures`)
- PDF / Report (if applicable)
- README and LICENSE files

---

## 📊 Dataset

**Dataset:** *Mall Customer Segmentation Data*  
Source: Kaggle  
Link: https://www.kaggle.com/datasets/shwetabh123/mall-customers

The dataset contains demographic and behavioural attributes:

- Gender  
- Age  
- Annual Income (k$)  
- Spending Score (1–100)  

Ensure this file is downloaded from Kaggle and placed in the `data/` folder.

---

## 🧪 Methods Used

### **1. Dimensionality Reduction**
- **PCA** (linear)
- **t-SNE** (nonlinear, neighbourhood-based)
- **UMAP** (manifold learning using graph topology)

### **2. Clustering**
- **K-Means** on each embedding  
- **Silhouette Score** evaluation  

### **3. Visualisation**
- 2D scatter plots of embeddings  
- Silhouette score comparison  
- PCA cumulative explained variance  

---

## 🛠️ How to Run the Notebook

### **1. Install dependencies**
Recommended (Jupyter):

```bash
pip install numpy pandas scikit-learn matplotlib seaborn umap-learn
```

