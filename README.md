# ***Genomic Landscape of Structural Variation in *Passer domesticus****

## ***Structural Variant Calling and Visual Curation*** 

***Snakefile:***
BWA alignment and GATK pipeline

Followed by: Structural variant calling and genotyping with `smoove`[(more here)](https://github.com/brentp/smoove)


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

***Notebook #4: Circos Plot in R***
Click to open
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/gdaviduu/House-Sparrow-Genome-Analysis.git/main?filepath=circos_R.ipynb)
