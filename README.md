This research project was conducted between May–August 2026 at the University of Leicester.

The aim of the project was to analyse the effect of reference panel size and genomic composition on the imputation of Mozambican low-coverage genomes. Four custom reference panels were constructed from the 1000 Genomes Project dataset and a Bantu dataset. GLIMPSE2 was used for genotype imputation, PLINK2 for PCA computation, and RStudio for PCA visualisation using two approaches:

(i) Projection PCA — projecting imputed samples onto reference panel PCs, which produced a systematic PC1 offset due to differences between imputed genotype dosage values and reference hard calls.

(ii) Joint PCA — combining imputed samples with the reference panel, which produced the expected population clustering results.

This repository contains two folders, each with two R scripts corresponding to the above PCA methods. A reference list and acknowledgement note are also included.
