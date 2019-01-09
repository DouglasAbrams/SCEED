# SCEED
##### A computational method to aid the design and analysis of single cell RNA-seq experiments for cell type identification

### Background

The advent of single cell RNA sequencing (scRNA-seq) enabled researchers to study transcriptomic activity within individual cells and identify inherent cell types in the sample. Although numerous computational tools have been developed to analyze single cell transcriptomes, there are no published studies and analytical packages available to guide experimental design and to devise suitable analysis procedure for cell type identification. 

### Results

We have developed an empirical methodology to address this important gap in single cell experimental design and analysis into an easy-to-use tool called SCEED (Single Cell Empirical Experimental Design and analysis). With SCEED, user can choose a variety of combinations of tools for analysis, conduct performance analysis of analytical procedures and choose the best procedure, and estimate sample size (number of cells to be profiled) required for a given analytical procedure at varying levels of cell type rarity and other experimental parameters. Using SCEED, we examined 3 single cell algorithms using 48 simulated single cell datasets that were generated for varying number of cell types and their proportions, number of genes expressed per cell, number of marker genes and their fold change, and number of single cells successfully profiled in the experiment. 

### Conclusions

Based on our study, we found that when marker genes are expressed at fold change of 4 or more than the rest of the genes, either Seurat or Simlr algorithm can be used to analyze single cell dataset for any number of single cells isolated (minimum 1000 single cells were tested). However, when marker genes are expected to be only up to fC 2 upregulated, choice of the single cell algorithm is dependent on the number of single cells isolated and proportion of rare cell type to be identified. In conclusion, our work allows the assessment of various single cell methods and also aids in examining the single cell experimental design.


