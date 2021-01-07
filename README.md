# ***Genomic Landscape of Structural Variation in *Passer domesticus****

***Snakefile #1:***
BWA alignment and GATK pipeline

***Snakefile #2:***
Structural variant calling and genotyping with `smoove`[(more here)](https://github.com/brentp/smoove)

***Intermediate steps needed prior to visual curation:***

TO DO: JupyterNotebook for: 
Randomly selecting 3 individuals of each genotype (`HOM_REF, HET, HOM_ALT`) with `gen_samplot.py` for generating the Samplot images (.png) for PlotCritic

TO DO: ***Snakefile #3:***
Setting up a project in PlotCritic for visual curation, using SV-Plaudit on an Amazon Instance


## ***Data Exploration*** 
JupyterNotebooks for executing all steps, from extracting curated variants from raw PlotCritic reports to final plotting in Python3. These need to be run in the order presented below.


***Notebook #1, Part 1: Intersecting and plotting a PCA for all Deletions that were given "Yes" by all four curators.***

Click to open
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/gdaviduu/House-Sparrow-Genome-Analysis.git/main?filepath=Extract_SV_regions_PCA_Part1to4.ipynb)


***Notebook #1, Parts 2 to 4: Intersecting and plotting a PCA for all Deletions that were given either "Yes" or "Maybe" by all four curators; plotting all of the remaining SVs that were rejected by all four curators; and plotting all raw Uncurated Deletions.***

Click to open
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/gdaviduu/House-Sparrow-Genome-Analysis.git/main?filepath=Extract_SV_regions_PCA_Part1to4.ipynb)


***Notebook #2: Plotting Size Histograms for SVs***

Click to open
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/gdaviduu/House-Sparrow-Genome-Analysis.git/main?filepath=Plotting_Size_Histograms_for_SVs.ipynb)

***Notebook #3: Downsampling SNPs in PLINK and plotting PCAs to compare to similarly-sized SV-callsets***

Click to open
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/gdaviduu/House-Sparrow-Genome-Analysis.git/main?filepath=Plotting_PCA_for_Downsampled_SNPs.ipynb)


