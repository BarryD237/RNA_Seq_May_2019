# Cyto
This folder contains all Cell type vs Cell type comparisons within the treated samples. Reported tables are subject to a Log2 Fold change filter of +/- 1 (i.e these genes are upregulated/downregulated twice as much vs. the reference cell type) and additional statistical filtering using the Benjamini & Hochberg method, which returns genes with a false discovery rate below 0.1 (10%) as significant.  

# Control
This folder contains all Cell type vs Cell type comparisons within the control samples. Reported tables are subject to a Log2 Fold change filter of +/- 1 (i.e these genes are upregulated/downregulated twice as much vs. the reference cell type) and additional statistical filtering using the Benjamini & Hochberg method, which returns genes with a false discovery rate below 0.1 (10%) as significant. 

# Controlling for condition
This folder contains Cell type vs. Cell type, whilst controlling for the effect of condition. The previous set of results compared cell types within condition (4 vs 4), where this method compares cell types in both conditions (8 vs 8) increasing its statistical power, whilst nullifying the effect of the treatments. Results are reported with a false discovery rate of 0.1 (10%) and thus can be interpreted as statistically significant. 

# Controlling for Donor
This folder contains Cell type vs. Cell Type, whilst controlling for the inherent genetic variation between sample donors. These results are for both Control and CYTO respectively. Reported tables are subject to statistical filtering using the Benjamini & Hochberg method, which returns genes with a false discovery rate below 0.1 (10%) as significant.
