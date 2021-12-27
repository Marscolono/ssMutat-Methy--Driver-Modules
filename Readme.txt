
ssMutat(methy)-Driver Modules


-------------------------References----------------------------------------
# Here is the source code of the construction of samples-specific mutation driver modules and methylation aberration driver module （ssMutat-DM and ssMethy-DM).

References:
Yuanyuan Chen, Haitao Li, Xiao Sun, Construction and analysis of sample-specific driver modules for breast cancer.


--------------------------Description---------------------------------------------
The functional impact of somatic mutation and methylation aberration at an individual level is an important research direction to implement precision medicine. 
More and more studies have shown that the perturbation of gene interaction network provides a fundamental link between genotype (or epigenotype) and phenotype. 
However, functional effects on biological networks for individual mutations, especially for individual methylation aberration, are largely unknown. 
To solve this, we provided a sample-specific driver module construction method by the 2-order network theory and hub-gene theory 
to identify individual perturbation networks driven by mutations or methylation aberrations. 
The method integrated multi-omics including genomics, transcriptomics, epigenomics and interactomic of breast cancer, 
and provided new insight into the synergistic collaboration between methylation and mutation at individual level. 

We construct sample-specific driver modules in three steps. 
First, the sample-specific network (SSN) for each breast cancer sample can be constructed based on the gene expression profiles and background network by the SSN method. 
Second, the somatic mutation profiles of all breast cancer samples can be constructed by the somatic mutation data. 
In addition, based on the methylation data we can obtain the aberrantly methylated genes for each tumor sample by the outlier detection method of Hampel filter, 
which make up the methylation aberration profiles for breast cancer samples. 
Finally, the sample-specific mutation driver module (ssMutat-DM) and the sample-specific methylation aberration driver module (ssMethy-DM) 
can be constructed using the 2-order network theory and hub-gene theory.



--------------------------Contact---------------------------------------------
If any problem or suggestion, please contact Meina Kan (chenyuanyuan@njau.edu.cn)
