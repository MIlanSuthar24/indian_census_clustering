# Indian Census Clustering: Socio-Economic Segmentation

**A data analytics project focused on exploring socio-economic patterns using Indian census-style data.**

---

## 📂 Project Structure

indian_census_clustering/
│── Dataset/caste_clustering_data.csv
│── Visuals/
│ ├── income_distribution.png
│ ├── literacy_distribution.png
│ ├── caste_distribution.png
│ ├── elbow_method.png
│ ├── dendrogram.png
│ ├── kmeans_pca.png
│ ├── agglo_pca.png
│ └── dbscan_pca.png
│── clustering_analysis.ipynb
│── README.md



---

## 🔍 Objectives

- Analyze caste-wise population and income distribution.  
- Apply clustering algorithms to identify socio-economic groups.  
- Compare K-Means, Agglomerative, and DBSCAN clustering methods.  
- Visualize clusters with PCA for interactive insights.  

---

## 🧰 Tools & Technologies

- Python  
- Pandas, NumPy  
- Seaborn, Matplotlib  
- Scikit-learn  
- PCA for dimensionality reduction  

---

## 📊 Clustering Algorithms & Metrics

| Algorithm           | Silhouette Score |
|-------------------|----------------|
| K-Means           | 0.249          |
| Agglomerative     | 0.235          |
| DBSCAN            | 0.179          |

**Insights:**  
- **K-Means:** Best cluster separation; clear socio-economic segmentation.  
- **Agglomerative:** Hierarchical view of clusters; slightly less compact.  
- **DBSCAN:** Detects outliers and irregular clusters.  
- Certain caste groups are concentrated in lower-income brackets.  
- Literacy rate, occupation, and income influence cluster formation.  

---

## ✅ Final Conclusion

This project demonstrates how **clustering and visualization** can uncover hidden socio-economic structures, aiding policymakers and researchers in data-driven insights. Combining multiple clustering approaches provides a comprehensive view of population patterns.

---

## 📷 Visualizations

- `Visuals/` folder contains plots for:
  - Income and literacy distribution  
  - Caste category distribution  
  - Elbow method for K-Means  
  - Hierarchical dendrogram  
  - PCA-based cluster visualizations  

---

## 🚀 How to Run

1. Install required packages:

pip install pandas numpy matplotlib seaborn scikit-learn

2.Open clustering_analysis.ipynb in Jupyter Notebook or Jupyter Lab.

3.Run all cells to reproduce analysis, clustering, and visualizations.


🙋 About Me:
Milan Suthar
MSc Statistics & Computing, BHU
Aspiring Data Analyst | Skilled in Python, SQL, Power BI
LinkedIn: https://www.linkedin.com/in/milan-kumar-suthar-3b95b0281
