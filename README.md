

<!-- README.md is generated from README.Rmd. Please edit that file -->



# PARIS

<!-- badges: start -->
<!-- badges: end -->

Shiny App to visualize cancer vulnerabilities predicted by PARIS between DNA Damage Repair genes and the entire genome.

## Installation

To run the shiny app locally in R, clone or download this repository and install the required R pacakges as follows:

```r
install.packages("RColorBrewer")
install.packages("tidyverse")
install.packages("visNetwork")
install.packages("shiny")
```

## Run

To run the shiny app (modify the path accordingly to your directory) :

```r
library(shiny)
setwd("/shiny_app_directory/")
runApp()
```

