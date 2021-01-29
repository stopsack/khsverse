
# khsverse

<!-- badges: start -->
<!-- badges: end -->

The goal of khsverse is to provide a simple way of loading a number of package for epidemiology research.

## Installation

The khsmisc package can be installed from [GitHub](https://stopsack.github.io/khsverse). A CRAN submission is not planned.

```r
# if "remotes" library is missing, install it first:
#   install.packages("remotes")
remotes::install_github("stopsack/khsverse")
```


## Loaded Core Packages

When loading `library(khsverse)`, the following dependencies will be made available:

* **Data handling:** the whole universe of the `tidyverse`;
variable labels via `labelled`; reading Excel files via `readxl`.
* **Tables:** formatted tables via `gt`; descriptive tables via `gtsummary`.
* **Figures:** `ggplot2`; red/green blindness-proof color palettes via `viridis`;
  arranging figure panels via `cowplot`.
* **Analyses:** time-to-event analyses using `survival`;
  accessing regression model results via `broom`.
* **Custom:** extra functions from the `khsmisc` package
