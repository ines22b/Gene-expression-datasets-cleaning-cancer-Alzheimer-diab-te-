
# Gene Expression Datasets Cleaning – Cancer, Alzheimer & Diabetes

> Transcriptomic data preprocessing pipelines for GEO and TCGA datasets focused on cancer, Alzheimer’s, and diabetes. Includes quality control, normalization, and preparation of gene expression matrices for bioinformatics and statistical analyses.

## 🧬 Overview

This project provides a set of Jupyter Notebooks dedicated to the cleaning and preprocessing of transcriptomic datasets across multiple diseases. It supports datasets from both GEO (NCBI) and TCGA (Pan-Cancer), including:

- Cancer datasets (e.g. TCGA Pan-Cancer RNA-Seq)
- Alzheimer datasets (e.g. GSE131617)
- Diabetes datasets (e.g. GSE88794)

## ⚙️ Main Tasks

- Web scraping (for GEO-based datasets)
- Removal of duplicated or low-quality entries
- Filtering of genes with no or low expression
- Log transformation (when appropriate)
- Label cleaning and formatting
- Saving of cleaned datasets in `.csv` or `.pkl` format

## 📁 Included Notebooks

- `GSE2109_series_matrix_Preprocessing.ipynb` (Pan-Cancer)
- `EBPlusPlusAdjustPANCAN_IlluminaHiSeq_RNASeqV2.geneExp_Preprocessing.ipynb` (TCGA RNA-Seq)
- `GSE131617-GPL5175_series_matrix_Preprocessing.ipynb` (Alzheimer)
- `GSE88794_series_matrix_Preprocessing.ipynb` (Diabetes)

## 📦 Installation

1. Clone the repository:
```bash
git clone https://github.com/ines22b/gene-expression-datasets-cleaning.git
cd gene-expression-datasets-cleaning
```

2.Launch the notebooks:
```bash
jupyter notebook
```

## 📌 Notes

- All notebooks are fully documented and reusable.
- Output files are formatted for compatibility with R, Python, and other bioinformatics pipelines.
- Easily adaptable to other GEO/TCGA datasets.

## 🙋 Author

Developed by [Inas Boudjeda]. Contributions and collaborations are welcome.
