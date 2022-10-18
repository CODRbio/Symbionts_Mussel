Strain-level assembly of Symbionts mussels from vents and cold seeps in the Wester-Northern Pacific Ocean

The repository is built to store scripts utilized for the assembly of the strain-level genomes of the methane-oxidising (MOX) symbionts. The scripts will also support the analysis on positive selection,  clade-specific genes recovery and differential distribution of genes along certain locations.
The scripts offer the necessary supports for readers of the manuscript entitling "The environment-driven mosaic evolution of bacterial endosymbionts in deep-sea mussels based on strain-level genome assemblies" to do the analysis themselves. We have not checked their validity on other datasets. Please be aware that they are not tools intended for further usage.

For most of the scripts, -h option following each command will give the general introduction on their usages.

Modified binning scripts were stored in the directory metawrap-modules

Enrichment analysis of selected gene lists
Script: GOenrich.r and KEGGenrich.R for GO and KEGG enrichment analysis

Phylogenetic tree construction using both single-copy and multiple-copy orthologs
Script: astral_tre.pl and adj_AstrialTree.py

Find out clade-specifc genes from the orthologs
Script: get_specialOrtholog.py

PAML analysis to find out genes under selection for each clade
Script: selection_paml_group.py

Population genetic analysis pipelines providing Fst, pN/pS
Script: Snakemake.py and softwares in the folder scripts

Comparisons of Genes density around locations of interest
Script: bilateral_gene_cruise.py

Get representative sequences for each othologs
Script: get_represetativeOrtholog.py

Align the cds based on the aligned peptide
Script: get_represetativeOrtholog.py
