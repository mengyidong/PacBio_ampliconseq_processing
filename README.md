# PacBio 16S and ITS Processing Pipeline

This repository contains the PacBio 16S and ITS sequence-processing workflow used for **PreMiEr Project in built-environmental microbiome**.

## Overview

This workflow was used to process PacBio amplicon sequencing data for microbial community analysis, including:
- primer removal
- quality filtering
- error learning
- denoising
- sequence table generation

## Attribution

This workflow was **adapted from Benjamin Callahan’s DADA2 + PacBio: Fecal Samples** and further modified for this project by **Mengyi Dong** and **Eva Kim**.

Original workflow:  
(https://benjjneb.github.io/LRASManuscript/LRASms_fecal.html)

If you use this repository, please cite:
1. Benjamin Callahan’s original PacBio workflow/repository
2. this repository
3. relevant software packages used in the analysis (for example, DADA2)

## Contributors

- Mengyi Dong
- Eva Kim

## Version used for manuscript

The version used for the analyses reported in **[manuscript title]** is:
- Release/tag: `v1.0-manuscript`

This release reflects the exact code used for the manuscript analyses. Later improvements may be incorporated in future releases.

## Requirements

- R
- dada2
- Qiime 2

## Contact

Mengyi Dong  
