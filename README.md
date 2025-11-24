# Clustering Lab – Hierarchical & DBSCAN on Wine Dataset

## 📌 Purpose of the Lab
The purpose of this lab was to explore unsupervised clustering techniques using the Wine dataset from the `sklearn` library. The lab focused on applying **Hierarchical Clustering** and **DBSCAN** to understand how these algorithms group data based on feature similarity, and how parameter choices impact clustering behavior. The activity emphasized visualization, evaluation metrics, and interpretation of cluster structures.

---

## 🔍 Key Insights from Clustering Results

### ✅ Hierarchical Clustering
- Produced meaningful separation when using **n_clusters = 3**, aligning with the three known wine classes.
- The **dendrogram visualization** clearly showed where natural cluster boundaries emerged.
- Standardization significantly improved structure visibility.
- Cluster assignments demonstrated how samples merge at increasing distance thresholds.

### ✅ DBSCAN Clustering
- Cluster outcomes were highly sensitive to **eps** and **min_samples** settings.
- Certain parameter combinations produced multiple clusters, while others labeled many points as **noise**.
- DBSCAN identified sample density patterns that Hierarchical Clustering could not.
- Evaluation metrics provided quantitative assessment:
  - **Silhouette Score** helped measure internal cohesion.
  - **Homogeneity** and **Completeness** illustrated alignment with true wine categories.

### 📊 Overall Interpretation
- Hierarchical Clustering provided **better interpretability** and alignment with expected structure.
- DBSCAN demonstrated **flexibility** and **noise detection**, but required more tuning.

---

## ⚠️ Challenges and Decisions Made
✅ Choosing meaningful values for **n_clusters** required observing the dendrogram.  
✅ Selecting DBSCAN parameters involved iterative experimentation due to sensitivity.  
✅ Visualizations needed feature scaling to avoid distortion.  
✅ Interpreting metrics required understanding how noise affects scoring.  

---

## 📁 Files Included
- `lab5.ipynb` – Full notebook with all steps
- `README.md` – Summary and reflection for assignment submission

