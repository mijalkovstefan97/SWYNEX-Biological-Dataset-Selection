# SWYNEX — Biological Dataset Selection

**Bioinformatics Internship | Task 1**

## 1. Project Overview

This project was developed as part of the SWYNEX Technologies Bioinformatics Internship.

The objective of this task is to select, examine, and document a publicly available biological dataset, including its source, structure, size, biological relevance, and potential research applications.

The selected dataset is **GSE19804**, a publicly available gene expression dataset from the National Center for Biotechnology Information (NCBI) Gene Expression Omnibus (GEO).

The study investigates gene expression patterns in lung cancer among women in Taiwan who have never smoked.

## 2. Dataset Information

- **Dataset accession:** GSE19804
- **Dataset title:** Genome-wide screening of transcriptional modulation in non-smoking female lung cancer in Taiwan
- **Data repository:** NCBI Gene Expression Omnibus (GEO)
- **Organism:** Homo sapiens
- **Technology:** Affymetrix DNA microarray
- **Platform:** GPL570 — Human Genome U133 Plus 2.0 Array
- **Total samples:** 120
- **Tumor tissue samples:** 60
- **Matched non-tumor tissue samples:** 60
- **Study design:** Paired tumor and non-tumor tissue comparison

**Official dataset URL:** https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE19804

## 3. Dataset Size and Structure

The dataset contains gene expression measurements from 120 lung tissue samples, including 60 tumor samples and 60 matched non-tumor samples.

The processed data was downloaded from NCBI GEO as a compressed Series Matrix file.

- **Processed file:** GSE19804_series_matrix.txt.gz
- **Compressed file size:** 21.53 MB
- **Raw data archive:** GSE19804_RAW.tar (602.7 MB)
- **Expression measurements:** 54,675 probe sets
- **Sample columns:** 120
- **Missing values:** 0

Each row represents a microarray probe set, while each sample column contains its corresponding gene expression measurements. A probe set does not necessarily represent a unique gene.

The samples are organized into 60 matched pairs, allowing gene expression levels to be compared between tumor and non-tumor tissues from the same patient.

## 4. Research Question and Objectives

### Research Question

Which genes show different expression levels between lung tumor tissues and matched non-tumor tissues in women in Taiwan who have never smoked?

### Research Objectives

The main objectives of a potential analysis of this dataset are:

- To compare gene expression levels between 60 tumor samples and their matched non-tumor samples.
- To identify genes that may show differences in expression between the two tissue types.
- To explore how these differences could contribute to a better understanding of lung cancer at the molecular level.

The paired study design allows tumor and non-tumor samples from the same patient to be compared, helping to reduce the influence of individual differences.

At this stage, the project focuses on selecting and documenting the dataset. The research question provides a starting point for future analysis.

## 5. Dataset Relevance and Limitations

### Why This Dataset Was Selected

I selected GSE19804 because it provides publicly available gene expression data that can be used to study molecular differences between lung tumor and non-tumor tissues.

One of its main advantages is the paired study design. Each tumor sample has a corresponding non-tumor sample from the same patient, making it possible to compare gene expression while reducing the influence of differences between individuals.

The dataset is also suitable for further bioinformatics analysis using Python, including data exploration, statistical comparisons, and visualization.

### Dataset Limitations

There are several limitations to consider:

- **Study population:** The dataset focuses on women in Taiwan who have never smoked. Therefore, the findings may not apply to all lung cancer patients.
- **Sample size:** Although the dataset contains 120 tissue samples, these come from 60 patients. Larger and more diverse datasets would be useful for validating future findings.
- **Microarray technology:** The measurements are based on microarray probe sets, which do not always correspond directly to individual genes. Additional annotation is needed for gene-level analysis.
- **Interpretation:** Differences in gene expression may be associated with lung cancer, but they do not necessarily indicate that the affected genes cause the disease.

These limitations should be considered when interpreting any future results obtained from this dataset.

## 6. Dataset Source and References

### Dataset Source

The GSE19804 dataset is publicly available through the NCBI Gene Expression Omnibus (GEO), a repository for gene expression and other functional genomics data.

The dataset was submitted by researchers from National Taiwan University and is available for research and educational purposes.

- **Dataset:** [GSE19804 — NCBI GEO](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE19804)
- **Microarray platform:** [GPL570 — Affymetrix Human Genome U133 Plus 2.0 Array](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GPL570)
- **Processed data:** [GSE19804 Series Matrix files](https://ftp.ncbi.nlm.nih.gov/geo/series/GSE19nnn/GSE19804/matrix/)

### Original Research Publication

Lu, T.-P., et al. (2010). Identification of a novel biomarker, SEMA5A, for non-small cell lung carcinoma in nonsmoking women. *Cancer Epidemiology, Biomarkers & Prevention, 19*(10), 2590–2597.

**DOI:** https://doi.org/10.1158/1055-9965.EPI-10-0332

**PubMed:** https://pubmed.ncbi.nlm.nih.gov/20802022/

The publication provides scientific background for the dataset and describes the comparison of gene expression between lung tumor and matched non-tumor tissues.
