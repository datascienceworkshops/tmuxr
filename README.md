
<!-- README.md is generated from README.Rmd. Please edit that file -->

# tmuxr <img src="man/figures/logo.png" align="right" width="100px" />

[![Travis-CI build
status](https://travis-ci.org/datascienceworkshops/tmuxr.svg?branch=master)](https://travis-ci.org/datascienceworkshops/tmuxr)
[![codecov](https://codecov.io/gh/datascienceworkshops/tmuxr/branch/master/graph/badge.svg)](https://codecov.io/gh/datascienceworkshops/tmuxr)
[![Lifecycle:
experimental](https://img.shields.io/badge/lifecycle-experimental-orange.svg)](https://www.tidyverse.org/lifecycle/#experimental)
[![CRAN\_Status\_Badge](https://www.r-pkg.org/badges/version/tmuxr)](https://cran.r-project.org/package=tmuxr)

## Overview

`tmuxr` is an R package that allows you to manage
[tmux](https://github.com/tmux/tmux/wiki) and interact with the
processes it runs. It features a pipeable API with which you can create,
control, and capture tmux sessions, windows, and panes.

## Demonstration

The recording below demonstrates various capabilities of `tmuxr` such
as: running processes, sending keys, splitting windows, and capturing
panes. Note that normally, managing tmux and the processes it runs is
done in a detached mode, so you wouldn’t see anything, but the result
would be the same.

<asciinema-player src="reference/figures/tmuxr.cast" cols="114" rows="38" poster="npt:0:52"></asciinema-player>

Have a look at [the
reference](https://datascienceworkshops.github.io/tmuxr/reference/) to
learn more about what `tmuxr` has to offer.

## Installation

The development version of `tmuxr` can be installed with:

``` r
# install.packages("remotes")
remotes::install_github("datascienceworkshops/tmuxr")
```

## Compatibility

We [regularly test](https://travis-ci.org/datascienceworkshops/tmuxr)
`tmuxr` on Ubuntu with tmux versions 2.1 through 3.1 and on macOS with
the latest version of tmux provided by Homebrew. `tmuxr` might work on
Windows using Cygwin or WSL, but we haven’t tested this.

## License

The `tmuxr` package is licensed under the MIT License.
