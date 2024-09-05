# Dataset 1 description

The dataset is from the scientific paper:


Nguyen L-P, Galtier N, Nabholz B. 2015 Gene expression, chromosome heterogeneity and the fast-X effect in mammals. Biol. Lett.11 : 20150010.

# Data source:  
http://dx.doi.org/10.1098/rsbl.2015.0010

# The data underlying this study are available on Dryad:
doi:10.5061/dryad.qr20n

# Abstract
The higher rate of non-synonymous over synonymous substitutions (dN/dS) of the X chromosome compared with autosomes is often interpreted as a consequence of X hemizygosity.
However, other factors, such as gene expression, are also known to vary between X and autosomes. 
Analysing 4800 orthologues in six mammals, we found that gene expression levels, associated with GC content, fully account for the variation in dN/dS between X and autosomes with no detectable effect of hemizygosity.
We also report an extensive variance in dN/dS and gene expression between autosomes

# Columns in the dataset

##   gene = col_character(),    # GENE id
##   Species = col_character(), # Species
##   labs = col_character(),    # A label
##   chrMark = col_character(), # X or autosome
##   chr = col_character(),     # chromosome
##   dN = col_double(),         # dN - nonsynonymous rate
##   dS = col_double(),         # dS - synonymous rate
##   dNdS = col_double(),       # dN/dS ratio
##   RPKM = col_double(),       # Read pr kilobase exon pr. million reads = gene expression level
##   Tau = col_double(),        # Tau = expression specificity (see paper). Tau ranges from 0 (same level of expression across all tissues) to 1 (only expressed in a single tissue).
##   GC3 = col_double()         # GC content of the third codon position.

