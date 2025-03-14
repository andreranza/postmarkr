
<!-- README.md is generated from README.Rmd. Please edit that file -->

# postmarkr

<!-- badges: start -->

[![Project Status: WIP – Initial development is in progress, but there
has not yet been a stable, usable release suitable for the
public.](https://www.repostatus.org/badges/latest/wip.svg)](https://www.repostatus.org/#wip)
<!-- badges: end -->

The goal of postmarkr is to interact with the Postmark API, from R.

## Installation

You can install the development version of postmarkr like so:

``` r
pak::pak("andreranza/postmarkr")
```

## Example

This is a basic example which shows you how to solve a common problem:

``` r
library(postmarkr)
outbound_messages_fetch(count = 20L)
```
