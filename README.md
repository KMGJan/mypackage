
<!-- README.md is generated from README.Rmd. Please edit that file -->

# mypackage

<!-- badges: start -->
<!-- badges: end -->

The goal of mypackage is to make splitting one string easier.

## Installation

You can install the development version of mypackage from
[GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("KMGJan/mypackage")
```

## Example

This is a basic example which shows you how to solve a common problem:

``` r
library(mypackage)

(x <- "alfa,bravo,charlie,delta")
#> [1] "alfa,bravo,charlie,delta"
str_split_one(x, pattern = ",")
#> [1] "alfa"    "bravo"   "charlie" "delta"
```
