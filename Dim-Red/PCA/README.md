# 🧪 PCA of Gene Expression Data

This notebook demonstrates how Principal Component Analysis (PCA) can be used to reduce high-dimensional gene expression data to just two components for easy visualization and pattern discovery.

## 📁 Dataset Used
A synthetic `gene_expression_dataset.csv` with the following structure:
- `Patient_ID`: Unique identifier for each patient
- `Subtype`: Diagnostic label (e.g., A, B, C)
- Gene expression columns (G1, G2, ..., Gn)

## 🔬 Objective
- Reduce high-dimensional gene expression data to 2D using PCA
- Visualize clusters based on subtypes
- Identify variance captured by each principal component

## 📊 Tools & Libraries
- `pandas` for data manipulation
- `scikit-learn` for PCA implementation
- `plotly.express` for interactive plotting

## 🧠 Key Takeaways
- PCA helps simplify complex gene expression data while preserving variance
- Visual clusters may indicate biological subtypes
- This forms the foundation for more advanced techniques like t-SNE and UMAP

## 📌 Next Steps
- Compare PCA results with t-SNE and UMAP
- Explore feature importance and gene loadings
- Apply dimensionality reduction to real-world datasets (e.g., cancer RNA-seq)

---

> ⚠️ Note: This notebook is part of a larger portfolio on AI/ML in Bioinformatics.
