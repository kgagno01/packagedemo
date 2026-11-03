
<!-- README.md is generated from README.Rmd. Please edit that file -->

# packagedemo

<!-- badges: start -->

<!-- badges: end -->

The goal of packagedemo is to enable users to easily calculate common
powers of numeric data. (It serves as a demo for R Package creation.)

## Installation

Package installation can be done directly by calling:

``` r
devtools::install_github("kgagno01/packagedemo")
```

## Example

This is a basic example which shows you how to use the `square` function
from the `packagedemo` package:

``` r
library(packagedemo)

#square a single numeric
square(4)
#> [1] 16

#square a numeric vector
square(c(2,3,4))
#> [1]  4  9 16
```
