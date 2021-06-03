<!-- README.md is generated from README.Rmd. Please edit that file -->

# joineRML <img src="man/figures/grpCox_logo.png" width = "175" height = "200" align="right" />

<!-- badges: start -->

[![CRAN version](https://img.shields.io/cran/v/grpCox?logo=R)](https://cran.r-project.org/web/packages/grpCox/index.html)
[![CRAN RStudio mirror overall downloads](http://cranlogs.r-pkg.org/badges/grand-total/grpCox)](http://www.r-pkg.org/pkg/grpCox)
[![downloads](https://cranlogs.r-pkg.org/badges/grpCox)](https://cran.r-project.org/package=grpCox)

# [Penalized Cox Model for High-Dimensional Data with Grouped Predictors](https://cran.r-project.org/web/packages/grpCox/index.html)

`grpCox` is an R package fitting the penalized Cox models with both non-overlapping and overlapping grouped penalties including the group lasso, group smoothly clipped absolute deviation (SCAD), and group minimax concave (MCP) penalty. The algorithms combine the MM approach and group-wise descent with some computational tricks including the screening, active set, and warm-start. Different tuning regularization parameter methods are provided.


### Install

* To install the latest release version from CRAN: `install.packages("grpCox")`
* To install the latest development version from GitHub: `remotes::install_github("xuandt1289/grpCox")`
