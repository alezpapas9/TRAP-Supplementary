# TRAP-Supplementary

This repository contains supplementary datasets and files supporting the MSc dissertation:  
**"Large-Scale Phylogenetic and Structural Analysis of TRAP Proteins: Evolutionary Insights and Bioengineering Potential"**  


## Overview
The files in this repository include curated TRAP protein sequence datasets, alignments, and input files used for phylogenetic analyses.  
They provide transparency and reproducibility for the analyses described in the dissertation.

## Contents

- **Supplementary File 1.**  
  NEXUS alignment file (`TRAP_Bayer_analysis_nexus_file`) with an embedded MrBayes block specifying all model parameters.  
  → Used for Bayesian phylogenetic inference in MrBayes.  

- **Supplementary File 2.**  
  RAxML manual (v8.2.X).  
  → Reference guide followed for maximum-likelihood phylogenetic inference.  

- **Supplementary File 3.**  
  Trimmed multiple sequence alignment in PHYLIP format (`TRAP_PHYLIP`).  
  → Input file used in RAxML and ModelTest-NG analyses.  

- **Supplementary File 4.**  
  ModelTest-NG manual (v1.0.0).  
  → Reference guide followed for model testing and evaluation.  

- **Supplementary File 5.**  
  Final aligned, trimmed, and curated dataset of TRAP homologs in FASTA format  
  ([TRAP_final_trimmed_curated_alignment.fasta](https://github.com/alezpapas9/TRAP-Supplementary/blob/fc2ed2ac270ab43c5af6febf20cf51e928dad921/TRAP_final_trimmed_curated_alignment.fasta)).  
  → Primary dataset used for downstream maximum-likelihood and model-based phylogenetic inference in IQ-TREE.  

## Usage
These files can be used to reproduce the phylogenetic analyses described in the dissertation.  
For example:
- The PHYLIP files can be used as input for **RAxML**, **IQ-TREE**, or **ModelTest-NG**.
- The FASTA file can be used as input for **MrBayes** or other phylogenetic tools that are compatible with FASTA.  
- The NEXUS file contains pre-configured MrBayes commands for direct use.  
- Manuals are provided for methodological reference.
