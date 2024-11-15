"# Spatial-transcriptomics"

This code visualized the spatial gene expression of cells in the 2nd serial anterior section 
of the sagittal mouse brain and compared 2 methods for cell-type deconvolution: Seurat 
V3 and PhiSpace. Seurat V3 is designed for single-cell RNA sequencing analysis but can 
be adapted for spatial transcriptomics analysis. It transfers labels from reference cells to 
query cells. PhiSpace is a more recent tool that uses a supervised learning approach to 
improve deconvolution accuracy by incorporating spatial coordinates and features 
derived from the data. We are interested if PhiSpace performs better than Seurat V3.  
