[![R-CMD-check](https://github.com/KWB-R/kwb.ml/workflows/R-CMD-check/badge.svg)](https://github.com/KWB-R/kwb.ml/actions?query=workflow%3AR-CMD-check)
[![pkgdown](https://github.com/KWB-R/kwb.ml/workflows/pkgdown/badge.svg)](https://github.com/KWB-R/kwb.ml/actions?query=workflow%3Apkgdown)
[![codecov](https://codecov.io/github/KWB-R/kwb.ml/branch/main/graphs/badge.svg)](https://codecov.io/github/KWB-R/kwb.ml)
[![Project Status](https://img.shields.io/badge/lifecycle-experimental-orange.svg)](https://www.tidyverse.org/lifecycle/#experimental)
[![CRAN_Status_Badge](https://www.r-pkg.org/badges/version/kwb.ml)]()

R Package with Functions, Workflows and Tutorials
for Machine Learning at KWB.

## Installation

For installing the latest release of this R package run the following code below:

```r
# Enable repository from kwb-r
options(repos = c(
  kwbr = 'https://kwb-r.r-universe.dev',
  CRAN = 'https://cloud.r-project.org'))
  
# Download and install kwb.ml in R
install.packages('kwb.ml')

# Browse the kwb.ml manual pages
help(package = 'kwb.ml')
```

## Usage 

The purpose of the R package `kwb.ml` is on the one hand to give a general 
overview on how to perform machine learning in R and on the other hand to 
show practical machine-learning case-studies performed in publically funded 
research projects in form of `reproducible workflows`.

Currently the following [articles](articles/) are available: 

1. [Getting Started](articles/getting-started.html) with machine learning in R 
(recommendation of R packages, literature and e-learning tools)

2. [Case Study: Satellite Image Classification](articles/case-study_satellite-image-classification.html) as 
reproducible R workflow developed in project [KEYS](https://kompetenz-wasser.de/en/forschung/projekte/keys) for `urban surface classification` (e.g. roofs, streets, water) based on a `satellite image`.
