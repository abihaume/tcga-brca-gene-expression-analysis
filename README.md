# 🧬 Cancer Gene Expression Analysis Using TCGA-BRCA RNA-seq Data

## End-to-End Bioinformatics Pipeline Using Databricks and Python

### 👩‍💻 Author

**Ume Abiha**

---

# 📖 Project Overview

This project presents an end-to-end bioinformatics workflow for analyzing breast cancer RNA-seq data obtained from **The Cancer Genome Atlas (TCGA-BRCA)**. The objective was to identify transcriptomic differences between tumor and normal breast tissue using statistical analysis, unsupervised learning, and supervised machine learning techniques.

The complete workflow was developed in **Databricks** using **Python** and demonstrates common approaches used in cancer genomics and bioinformatics research.

---

# 🎯 Project Objectives

* Load and preprocess TCGA-BRCA RNA-seq data
* Integrate clinical metadata
* Annotate tumor and normal tissue samples
* Perform exploratory data analysis
* Conduct differential gene expression analysis
* Visualize results using Volcano Plots
* Reduce dimensionality using Principal Component Analysis (PCA)
* Cluster samples using K-Means
* Build a Logistic Regression classifier for tumor prediction

---

# 📂 Dataset

**Source:** The Cancer Genome Atlas (TCGA-BRCA)

**Dataset Summary**

* 20,530 genes analyzed
* 1,211 breast tissue samples
* RNA-seq gene expression data
* Clinical metadata including age, receptor status, tumor stage, and survival information

---

# 🛠 Technologies Used

* Python
* Databricks
* pandas
* NumPy
* SciPy
* scikit-learn
* Matplotlib

---

# 🔬 Analysis Workflow

1. Data Loading
2. Data Cleaning and Preprocessing
3. Clinical Metadata Integration
4. Sample Annotation (Tumor vs Normal)
5. Exploratory Data Analysis
6. Differential Gene Expression Analysis
7. Volcano Plot Visualization
8. Principal Component Analysis (PCA)
9. K-Means Clustering
10. Logistic Regression Classification

---

# 📊 Key Results

- Processed **1,211** TCGA-BRCA samples
- Analyzed **20,530** genes
- Identified significantly differentially expressed genes between tumor and normal tissue
- PCA demonstrated clear separation between tumor and normal samples
- K-Means clustering identified biologically meaningful sample groups
- Logistic Regression achieved:
  - **Accuracy:** 98.35%
  - **Precision (Tumor):** 0.99
  - **Recall (Tumor):** 0.99

---

# 📁 Repository Structure

# 📁 Repository Structure

```text
tcga-brca-gene-expression-analysis/
│
├── README.md
├── LICENSE
├── .gitignore
│
└── notebook/
    ├── TCGA_BRCA_Data_Analysis.ipynb
    ├── TCGA_BRCA_Data_Analysis.html
    ├── figures/
    │   ├── volcano_plot.png
    │   ├── pca_plot.png
    │   ├── kmeans_plot.png
    │   └── confusion_matrix.png
    │
    └── results/
        ├── dge_results.csv
        └── pca_results.csv
```

---

# 🚀 Future Improvements

* Apply False Discovery Rate (FDR) correction
* Perform Gene Ontology (GO) enrichment analysis
* Explore KEGG pathway enrichment
* Compare additional machine learning models such as Random Forest and XGBoost
* Investigate survival prediction using clinical outcomes

---

# 📜 License

This project is licensed under the MIT License.
