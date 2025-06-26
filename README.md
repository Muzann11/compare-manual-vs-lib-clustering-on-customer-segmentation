# 📊 Customer Clustering: Manual vs Library Methods

This project explores **unsupervised customer segmentation** using various clustering techniques, both implemented **from scratch** and using **scikit-learn**, enhanced with **Principal Component Analysis (PCA)** for dimensionality reduction and visualization.

---

## 🧠 Project Objectives

* Apply **K-Means** and **Hierarchical Clustering** to segment customers.
* Compare **manual vs library-based implementations**.
* Utilize **PCA** to:

  * Reduce dimensionality while preserving variance
  * Improve clustering performance
* Evaluate clustering performance using:

  * Silhouette Score
  * Davies-Bouldin Index
  * Calinski-Harabasz Index
  * Rand Index
  * Purity Score

---

## 📦 Dataset

* **Source**: Kaggle – [Customer Segmentation](https://www.kaggle.com/datasets/vetrirah/customer)
* **Target Variable**: `Segmentation` (classes A, B, C, D)

---

## ⚙️ Methods and Workflow

1. **EDA & Preprocessing**

   * Handling missing values, outliers, and categorical encoding
   * Standardization of numerical features
2. **Clustering Models**

   * ✅ **K-Means** (manual and scikit-learn)
   * ✅ **Hierarchical Clustering** (manual and scikit-learn; Single & Complete linkage)
3. **💡 Principal Component Analysis (PCA)**

   * PCA with 95% variance retention
   * PCA 2D projection for visual inspection
   * Dimensionality reduction to improve runtime and clustering clarity
4. **Evaluation**

   * Multi-metric assessment of all models
   * Purity and Rand Score for ground truth alignment

---

## 📈 PCA Highlights

| Purpose                   | Description                                                        |
| ------------------------- | ------------------------------------------------------------------ |
| **Variance Preservation** | PCA reduced data dimensionality while maintaining >95% information |
| **Performance**           | Improved Silhouette, CH Index, and execution time in clustering          |
| **Noise Reduction**       | Helped eliminate redundant and weakly informative features         |

---
