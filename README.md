## The APOE isoforms differentially shape the transcriptomic and epigenomic landscapes of human microglia in a xenotransplantation model of Alzheimer’s disease   

Kitty B. Murphy, Di Hu, Leen Wolfs, Renzo Mancuso, Bart De Strooper, Sarah J. Marzi

This repository contains all the data and code required to reproduce the figures in our manuscript: [doi.org/10.1101/2024.07.03.601874](doi.org/10.1101/2024.07.03.601874). The code can be found in the file manuscript_figures.qmd.

# Software version requirements
- General QC: FASTQC 
- Alignment: bowtie2 v2.4.2
- Sorting and indexing: samtools v1.9
- Removal of duplicates: picard (JAVA version 21)
- Peak calling: MACS3 v3.0.0b3
- Filtering (non-uniquely mapped reads, quality threshold): samtools v1.9
- Filtering of blacklist regions: bedtools v2.31.0
- Read count generation: featureCounts v2.0.3
- Differential expression and chromatin accessibility analysis: DESeq2 v1.44
- Peak annotation: ChIPseeker v1.40 
- Pathway enrichment analysis: clusterProfiler v4.12
- Motif enrichment analysis: HOMER v4.11 
- Weighted gene co-expression network analysis (WGNA): v1.73
- LDSC: v1.0.1
