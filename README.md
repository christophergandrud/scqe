
<!-- README.md is generated from README.Rmd. Please edit that file -->

# scqe

<!-- badges: start -->

<!-- badges: end -->

The scqe package allows users to implement the stability controlled
quasi-experiment (SCQE) (Hazlett, 2019) approach to study the effects of
newly adopted treatments that were not assigned at random. This package
created tools to help users avoid making statistical assumptions that
rely on infeasible assumptions.

## Motivation

Typical covariate-adjustment techniques used in statistical analysis
impose the often too strict “no-unobserved confounding” assumption.
Ignoring relevant cofounding biases can lead to overconfidence or
inaccuracy of experimental results. SCQE instead imposes an assumption
about the “baseline trend” for the change in average non-treatment
outcome between successive cohorts in observational studies. More
information about this method can be found in Hazlett, 2019.

## Installation

You can install the development version of scqe from
[GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("chadhazlett/scqe")
```

## Example

This is a basic example which shows you how to solve a common problem:

``` r
#library(scqe)
## basic example code
```