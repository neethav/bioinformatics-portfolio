# TCGA-LUAD Survival ML Pipeline

**Machine learning pipeline predicting lung adenocarcinoma survival from RNA-seq data.**

## Key Results
- Cox PH: TP53 (HR=1.87, p<0.001), EGFR (HR=1.42)
- Random Forest: R²=0.67 on held-out test set
- Top pathways: p53 signaling (25%), RTK/MAPK (35%)

## [Full analysis → notebooks/tcga-survival.ipynb](tcga-survival-ml/notebooks/tcga-survival.ipynb)

**Tech:** lifelines, scikit-learn, TCGA, Nextflow-ready
