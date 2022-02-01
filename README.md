
<!-- README.md is generated from README.Rmd. Please edit that file -->

# nflverse <a href='https://nflverse.nflverse.com/'><img src='man/figures/logo.png' align="right" width="25%" min-width="120px" /></a>

<!-- badges: start -->

[![R build
status](https://img.shields.io/github/workflow/status/nflverse/nflverse/R-CMD-check?label=R%20check&style=flat-square&logo=github)](https://github.com/nflverse/nflverse/actions)
[![nflverse
support](https://img.shields.io/discord/789805604076126219?color=7289da&label=nflverse%20support&logo=discord&logoColor=fff&style=flat-square)](https://discord.com/invite/5Er2FBnnQa)
<!-- badges: end -->

## Overview

The nflverse is a set of packages dedicated to data of the National
Football League. The **nflverse** package is designed to make it easy to
install and load core packages from the nflverse in a single command.

## Installation

The easiest way to get nflverse is to install it from
[GitHub](https://github.com/nflverse/nflverse/) with:

``` r
if (!require("remotes")) install.packages("remotes")
remotes::install_github("nflverse/nflverse")
```

## Usage

`library(nflverse)` will load the following nflverse packages:

-   [nflfastR](https://www.nflfastr.com/), for play-by-play data back
    to 1999.
-   [nflseedR](https://nflseedr.com/), for season simulations.
-   [nfl4th](https://www.nfl4th.com/), for 4th down analysis.
-   [nflreadr](https://nflreadr.nflverse.com/), for fast end efficient
    nflverse data downloads.
-   [nflplotR](https://nflplotr.nflverse.com/), for tools to create
    visualization of NFL related analysis.

## Getting help

The best places to get help on this package are:

-   the [nflverse discord](https://discord.com/invite/5Er2FBnnQa) (for
    both this package as well as anything R/NFL related)
-   opening [an
    issue](https://github.com/nflverse/nflverse/issues/new/choose)

## Contributing

Many hands make light work! Here are some ways you can contribute to
this project:

-   You can [open an
    issue](https://github.com/nflverse/nflverse/issues/new/choose) if
    you’d like to request specific data or report a bug/error.

-   If you’d like to contribute code, please check out [the contribution
    guidelines](https://nflverse.nflverse.com/CONTRIBUTING.html).

## Terms of Use

The R code for this package is released as open source under the [MIT
License](https://nflverse.nflverse.com/LICENSE.html). NFL data accessed
by this package belong to their respective owners, and are governed by
their terms of use.
