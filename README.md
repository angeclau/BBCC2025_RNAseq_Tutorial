# *BBCC2025 Tutorial: Introductory bulk RNA-seq analysis in R:*
## *From raw counts to biological interpretation.*


## Speaker

* Claudia Angelini, <sup>1<sup>

## Tutors
* Olga Lanzetta<sup>1,2<sup>
* Maura Mecchi<sup>3<sup>
* Eva Luna Tarallo<sup>1<sup>

1 Istituto per le Applicazioni del Calcolo "M. Picone", IAC-CNR, Naples, Italy\
2 Dipartimento di Medicina Sperimentale - DIMES, Università degli Studi di Genova Italy\
3 Università degli Studi della Basilicata

## Description

After providing a general overview of bulk RNA-seq data and analysis, this practical tutorial will focus 

* Quality control, Normalization, Batch correction,  

* Differential Expression (DE) Analysis,
 
* Functional Enrichment and Pathway Analysis, using R and Bioconductor packages. 

In particular, we will use DESeq2 for differential expression analysis, which is one of the most popular and robust methods for RNA-seq analysis.

## When

The tutorial will be given on December 3rd, 2025 in occasion of the Bioinformatics and Computational Biology Conference (BBCC2025)

## Detailed program 

1.    **Introduction** 

* What are bulk RNA-seq data?
* An overview of the RNA-seq workflow 

2.    **Data Import & Preprocessing**

* Import count matrix & metadata

3.   **QC & Exploratory Data Analysis**
   
* Summary statistics, library sizes, PCA, and hierarchical clustering, 
* Visualization 

4.    **Data Normalization**

* The need for normalization
* Normalization strategies using DESeq2 (i.e., variance stabilizing transformation (VST) or rlog transformation)
* Post-normalization QC:

5.    **Differential Expression Analysis**

* Statistical Model Setup: Experimental design formula (e.g., ~ condition)
* Run Differential Expression Using DESeq2 

6.    **Results Extraction: Log2 fold changes, adjusted p-values**

* Visualization: MA plot, Volcano plot, Heatmap of top DE genes.

7.    **Functional Enrichment Analysis**

* Gene Ontology (GO) and Pathway Analysis clusterProfiler for GO/KEGG enrichment
* Visualization

8. **Question time**

9. **Exercises**

## To do before coming 
List of things to do before attending the tutorial:

1.    Install R (https://www.r-project.org)

2.    R Studio (https://posit.co/download/rstudio-desktop/)

3.    List of packages to install:

From CRAN (https://cran.r-project.org/)

- install.packages("ggplot2")
- install.packages("dplyr")
- install.packages("pheatmap")
- install.packages("RColorBrewer")

From Bioconductor (https://www.bioconductor.org/)

if (!require("BiocManager", quietly = TRUE))

    install.packages("BiocManager")
BiocManager::install(version = "3.22")

- BiocManager::install("DESeq2")
- BiocManager::install("AnnotationDbi")  
- BiocManager::install("org.Hs.eg.db")  
- BiocManager::install("clusterProfiler")  
- BiocManager::install("apeglm")
- BiocManager::install("msigdbr")
- BiocManager::install("airway") ## For the example dataset 


## Acknowledgments

- This tutorial presented at BBCC 2025 (https://www.bbcc-meetings.it/bbcc2025/) is part of the dissemination activities supported by the P2022BLN38 project *Computational approaches for the integration of multi-omics data* – funded by European Union – Next Generation EU within the PRIN 2022 PNRR program (D.D. 1409 del 14/09/2022 Ministero dell’Università e della Ricerca) CUP B53D23027810001.




