# Cell Type Inference Methods

A public list of computational methods for cell type inference based on genome-scale DNA methylation data

## Reference-based methods  

### Conceptually new reference-based estimation methods  
* **Constrained projection method by Houseman et al.**  
Reference: [PMID 22568884](https://www.ncbi.nlm.nih.gov/pubmed/22568884)  
Implementations: [methylSpectrum (R, script)](http://people.oregonstate.edu/~housemae/software/Houseman-2012-BMCBioinformatics-Software-v112.zip), [minfi (R, BioC)](https://bioconductor.org/packages/release/bioc/html/minfi.html), [RnBeads (R, BioC)](https://www.bioconductor.org/packages/release/bioc/html/RnBeads.html)  

* **Cell epigenotype-specific (CETS) model**  
Reference: [PMID 23426267](https://www.ncbi.nlm.nih.gov/pubmed/23426267)  
Implementation: [CETS project on r-forge (R)](http://cets.r-forge.r-project.org)  

* **EpiDISH**  
Reference: [PMID 28517979](https://www.ncbi.nlm.nih.gov/pubmed/28517979)  
Implementation: [EpiDISH (R, Bioc)](https://bioconductor.org/packages/release/bioc/html/EpiDISH.html)

### Methods for the optimal search of the cell type-specific CpG libraries

* **IDOL**  
Reference: [PMID 26956433](https://www.ncbi.nlm.nih.gov/pubmed/26956433)  
Implementation: unknown  

## Reference-free methods

### Reference-free methods for the correction of differential methylation analysis

* **FaST-LMM-EWASHer**  
Reference: [PMID 24464286](https://www.ncbi.nlm.nih.gov/pubmed/24464286)  
Implementation: [FaST-LMM-EWASHer (R)](https://www.microsoft.com/en-us/download/details.aspx?id=52501)   

* **RefFreeEWAS**  
Reference: [PMID 24451622](https://www.ncbi.nlm.nih.gov/pubmed/24451622)  
Implementation: [RefFreeEWAS (R, CRAN)](https://cran.r-project.org/package=RefFreeEWAS)  

* **ReFACTor**  
Reference: [PMID 27018579](https://www.ncbi.nlm.nih.gov/pubmed/27018579)  
Implementation: [web-site (python, R)](https://www.cs.tau.ac.il/~heran/cozygene/software/refactor.html)  

### Reference-free deconvolution methods

* **RefFreeCellMix**  
Reference: [PMID 27358049](https://www.ncbi.nlm.nih.gov/pubmed/27358049)  
Implementation: [RefFreeEWAS (R,CRAN)](https://cran.r-project.org/package=RefFreeEWAS)  

* **MeDeCom**  
Reference: [PMID 28340624](https://www.ncbi.nlm.nih.gov/pubmed/28340624)  
Implementation: [MeDeCom (R, GitHub)](https://github.com/lutsik/MeDeCom)  


# Benchmarking studies  
* https://www.ncbi.nlm.nih.gov/pubmed/28410574
