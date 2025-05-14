# Cord Blood ILTs
This repository is for our "Cord Blood Innate-like T cell responses in neonates born to healthy women and women living with HIV" manuscript. It contains the data and R code needed to reproduce our analysis and figures, as well as the .svg files used to create the figures in Inkscape. 

## Organization

The .csv files for the respective analyses are stored in the data folder, from which they can be accessed by the code. The code is contained within the Quarto Markdown (.qmd) files named after the respective figure. The .svg files can be opened with Inkscape to access the Figure assembly layout. 

## Coereba

Please note, you will need to install [Coereba](https://github.com/DavidRach/Coereba) to reproduce some of the Figures. The package version utilized for running of the code in this manuscript was the 0.99.2 release (prior to the switch to using SummarizedExperiment objects for the Bioconductor submission). 

## Raw Data

Due to size constraints, this repository only contains the processed data files derrived from our original .fcs files. These are being uploaded to ImmPort (SDY3080) and will be available at the next release cycle. 

## Interactive View

For Figures 3 and Figures 7, I made an internal version of the plot featuring all the Vdelta2 clusters in a single view, it can be found [here](https://davidrach.quarto.pub/comparisons/)

