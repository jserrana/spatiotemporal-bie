Title: "Pollutant biodegradation profile mediated by multi-trophic microbial dynamics in rivers"
Author: "Joeselle Serrana"
Date: "8/1/2025"

---  
Source Data:

MS-Spatiotemporal-BIE_R-Codes.Rmd           		 # R scripts for the analyses: from input data processing to downstream analyses.

src/

		dada2/										 # Output files from the DADA2 read processing, e.g., ASV count table, read counts, etc.
		fasttree/									 # Phylogenetic tree files for the 16S and 18S rRNA data.
		modima/								 		 # Modima R code.
		microeco/									 # Microtable objects for downstream analyses, e.g., bac.mco (16S rRNA microtable), euk.mco (18S rRNA microtable), etc. 
---
Notes: The major R packages needed for running the scripts are:
phyloseq; microeco                                   # Libraries for data manipulation, analysis, and visualization. Ecological analysis of microbiome data; visit https://github.com/ChiLiubio/microeco for more details
ggplot2; ggradar; ggcor; ComplexHeatmap; aplot       # libraries for data visualization
magrittr; ggh4x; dplyr; microViz; magrittr           # Other packages needed.

Other packages for different processes (e.g., readxl, textshape, car, patchwork, etc.) also needs to be installed. If there is an issue dealing with the code send a message to joeselle.serrana@aces.su.se/joeselle.ms@gmail.com :)
