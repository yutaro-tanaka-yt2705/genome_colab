# genome_colab

Pipeline for obtaining genome files (FASTA/FASTQ) and preparing them for analysis on Google Colab.

Problems:
- Preparing Genome files for analysis can be a confusing minefield of utilizing different packages for each step in filtering, sampling, and the raw genome sequences.
- Files provided in public are often raw sequenced data in FASTA/Q format, and VCF (Variant Call Files) need to be prepared to for genomic analysis.
- Many of the packages currently used are designed for HPC (High-Performance Clusters) and High RAM/GPU availability is assumed. 

Aims : 
- This script allows a user to download files from ENA (EMBL-EBI) and other public databases, and prepare a VCF file ready for analysis solely on Google Colab, a Jupyter Notebook environment. 
  - This is not intended to be the most efficient method, but a convenient and accessible alternative to many current methods/

Status : In Development. (as of June 13th 2022)

Next Steps: 
- Eventually, a terminal/command line package will be developed for end-to-end analysis of WGS files. 


A Flowchart for SNP discovery in DNA (Broad Institute, Genome Analysis Toolkit)
![gatk](https://user-images.githubusercontent.com/64746654/173368634-f5a5c49c-1fca-4305-8ed0-c1da95d8af5a.png)
