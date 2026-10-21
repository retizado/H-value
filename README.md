# TCGA Clinical & Biomarker Data Analysis

This repository contains clinical and genomic datasets retrieved from **TCGA (The Cancer Genome Atlas)** via the **UCSC Xena** platform, along with auxiliary files and scripts for processing transcriptomic data and H-value scores.

---

## 📁 Repository Structure

| File / Folder | Description |
| :--- | :--- |
| **`COAD.csv`** | Expression/clinical data for Colon Adenocarcinoma (TCGA-COAD). |
| **`KIRC.csv`** | Data for Kidney Renal Clear Cell Carcinoma (TCGA-KIRC). |
| **`LIHC.csv`** | Data for Liver Hepatocellular Carcinoma (TCGA-LIHC). |
| **`LUAD.csv`** | Data for Lung Adenocarcinoma (TCGA-LUAD). |
| **`OV.csv`** | Data for Ovarian Serous Cystadenocarcinoma (TCGA-OV). |
| **`STAD.csv`** | Data for Stomach Adenocarcinoma (TCGA-STAD). |
| **`datos_clin_st.xlsx`** | Excel file containing processed/standardized clinical variables. |
| **`datos_clin_tn.xlsx`** | Excel file containing complementary clinical data (e.g., TNM staging / Normal vs. Tumor tissue). |
| **`Download usc xena data`** | Script or instructions for fetching data from UCSC Xena. |
| **`H-value data example`** | Example dataset/script structured for calculating or evaluating H-value scores. |

---

## 📊 Data Source & Compliance

The genomic and clinical data in this repository were retrieved via **UCSC Xena Browser**:
* **Original Source:** The Cancer Genome Atlas (TCGA) — National Cancer Institute (NCI) / GDC.
* **Access Level:** Open Access, fully anonymized non-identifiable public data.

---

## 🛠️ Setup & Requirements

To work with the CSV and Excel files in this repository, the following environment dependencies are recommended:

### Python
```bash
pip install pandas openpyxl


If you use this dataset or code, please acknowledge the original TCGA program and UCSC Xena resource:

Goldman, M. J., et al. Visualizing and analyzing TCGA data with Xena hub. Nature Biotechnology 38, 675–678 (2020).

National Cancer Institute Genomic Data Commons (GDC) TCGA Program.
