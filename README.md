# BioTrainSce2GProject
HudsonAlpha Cochran Dry Lab Project: ScE2G Links &amp; Cross Analysis

Goal of this project: To determine cis-Regulatory Elements (cCREs) through enhancer gene pairs (links) in Alzheimer's disease (AD) single cell dataset using a new machine learning program, ScE2G, then cross-analyze with prior test results and databases such as a previous enhancer-gene method, Cell Ranger ARC, MAPT experimental results, and AD Significant Variant Genome Wide Association Studies (GWAS) to verify performance results.

This project is research-oriented, so all data and code are open access. The Cochran Lab previously sequenced 15 post-mortem brain tissues, 8 being control patients, while the other 7 had diagnosed Alzheimer's. I was given the raw ATAC, chromatin accessibility, and RNA gene expression sequences. I followed the ScE2G step-up and execution GitHub (https://github.com/EngreitzLab/scE2G). I executed ScE2G on five key cell types (Astrocytes, Excitatory, Inhibitory, Microglia, and Oligodendrocytes), and the code begins with the start of accessing the results. 

Other Datasets Used:

 "enc4" - ENCODE Candidate Cis-Regulatory Elements used to overlap with my link calls
 
 "OldLinks" - Ashyln Anderson from the Cochran Lab had run Cell Ranger ARC method on the same dataset previously, so I used it to compare performance 

 "Past.MapT" - A dataset of enhancer regions connecting to the MAPT gene with columns detailing True/False if the enhancer passed the wet lab test, indicating gene expression of MAPT

 "AD" - a GWA dataset with variants that have been identified to be significant in AD development (Bellenguez et al)
 

