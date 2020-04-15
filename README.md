# ReactomeGSA Tutorials

This is a collection of [Jupyter notebooks](https://jupyter.org) to showcase how to use the [ReactomeGSA R package](https://github.com/reactome/ReactomeGSA).

Most of these notebooks contain rather large analyses take quite a while to run. Shorter tutorials that also cover the complete functionality of the ReactomeGSA package are released as vignettes of the R package.

You can find these vignettes as pre-compiled HTML files at the ReactomeGSA [Bioconductor page](https://bioconductor.org/packages/release/bioc/html/ReactomeGSA.html) (or [here](https://bioconductor.org/packages/devel/bioc/html/ReactomeGSA.html) for the latest development version).

## Comparative Pathway Analysis

  * **[TCGA Cancer Analysis](notebooks/TCGA_B_Cell_Analysis.ipynb)**: An analysis of B cell rich vs. poor cancer samples from the TCGA studies on melanoma, ovarian, lung (adenocarcinoma and squamous cell carcinoma), and breast cancer as well as the corresponding CPTAC proteomics studies on breast and ovarian cancer.

## Single Cell Analysis

  * **[B cell subtype analysis](notebooks/Jerby_Arnon_Seurat.ipynb)**: An analysis of B cells extracted from the single-cell RNA-sequencing dataset published by Jerby-Arnon *et al.* (Cell, 2018). ReactomeGSA allowed us to quickly compare different pathway functions in the identified B cell subtypes.
