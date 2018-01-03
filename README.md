
<!-- README.md is generated from README.Rmd. Please edit that file -->
rmddm
=====

rmddm provides Rmarkdown templates for use in data mining, specifically those projects following the [CRISP-DM](https://en.wikipedia.org/wiki/Cross-industry_standard_process_for_data_mining) process. The package is based on the [rticles](https://github.com/rstudio/rticles) package.

Installation
------------

Installing rmddm from github with:

``` r
# install.packages("devtools")
devtools::install_github("wdavis12/rmddm")
```

Example
-------

Creating an RMarkdown template with the CRISP-DM structure:

``` r
library(rmarkdown)
draft("MyReport.Rmd", template = "crispdm_report", package = "rmddm", edit=FALSE)
```
