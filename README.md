# worm-tutorials
A collection of Jupyter notebooks in Python showing how to use some tools from WormBase and related resources
For each notebook there is a brief description of what it does and a link to an html preview with nbviewer and a ready to run enrivonment using Google colab



## Tissue enrichment analysis 
[Open HTML preview](https://nbviewer.jupyter.org/github/Munfred/worm-tutorials/blob/main/tissue_enrichment_analysis.ipynb) or [Run in Colab](https://colab.research.google.com/github/Munfred/worm-tutorials/blob/main/tissue_enrichment_analysis.ipynb)

This notebook showcases how to usue the pip packaged version of Tissue Enrichment Analysis (TEA). 
TEA Results are output to a dataframe and example bar plots plots are shown. 

**Steps performed**

- Installing and loading the required libraries
- Loading a list of genes from a text file
- Fetching the needed analysis dictionaries from wormbase
- Performing enrichment analysis on the gene list
- Plotting the results withs tandard pandas function
