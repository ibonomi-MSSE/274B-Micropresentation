# 274B-Micropresentation-Spectral-Clustering
#### By: Isabella Bonomi, Anna Devlen, Cris Zong, Jahnavi Gandhi

This repostory contains an ipynb file explaining how to implement spectral clustering for single cell RNA sequencing data.

### What is Spectral Clustering?
Spectral clustering is a graph partitioning technique where data points are treated as nodes of a graph and nodes are mapped to a lower dimensional space to form clusters. The main goal is to find connected-components and cluster data that is connected based on relationships and connectivity using eigenvalues derived from its similarity matrix. Spectral clustering has many applications in molecular science, one of which will be explored in this repository on single cell RNA requencing data.

### Instructions
The ipynb file can be run in colab. For this walk-through, you will need to download the Series Matrix File (.h5) file, which is included in the repository for convenience (GSM3169075_filtered_gene_bc_matrices_h5.h5). This file was downloaded from Genome Expression Omnibus (an NCBI database) and can be found by searching the ID GSE115189, as shown in the link below. This dataset contains single-cell RNA sequencing information for peripheral blood mononuclear cells from healthy human donor.

https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE115189

Once you have uploaded the h5 matrix file, the colab is set up with decriptive steps on how to load in the data, perform some initial filtering of the data, build a spectral clustering algorithm, and map the clusters to analyze different cell types based on gene expression.
