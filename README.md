# sod1-als-snrna

## Before running app...

This R Shiny app also requires that you download the integrated SCT normalized count data, which can be found at NCBI GEO GSE173524 (GSE173524_umi.sctransform.tsv.gz). It has not been included on Github simply due to large file size.

Once dowloaded, unzip in Terminal, read into R, optionally convert to S4 sparse matrix, and finally save as uncompressed RDS with file name data.exp.rds.

Put the rds file in the folder with the app and other files.

## Citation and Data

MacLean M, López-Díez R, Vásquez C, Gugger PF, Schmidt AM (Submitted) Neuronal–glial communication perturbations in murine *SOD1<sup>G93A</sup>* spinal cord, *Communications Biology*, [doi:TBD](LINK TO PAPER).

Raw sequencing data, gene-barcode matrices, and metadata:
 [NCBI GEO GSE173524](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE173524)

## Abstract

Amyotrophic lateral sclerosis (ALS) is an incurable progressive neurodegenerative disease characterized by proteinaceous aggregate accumulation and neuroinflammation. To interrogate cell-intrinsic and inter-cell-type perturbations in ALS, single-nucleus RNA sequencing was performed on the lumbar spinal cord in the murine ALS model *SOD1<sup>G93A</sup>* transgenic mice and littermate control mice at peri-symptomatic onset stage of disease, age 90 days. Our findings pinpoint perturbed tripartite synapse functions coupled with dysfunctional repair mechanisms and complement activation. These processes, together with metabolic stress, exacerbate cell-death and proteolytic stress-associated gene sets, even during incipient symptomatology at age 90 days. This work provides a new resource of cell-specific niches in the ALS spinal cord and asserts that intertwined neurodegenerative cellular processes are underway before disease manifestation and are recapitulated, in part, in the human post-mortem ALS spinal cord.
<br/><br/>

[Shiny](https://shiny.rstudio.com) *app designed by* [Paul Gugger](https://scholar.google.com/citations?user=XoKJ7WwAAAAJ&hl=en) *based partly on code from* [nichExplorer](https://github.com/igordot/nichexplorer)
