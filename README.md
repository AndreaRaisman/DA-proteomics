**Disease Atlas's proteomics analysis**

**Description**: This is a pipeline to process and analyze the proteomics data obtained with mass spectrometry from ca. 3000 samples from patients with a variety of diseases. 
This project is taking place within the Human Protein Atlas. The objective is to find disease biomarkers that can improve clinical applications.
The samples were distributed into 96-well plates, which included in-house plasma samples for quality control - including batch effect analysis.
This information was used to make decisions about how the data should be handled.
After that, each plate was first QC'd on its own, filtering out low-quality peptides and samples. 
The data from all plates was then merged and pre-processed before starting the biomarker discovery pipeline.

**Table of Contents**
- Batch pre-analysis
- In-house batch correction
- Pre-processing
- PCA, UMAP & tSNE
- Hierarchical clustering
- Differential Expression Analysis

Requirements: The clinical and mass spectrometry data sets are needed to run any part of the pipeline. All libraries needed for each step are listed at the beginning. All packages must be installed beforehand.

**Usage**
This is an comprehensive, almost textbook-like analytical pipeline. It includes steps that are not necessary to get the final results, but help to understand the structure and behavior of the data and to make decisions about it.
It can work as a guide for other proteomics-based biomarker discovery projects, but it is completely tailored to the data sets that were being handled and which are not necessarily widespread in their format.

**Features**
This project includes code for histograms and boxplots to visualize data distribution, different dimensionality reduction and clustering methods for better insight into the data's patterns and differential expression analysis. 
It also includes explanations about the options and decisions that can be made at each step: data normalization and filtering, batch effect correction, data imputation, distance (correlation) methods for clustering, linear and non-linear dimensionality reduction, etc. 
Thus, it can be used as a guide for other proteomics projects that use similar datas and have to face similar issues.

The code is public and can be used without further permision, as long as it is **correctly cited**:
Villanueva-Raisman, A. (2023). Disease Atlas's proteomics analysis (Version 1.0) [Source code repository]. Github. https://github.com/AndreaRaisman/DA-proteomic

Contact: andrea.villanueva@scilifelab.se


