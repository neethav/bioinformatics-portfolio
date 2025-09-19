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
This project provides two ways to run the RNA-seq analysis workflow:

1. Running Separate Scripts (Step-by-step)
You can run each step independently using the provided scripts in order:

#Quality Control
#Run FastQC:
scripts/fastqc.sh

#Read Alignment
#Run Star aligner
scripts/star_align.sh

#Read Counting
#Run Feature
scripts/featurecounts.sh

#Differential Expression Analysis
#Run DESeq2
Rscript scripts/deseq2_analysis.R

#Functional Enrichment and Visualization
#Run Clusterprofiler
Rscript scripts/clusterprofiler_analysis.R
