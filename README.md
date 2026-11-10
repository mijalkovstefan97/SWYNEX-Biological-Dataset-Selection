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
