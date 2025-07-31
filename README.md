# scRNA_toolkit

**scRNA_toolkit** is a modular and user-friendly collection of Python scripts and Jupyter notebooks designed to streamline **single-cell RNA sequencing (scRNA-seq)** analysis. Built on top of **Scanpy**, this toolkit provides end-to-end functionality for preprocessing, clustering, visualization, and differential gene expression analysis in single-cell datasets.

---

## 📌 Features

- 🔬 Quality control and filtering  
- 🧬 Normalization, scaling, and highly variable gene selection  
- 🧪 Dimensionality reduction (PCA, UMAP, t-SNE)  
- 🔍 Clustering and marker gene identification  
- 📈 Differential expression and pathway enrichment  
- 🧭 Trajectory inference (Monocle3/Harmony compatible)  
- 🖼️ Publication-ready visualizations  

---

## 🧰 Requirements

- Python ≥ 3.8  
- [`scanpy`](https://scanpy.readthedocs.io/)  
- `anndata`, `matplotlib`, `seaborn`, `pandas`, `scikit-learn`  
- Optional: `harmonypy`, `scrublet`, `pySCENIC`, `cellrank`

To install dependencies:

```bash
pip install -r requirements.txt
