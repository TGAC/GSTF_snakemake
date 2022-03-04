# GSTF_snakemake
Snakemake version of GeneSeqToFamily
# GeneSeqToFamily

GeneSeqToFamily is a comprehensive workflow to indetify gene families from a set of coding sequences. First it was developed to run within Galaxy environment, but with this development not GeneSeqToFamily is able to run on a local computer as well as computing cluster. 

# Workflow

Snakemake version of GeneSeqToFamily workflow is divided into three steps:

* GSTF_smk_1

This step takes in CDS as input and identifies gene clusters using pairwise alignment scores.

* GSTF_smk_2

This step of the workflow takes in gene clusters as input and generates genetrees based on multiple sequence alignemnts of each cluster. Followed by splitting of larger genetrees.

* GSTF_smk_3

This step will infer homology and generate gene copy number file for each gene family.

# Citation
If you are using GeneSeqToFamily for your research pleae cite

Thanki AS, Soranzo N, Haerty W, Davey RP. GeneSeqToFamily: a Galaxy workflow to find gene families based on the Ensembl Compara GeneTrees pipeline. Gigascience. 2018 Mar 1;7(3):1-10. doi: 10.1093/gigascience/giy005. PMID: 29425291; PMCID: PMC5863215.
