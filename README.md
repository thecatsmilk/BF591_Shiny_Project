# BF591_Shiny_Project
**Please note that the counts matrix and `DESeq2` files are required for this app's use and can be found at the link below**
## Final project for BF591—creation of an R Shiny application for various bioinformatics analyses.
## BF591 is a rigorous course that teaches students bioinformatic analyses with the R programming language. We develop functions for a wide variety of bionformatic analyses in R. This final project serves as an amalgamation of everything we have learned into an elegant and concise R Shiny app.

### What the app contains
This app showcases various bioinformatic analyses of the data from this paper, written by the instructor of the course Dr. Adam Labadorf (https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE64810).

#### The first tab
The first tab dives into the metadata and returns a summary table as well as two ways to visualize variables of choice.

#### The second tab
The second tab dives into the counts data and outputs two summary tables, diagnostic scatter plots, a heatmap, and a PCA plot.

#### the third tab
The third tab takes in a differential expression results file (DESeq2), and returns a filtered tables of the results, as well as a volcano plot of up- and down-regulated genes

#### The fourth tab
The fourth tab performs gene set enrichment analysis via `fgsea` and returns a bar part of the top enriched pathways, a scatterplot of NES vs. -log(padj), and a filtered table by positive or negative NES with an option to download the results as a CSV file.
