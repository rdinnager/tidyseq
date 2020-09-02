
<!-- README.md is generated from README.Rmd. Please edit that file -->

# tidyseq

<!-- badges: start -->

[![Lifecycle:
experimental](https://img.shields.io/badge/lifecycle-experimental-orange.svg)](https://www.tidyverse.org/lifecycle/#experimental)
[![CRAN
status](https://www.r-pkg.org/badges/version/tidyseq)](https://CRAN.R-project.org/package=tidyseq)
<!-- badges: end -->

The goal of `tidyseq` is to provide a tidy API to manipulate common
biological sequence formats in R, using wrappers around established
formats (e.g. objects from `adegenet`, `ape`, `Biostrings`, `pegas`,
`ShortRead`, and more). It is largely inspired by `tidygraph`, which
similarly wraps `igraph` objects. In fact, `tidyseq` imports
`tidygraph`, currently only for the generic `activate()` function, but
eventually `tidyseq` will also support assembly graph manipulation using
`tidygraph`.

This is currently a work in progress. If you think this package is a
good idea, and would like to help out, please get in touch. I could use
all the help I can get (this is currently a side-side project for me, to
support my work on machine learning for biological data). It is also my
first attempt at a fully tidyverse compatible package, so I’m learning
as I go here\!

## Installation

You can install the development version from
[GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("rdinnager/tidyseq")
```

## Example

Nothing to show just yet

``` r
library(tidyseq)
## basic example code
```
