# Lecture-Based Labs

This folder contains the code, data, and results for the lecture-based labs of the "Introduction to Bioinformatics" course.

## Labs Descriptions

### Lab 1: Working with Genetic Databases

   **Description:** This lab focuses on utilizing the NCBI search engine for retrieving and exploring genetic information \
   **Details:**  All task requirements and corresponding solutions are included in the lab documentation.

### Lab 2: Reference-Based Genome Assembly from Raw Reads

   **Goal:** Investigate genomic variations (SNPs and Indels) that arise and become fixed in an *E. coli* population after thousands of generations in a low-glucose environment. \
   **Methodology:**  We followed the pipeline and instructions provided by [Data Carpentry](https://datacarpentry.github.io/wrangling-genomics/). The linked resource contains comprehensive information on the entire workflow. This section highlights key insights and learnings from the experiment. 

### Lab 3: Phylogenetic Tree Construction Based on Genetic Distances

   **Objective:** Build phylogenetic trees using the PHYLIP software.\
   **Data:**  We used 11 or more Banana streak virus strain variants downloaded from the [NCBI database](https://www.ncbi.nlm.nih.gov/genomes/GenomesGroup.cgi?taxid=10239&opt=Virus).\
   **Workflow:**
1.  Global alignment of the variable-length viral genomes using MAFFT (or similar).
2.  Calculation of a distance matrix between the viral strains.
3.  Construction of an unrooted phylogenetic tree using the distance matrix.

### Lab 4: Cluster Analysis

   **Task:** For a given set of three-dimensional data:
1. Create a visual representation of the data (use your creativity!).
2. Perform k-means clustering for different values of *k* (k = 2, 3, 4, 5), visualizing each cluster and its centroid.
3. Apply hierarchical clustering and compare the results with those from k-means.


### Lab 5: Application of Cluster Analysis for GWAS and Admixture Tasks (Population Analysis)

   **Overview:** This lab explores the practical application of clustering techniques in bioinformatics.

#### Tasks:
1.  **GWAS Analysis with `plink`:** Identify genetic loci associated with phenotypic traits using test data and `plink`.
2.  **Population Analysis with `admixture`:** Identify genetic clusters based on genotype similarity using test data and `admixture`. Determine the optimal K value and visualize the results.

## Tools

*   NCBI Search Engine
*   Data Carpentry Genomics Pipeline
*   PHYLIP
*   MAFFT (or similar)
*   `plink`
*   `admixture`
*   `R` (for visualization in Lab 5)

