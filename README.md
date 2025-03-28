
<!-- README.md is generated from README.Rmd. Please edit that file -->

# postmarkr <img src="man/figures/logo.png" align="right" height="138" />

<!-- badges: start -->

[![Project Status: WIP – Initial development is in progress, but there
has not yet been a stable, usable release suitable for the
public.](https://www.repostatus.org/badges/latest/wip.svg)](https://www.repostatus.org/#wip)
[![R-CMD-check](https://github.com/andreranza/postmarkr/actions/workflows/R-CMD-check.yaml/badge.svg)](https://github.com/andreranza/postmarkr/actions/workflows/R-CMD-check.yaml)
<!-- badges: end -->

The goal of postmarkr is to interact with the [Postmark
API](https://postmarkapp.com/developer), from R.

It is an independent, community-developed R package for the
[Postmark](https://postmarkapp.com) email service (not created by or
affiliated with Postmark).

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

## Features

- Get email delivery logs
- List email templates
- Track email delivery statistics
