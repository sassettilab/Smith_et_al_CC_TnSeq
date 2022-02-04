This repository contains supplemental data from Smith et al., 2022 (Online Ahead of Print). 

Publication URL: https://elifesciences.org/articles/74419

DOI: 10.7554/eLife.74419

Files:

addcovar.csv - batch membership; additive covariates formatted for R/qtl2

all_clinical_raw_phenos_individual_05JUN2020_v4.csv - master table of clinical
	phenotypes and covariates; individual mice

pheno_clinical_4qtl2_win2_05OCT2019_v4.csv - summarized clinical phenotype
	values used for R/qtl2 genome scans (winsorized)

pheno_eigenscores_from_WGCNA_all60_win.csv - eigentrait phenotype values used
	for R/qtl2 genome scans (winsorized)

pheno_Tn-seq_679_4qtl2_win.csv - Tn-seq phenotype values used for R/qtl2 genome
	scans (winsorized)

qtl2_mapping_objects_for_Smith_etal.Rdata - R data file containing objects used
	for R/qtl2 mapping. Includes the following variables:
		addcovar - data frame of additive covariates
		GM.snps - data frame giving genomic location of probes
		Xcovar - data frame of X chromosome covariates
		genoprobs.1 - R/qtl2 allele probabilities for mapping panel
		kinship - R/qtl2 kinship matrix (leave one chromosome out)
		map.1 - R/qtl2 genetic map (cM)
		map.Mb - R/qtl2 genetic map (Mb)

