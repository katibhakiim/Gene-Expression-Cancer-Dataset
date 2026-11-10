# Gene Expression Cancer RNA-Seq Dataset

A dataset exploration project using gene expression data from five cancer types, with a focus on understanding high-dimensional biological data and preparing it for Principal Component Analysis (PCA).

## 1. Dataset Overview

The Gene Expression Cancer RNA-Seq dataset is a collection of gene expression measurements extracted from the RNA-Seq (HiSeq) Pan-Cancer (PANCAN) dataset.

The data represents gene expression levels from samples belonging to five different cancer types.

### Dataset Information

| Property | Description |
|---|---|
| Dataset Name | Gene Expression Cancer RNA-Seq |
| Domain | Bioinformatics |
| Data Source | TCGA Pan-Cancer (PANCAN) |
| Technology | Illumina HiSeq |
| Samples | 801 |
| Features | 20,531 |
| Classes | 5 |
| Feature Type | Real-valued |
| Missing Values | None reported |
| Main Tasks | Classification and Clustering |

## 2. Cancer Types

The dataset contains five cancer types:

| Label | Cancer Type |
|---|---|
| BRCA | Breast Invasive Carcinoma |
| KIRC | Kidney Renal Clear Cell Carcinoma |
| COAD | Colon Adenocarcinoma |
| LUAD | Lung Adenocarcinoma |
| PRAD | Prostate Adenocarcinoma |

## 3. Dataset Files

The dataset consists of two main CSV files:

### data.csv

Contains gene expression measurements.

- Rows represent biological samples.
- Columns represent gene expression features.
- Values represent measured gene expression levels.

### labels.csv

Contains the cancer type associated with each sample.

- Each sample has an associated cancer label.
- Labels identify the five cancer types.

The two files represent the features (X) and target labels (y) used in machine learning workflows.

## 4. Project Structure

```text
Gene-Expression-Cancer-Dataset/
│
├── README.md
├── LICENSE
│
├── data/
│   ├── data.csv
│   └── labels.csv
│
├── notebooks/
│   └── 01_Dataset_Exploration.ipynb
│
├── results/
│
└── requirements.txt
```

## 5. Project Objectives

1. Explore and understand the dataset structure.
2. Identify samples, features, and cancer labels.
3. Analyze gene expression statistics.
4. Investigate the distribution of cancer types.
5. Check data quality and missing values.
6. Prepare the dataset for dimensionality reduction using PCA.

## 6. Technologies

- Python 3.12
- Jupyter Notebook
- os
- Pandas
- NumPy
- Matplotlib
- seaborn
- Scikit-learn

## 7. Getting Started

Clone the repository:

```bash
git clone https://github.com/katibhakiim/Gene-Expression-Cancer-Dataset.git
```

Navigate to the project directory:

```bash
cd Gene-Expression-Cancer-Dataset
```

Install the dependencies:

```bash
pip install -r requirements.txt
```

The dataset files are available in the `data/` directory.

## 8. Dataset Sources

- [Kaggle - Gene Expression Cancer RNA-Seq](https://www.kaggle.com/datasets/debatreyadas/gene-expression-cancer-rna-seq)
- [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/401/gene+expression+cancer+rna+seq)

Original Dataset Citation:

Fiorini, S. (2016). Gene Expression Cancer RNA-Seq. UCI Machine Learning Repository.

DOI: https://doi.org/10.24432/C5R88H

## 9. Licenses

**Project Code:** Apache License 2.0.

**Original Dataset:** Creative Commons Attribution 4.0 International (CC BY 4.0).

Dataset attribution: Samuele Fiorini (2016), UCI Machine Learning Repository.

Please refer to the original dataset source for attribution and licensing details.

## 10. Disclaimer

This repository is intended for educational and research purposes.

The dataset is provided for statistical analysis, bioinformatics exploration, and machine learning experimentation. It is not intended for medical diagnosis or clinical decision-making.
