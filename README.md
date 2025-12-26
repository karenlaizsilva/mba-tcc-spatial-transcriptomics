Spatial Transcriptomics Analysis of Spermatogenesis
This repository contains the data analysis pipeline developed for my MBA dissertation in Data Science and Analytics (USP/ESALQ). The project focuses on the extraction and processing of Visium HD (10x Genomics) data to map gene expression within testicular samples.

Project Overview
The primary goal of this research is to identify spatial patterns and cellular domains during the spermatogenesis process. I employ Machine Learning techniques for nuclei segmentation and transcriptional profile clustering, enabling a high-resolution view of tissue organization.

Technologies and Tools
Languages: Python and R.

Extraction Pipeline: Space Ranger (10x Genomics).

Infrastructure: Google Cloud Platform (GCP) / USP Cloud.

Data Analysis: Scanpy (Python) / Seurat (R).

Computer Vision: ML models for Nuclei Segmentation.

Pipeline Structure
Preprocessing: Raw data extraction (FASTQ) and image alignment via Space Ranger.

Segmentation: Identifying cellular boundaries to convert spot-based data into single-cell resolution.

Analytics: Dimensionality reduction (UMAP/t-SNE) and Clustering for cell-type discovery.

Validation: Comparative analysis of manual processing vs. automated 10x Cloud results.

How to Reproduce
Note: Raw data is proprietary and protected under research ethics. This repository focuses on the methodology and analysis scripts.

Set up a Linux environment (preferably cloud-based).

Install Space Ranger following the official 10x Genomics guides.

Execute the run_spaceranger.sh script located in the /scripts folder.