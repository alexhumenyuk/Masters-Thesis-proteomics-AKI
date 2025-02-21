# Phosphoproteome characterization of acute kidney injury
## Overview
**Project context** 

  We aimed to identify phosphorylated renal proteins with significant abundance changes during cisplatin-induced acute kidney injury (AKI) in mice, as these proteins may serve as potential biomarkers or therapeutic targets.

**Data summary**

  False discovery rate (FDR)-corrected abundances of 3,709 phosphopeptides were processed, quantified using tandem mass tag labeling coupled with high-performance liquid chromatography-tandem mass spectrometry (HPLC-MS/MS). Currently, both the data and results are not publicly available, as they await publication.
  
**Analysis tools**: Jupyter Notebooks and [Enrichr](https://maayanlab.cloud/Enrichr/).

## Analysis & Results
### Principal component analysis (PCA)
PCA was used to assess whether the samples clustered based on their experimental conditions. The resulting plot revealed two distinct groups, meaning that were consistent differences between them.

<img src="/Graphs/PCA.png">

### Heatmap
To visualize the most significant differences between the two groups, a heatmap was generated with the 20 phosphoproteins with the greatest increases in abundance and the 10 with the greatest decreases.

<img src="/Graphs/Heatmap.png">

### Volcano plot
A volcano plot was generated to facilitated the identification of potential biomarkers or therapeutic targets by highlighting phosphoproteins with both significant fold changes and statistical significance.

<img src="/Graphs/Volcano_plot.png">

### Enrichment analysis (biological process)
The FDR-corrected phosphopeptides corresponded to 1,800 non-redundant genes, while the phosphoproteins with a statistically significant fold change corresponded to 97 non-redundant genes. These two sets of genes were compared to determine if certain biological processes were overrepresented during AKI.

<img src="/Graphs/Enrichment.png">
