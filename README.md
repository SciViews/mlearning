# mlearning

<!-- badges: start -->

[![R-CMD-check](https://github.com/SciViews/mlearning/workflows/R-CMD-check/badge.svg)](https://github.com/SciViews/mlearning/actions) [![Win build status](https://ci.appveyor.com/api/projects/status/github/SciViews/mlearning?branch=master&svg=true)](https://ci.appveyor.com/project/phgrosjean/mlearning) [![Coverage status](https://img.shields.io/codecov/c/github/SciViews/mlearning/master.svg)](https://codecov.io/github/SciViews/mlearning?branch=master) [![CRAN status](https://www.r-pkg.org/badges/version/mlearning)](https://cran.r-project.org/package=mlearning) [![License](https://img.shields.io/badge/license-GPL-blue.svg)](https://www.gnu.org/licenses/gpl-2.0.html) [![Lifecycle: stable](https://img.shields.io/badge/lifecycle-stable-brightgreen.svg)](https://www.tidyverse.org/lifecycle/#stable)

<!-- badges: end -->

{mlearning} rovides a unified interface to various machine learning algorithms. Confusion matrices are provided too.

## Installation

You can install the released version of {mlearning} from [CRAN](https://CRAN.R-project.org) with:

``` r
install.packages("mlearning")
```

You can also install the latest development version. Make sure you have the {remotes} R package installed:

``` r
install.packages("remotes")
```

Use `install_github()` to install the {mlearning} package from GitHub (source from **master** branch will be recompiled on your machine):

``` r
remotes::install_github("SciViews/mlearning")
```

R should install all required dependencies automatically, and then it should compile and install {mlearning}.

Latest devel version of {mlearning} (source + Windows binaries for the latest stable version of R at the time of compilation) is also available from [appveyor](https://ci.appveyor.com/project/phgrosjean/mlearning/build/artifacts).

## Further explore {mlearning}

You can get further help about this package this way: Make the {mlearning} package available in your R session:

``` r
library("mlearning")
```

Get help about this package:

``` r
library(help = "mlearning")
help("mlearning-package")
vignette("mlearning") # None is installed with install_github()
```

For further instructions, please, refer to the help pages at <https://www.sciviews.org/mlearning/>.

## Code of Conduct

Please note that the {mlearning} package is released with a [Contributor Code of Conduct](https://contributor-covenant.org/version/2/0/CODE_OF_CONDUCT.html). By contributing to this project, you agree to abide by its terms.
