# Cord Blood ILTs

This repository is for our ["Cord Blood Innate-like T cell responses in neonates born to healthy women and women living with HIV"](https://www.frontiersin.org/journals/immunology/articles/10.3389/fimmu.2025.1628145/full) Frontiers in Immunology paper. It primarily contains the data and R code needed to reproduce our analysis and figures, as well as the .svg files we used to create the publication figures in [Inkscape](https://inkscape.org/). 

## Organization

The .csv files for the respective analyses are stored in the data folder. The code accesses this folder when creating the individual plots found within each figure. 

The code is contained within the [Quarto](https://quarto.org/) Markdown (.qmd) files, which are named and stored within folders based on their respective figure in the paper.

Additionally within these same folders, you can find the generated individual plots that went into the figure (usually .tiff or .png files), as well as the .svg files were we assembled the plots into their final figure layout using Inkscape.

## Coereba

Please note, you will need to install our R package [Coereba](https://github.com/DavidRach/Coereba) to reproduce some of the Figures. The package version we utilized for running of the code in this manuscript was the 0.99.2 release (prior to the switch to using SummarizedExperiment objects for the Bioconductor submission). 

## Raw Data

Due to size constraints, this repository only contains the processed data files derrived from our original .fcs files (see the data folder). The raw .fcs files and all unmixing controls have been uploaded to the ImmPort repository (SDY3080, Immunity in Neonates and Infants, U. Maryland Baltimore) and will be available at their next release cycle on September 25th, 2025. 

## Lab Notebook

The experimental datasheets used to record processing, staining, and acquisition information during each experiment have been scanned and uploaded to the LabNotebook folder.

## Instrument QC

The visualized quality control data for the 5-laser Cytek Aurora on which the specimens were acquired in 2023 is available via the [UMGCC FCSS dashboard](https://umgccfcss.github.io/Aurora5L/). The SFC experiments took place between May 12 and July 18th, 2023. 


## Interactive View

I made an internal version of the plots shown in Figures 3 and Figures 7, featuring all the Vdelta2 clusters in a single view. I found it useful in visualizing the differences. It can be found [here](https://davidrach.quarto.pub/comparisons/)

# Future Directions

Currently finishing thesis writing, but will continue migrating additional useful information as I find them while cleaning out my desk. If you are interested in anything in particular, please reach out! Best- David



