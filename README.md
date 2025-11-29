# 274B-Micropresentation-Spectral-Clustering

This repostory contains an ipynb file explaining how to implement spectral clustering for single cell RNA sequencing data.

### What is Spectral Clustering?
Spectral clustering is a graph partitioning technique where data points are treated as nodes of a graph and nodes are mapped to a lower dimensional space to form clusters. The main goal is to find connected-components and cluster data that is connected based on relationships and connectivity using eigenvalues derived from its similarity matrix. Spectral clustering has many applications in molecular science. This repository explores how to use spectral clustering on single cell RNA requencing data.

### Instructions
The ipynb file can be run in colab. For this walk-through, you will need to download the Series Matrix File (.h5) file from the NCBI database for Query DataSets for GSE115189 (peripheral blood mononuclear cells from healthy human donor).
(GSM3169075_filtered_gene_bc_matrices_h5.h5) found in the link below:
https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE115189

You will need to upload the matrix file into the colab space.
