# Analyses of tumor infiltrating lymphocytes involved in intercellular transfer with tumor cells
Scripts and custom code used for the analysis of data presented in "The Mosquito Effect: Regulatory and effector T cells acquire cytoplasmic material from tumor cells through intercellular transfer" (doi:)

# List of files:
- scRNAseq_CD45+_TILs.R  
  - R code using the Seurat package for the analysis of scRNAseq data of all CD45+ Tumor infiltrating lymphocytes.
- scRNAseq_CD45+TCR+_TILs.R
  - R code using the Seurat package and the ProjecTILs package for the analysis of scRNAseq data for CD45+ TCR+ TILs.
- csv_to_10x.py
  - Python script used to convert flow cytometry data exported as a csv file from the FlowJo software into the 10x genomics file formats, so that the data can be analyzed in R with the Seurat package.
- AURORA_to_Seurat. R
  - R code using the Seurat package for the analysis of flow cytometry data. Input files are generated using the csv_to_10x.py script.
 
 
