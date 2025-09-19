# RNA-seq Analysis Description and Details
## Overview
This project performs bulk RNA-seq analysis from raw fastq files through differential expression and enrichment analysis.

## Tools and Versions
- FastQC v0.11.9
- STAR aligner v2.7.9a
- DESeq2 v1.38.3

## Workflow
1. Quality control using FastQC
2. Read alignment with STAR
3. Count matrix generation with featureCounts
4. Differential expression analysis using DESeq2
5. Functional enrichment and visualization with clusterProfiler

## Key Outputs
- PCA and heatmaps for QC and exploratory analysis
- Volcano plots for differentially expressed genes
- Tables of normalized counts and DE genes

## Usage
Run the analysis script as follows:
Rscript run_rnaseq_analysis.R --input path/to/fastq --output results/
