# SISMID 2026: Spatial Statistics in Epidemiology and Public Health
Github repository for the SISMID 2026 "Spatial Statistics in Epidemiology and Public Health" module

**Course Dates**: Wednesday, July 22, 2026 to Friday, July 24, 2026

## Introduction

Welcome to the 2026 SISMID course on Spatial Statistics for Epidemiology and Public Health! 
Spatial methods are now used in many disciplines and play an important role in epidemiology and public health. This module gives an introduction to spatial methods. In particular, we will present methods for assessment of clustering, cluster detection, spatial regression, small area estimation, and disease mapping. Methods will be described for both point data (in which cases and non-cases (or a sample thereof) have an associated point location) and count data (in which the numbers of cases and non-cases in a set of geographical areas are available).

Many examples will be presented, with analysis carried out in the R programming environment.

## Prerequisites

This module assumes basic knowledge of probability and statistical inference. Some prior knowledge of R would be helpful.

## Installing R and RStudio

This SISMID module exclusively uses R. We recommend R 4.6 and above. You can download a recent version [here](https://www.r-project.org/).

We also recommend using RStudio as the main GUI interface. You can install the free version [here](https://posit.co/download/rstudio-desktop/). 

Installation of R and RStudio should proceed smoothly on most operating systems. Detailed instructions can be found [here](http://rafalab.dfci.harvard.edu/dsbook/installing-r-rstudio.html). 

The module makes use of other specific R packages as well. You can install them using the `install.packages("PACKAGE NAME HERE")` command. R will let you know what packages you do not have installed when you try to run a script in full.

## Installing R-INLA

You will need to download the INLA package to run the code in this module. 

The [INLA](https://www.r-inla.org/) package performs approximate Bayesian inference for latent Gaussian models. Installing the package is a bit different than normal since it is not on CRAN, the central software repository for R packages. Detailed instructions for installing the stable/testing can be found [here]([https://www.r-inla.org/download-install](https://www.r-inla.org/download/index.html)). 

Additionally, you can also install INLA by going to [this link](https://inla.r-inla-download.org/R/stable/bin/windows/contrib/). Go to your current R version (ideally version 4.6), and pick a "INLA_*.zip" file to download
where the star denotes the INLA package version number. Download the zip file to a known filepath. In RStudio, under the Tools menu, select Install Packages, and Install from: Package Archive File. Tell RStudio where the .zip file is located on your local machine.

## How to access code 

1. Go to the green "Code" button near the top of this page, click, and download as a zip file to your computer.
2. Save the zip file to a directory of your choice, then unzip the file.   You will see a folder of lectures, a folder for data, etc.
3. IMPORTANT:  You will also see a file named "SISMID_2026_spatial_statistics.Rproj" ; this will pull in all of the lab code and data as a project.
4. If you are unfamiliar with R/RStudio, you can focus on reading through the lab pdfs to see examples of what you can do.
5. If you are familiar with R/RStudio, you can try out the Rmd code.

## Schedule

1. Introduction + GitHub install + Mapping (**Waller**)
2. Areal Data (EDA, clustering) (**Chang**) 
3. Disease Mapping  (CARs, Bayesian analysis with INLA) (**Chang**) 
4. Spatial regression + Spatial Coefficient (**Waller**) 
5. Lab 1: Spatial Data Wrangling (**Chang/Waller**) 
6. Lab 2: Spatial Regression (**Chang/Waller**) 
7. Point Processes (**Waller**)
8. Gaussian Processes (**Chang**)
9. Lab 3: Point Processes and Gaussian Processes (**Chang/Waller**) 
10. Spatial infectious disease (SIR), ecology (**Waller**) 

## Reference

[Waller, L. and Gotway, C. (2004). Applied Spatial Statistics for Public Health Data. New York, John Wiley and Sons.](https://onlinelibrary-wiley-com.proxy.library.emory.edu/doi/book/10.1002/0471662682)

[Analyzing US Census Data: Methods, Maps, and Models in R.](https://walker-data.com/census-r/index.html)

[Geocomputation with R](https://r.geocompx.org/index.html)

[Spatial Data Science](https://r-spatial.org/book/)

[Spatial-Temporal Statistics with R](https://spacetimewithr.org/)

[Geospatial Health Data: Modeling and Visualization with R-INLA and Shiny](https://www.paulamoraga.com/book-geospatial/)

[Advanced Spatial Modeling with Stochastic Partial Differential Equations Using R and INLA](https://becarioprecario.bitbucket.io/spde-gitbook/index.html)

## Contact

If you have any questions feel free to contact the following course instructors and TA's, or send a message in the class Slack channel.

Instructors: [Lance Waller](mailto:lwaller@emory.edu), [Howard Chang](mailto:hhchang.emory.edu)

Teaching Assistant: [Akshay Deverakonda](mailto:akshay.deverakonda@emory.edu)
