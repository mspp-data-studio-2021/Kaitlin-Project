# Kaitlin-500-Cities

Getting Started:

You will first need to download and install R and RStudio.

Then clone this project repository and open the file r-project.Rproj to launch the project in R Studio.

This project uses renv to handle dependency managemnt. When you launch the project in RStudio this package will automatically be installed (you can do so manually using install.packages("renv")). Then to install all the required packages, run the following on the R console in RStudio, and when prompted, select the option Restore the project from the lockfile.:

renv::init()



To replicate the project:

Download the CSV file from Dropbox to obtain the raw data:
https://www.dropbox.com/s/xbk2eal3azcuoyd/500_Cities__Local_Data_for_Better_Health__2019_release.csv?dl=0



Replicating the analysis:

The entire analysis and all files can be replicated by running source("Code/final edit.rmd"), which in turn will run all the the other numbered scripts and notebooks in /code.

This notebook reads in the clean tract dataset and produces some maps. The map files are saved to /Images and the rendered notebook is saved to /Docs
