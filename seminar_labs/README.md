## Workshop/Seminar Labs

This folder contains the code, data, and results for the workshop/seminar labs of the "Introduction to Bioinformatics" course.

The detailed descriptions and instructions for these labs are located on the [course website](https://www.etssa.space/dry-lab)

## Lab Descriptions

### Level 0: Sequence Identification and Clustering

   **Description:** This lab focuses on identifying unknown DNA sequences using BLAST and understanding basic clustering.

#### Task 1: Unknown Sequence Identification with BLAST
   **Background:**  Mitochondrial barcoding was used to analyze samples collected in Oʻahu. \
   **Action:** Use the web version of BLAST to identify the species associated with the provided MT-COI sequences.

#### Task 2: GenBank Sequence Search and Clustering
   **Background:** In May 2022, the first draft genome of a monkeypox virus isolate was obtained. \
   **Action:** Explore GenBank using the provided monkeypox sequence and cluster the obtained sequences

#### Task 3: Alpine Mystery
**Background:** In 1991, mummified remains were found in the Alps.\
**Action:** Analyze the provided mitochondrial genome sequence to learn about the identity and history of the person.

### Level 1: Open Reading Frame (ORF) Identification

   **Objective:** Develop a script to identify potential open reading frames (ORFs) in nucleotide sequences. \
    **Action:**
1.  Implement a script that identifies start codons, reads in triplets until stop codons are found, generating a list of nucleotide sequences potentially coding for proteins or short peptides
2.  (Optional) Translate these sequences into amino acid sequences. Note that the genetic code may vary between organisms (including nuclear and mitochondrial codes).


### Level 4: Phylogenetic Analysis of Protein-Coding Genes

   **Objective:** To reconstruct the phylogenetic relationships of a protein-coding gene by identifying orthologs, performing multiple sequence alignment, and constructing a phylogenetic tree.

**Workflow:**
1. **Ortholog Identification:** Download the amino acid sequence of the target gene from Ensembl. Use tBLASTn to find orthologs in 11 genomes.
2. **Multiple Sequence Alignment:** Perform a multiple sequence alignment using MAFFT (E-INS-i).
3. **Format Conversion:** Convert the alignment to .nexus format.
4. **Phylogenetic Tree Reconstruction:** Reconstruct a phylogenetic tree using MrBayes.
5. Tree Visualization:** Visualize the tree using FigTree or iTOL.

### Level 5: Phylogenetic Analysis of Non-Coding Sequences

**Objective:** To reconstruct the phylogenetic relationships of a non-coding sequence by identifying orthologs, performing multiple sequence alignment, and constructing a phylogenetic tree.

**Workflow:**
1. **Ortholog Identification:** Download the nucleotide sequence of the target non-coding sequence from Ensembl. Use HMMER and BioMart to find orthologs in 11 genomes.
2. **Multiple Sequence Alignment:** Perform a multiple sequence alignment using MAFFT (E-INS-i).
3. **Format Conversion:** Convert the alignment to .nexus format.
4. **Phylogenetic Tree Reconstruction:** Reconstruct a phylogenetic tree using MrBayes.
5. **Tree Visualization:** Visualize the tree using FigTree or Archeopteryx.

### Level 15: SARS-CoV-2 Genetic Diversity Analysis

   **Overview:** This lab focuses on analyzing the genetic diversity of SARS-CoV-2 by building a phylogeny of the S-protein gene. \
   **Data:** Sequences of SARS-CoV-2 S-protein (or other) are used to assess the genetic diversity \
    **Workflow:**
1. Pairwise alignment of the sequences with BLASTn
2. Phylogentic tree reconstruction

### Level 16: Phylogenetic Analysis and Expression of Non-Coding Sequences

**Overview:** This lab focuses on phylogenetic analysis of non-coding sequences and evaluation of their expression in normal and pathological tissues \
**Data:** Expression data from pathological and normal tissues. \
**Workflow:**
1. Phylogentic analysis
2. Evaluation of expression patterns in normal and pathological tissues.
