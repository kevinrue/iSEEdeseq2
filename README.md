
<!-- README.md is generated from README.Rmd. Please edit that file -->

# iSEEdeseq2

<!-- badges: start -->

[![GitHub
issues](https://img.shields.io/github/issues/kevinrue/iSEEdeseq2)](https://github.com/kevinrue/iSEEdeseq2/issues)
[![GitHub
pulls](https://img.shields.io/github/issues-pr/kevinrue/iSEEdeseq2)](https://github.com/kevinrue/iSEEdeseq2/pulls)
[![Lifecycle:
experimental](https://img.shields.io/badge/lifecycle-experimental-orange.svg)](https://lifecycle.r-lib.org/articles/stages.html#experimental)
[![R-CMD-check-bioc](https://github.com/kevinrue/iSEEdeseq2/workflows/R-CMD-check-bioc/badge.svg)](https://github.com/kevinrue/iSEEdeseq2/actions)
[![Codecov test
coverage](https://codecov.io/gh/kevinrue/iSEEdeseq2/branch/main/graph/badge.svg)](https://app.codecov.io/gh/kevinrue/iSEEdeseq2?branch=main)
<!-- badges: end -->

The goal of `iSEEdeseq2` is to …

## Installation instructions

Get the latest stable `R` release from
[CRAN](http://cran.r-project.org/). Then install `iSEEdeseq2` from
[Bioconductor](http://bioconductor.org/) using the following code:

``` r
if (!requireNamespace("BiocManager", quietly = TRUE)) {
    install.packages("BiocManager")
}

BiocManager::install("iSEEdeseq2")
```

And the development version from
[GitHub](https://github.com/kevinrue/iSEEdeseq2) with:

``` r
BiocManager::install("kevinrue/iSEEdeseq2")
```

## Example

This is a basic example which shows you how to solve a common problem:

``` r
library("iSEEdeseq2")
## basic example code
```

## Citation

Below is the citation output from using `citation('iSEEdeseq2')` in R.
Please run this yourself to check for any updates on how to cite
**iSEEdeseq2**.

``` r
print(citation('iSEEdeseq2'), bibtex = TRUE)
#> 
#> To cite package 'iSEEdeseq2' in publications use:
#> 
#>   Kevin Rue-Albrecht (2022). iSEEdeseq2: iSEE Panels for DESeq2. R
#>   package version 0.99.0. https://github.com/kevinrue/iSEEdeseq2
#> 
#> A BibTeX entry for LaTeX users is
#> 
#>   @Manual{,
#>     title = {iSEEdeseq2: iSEE Panels for DESeq2},
#>     author = {Kevin Rue-Albrecht},
#>     year = {2022},
#>     note = {R package version 0.99.0},
#>     url = {https://github.com/kevinrue/iSEEdeseq2},
#>   }
```

Please note that the `iSEEdeseq2` was only made possible thanks to many
other R and bioinformatics software authors, which are cited either in
the vignettes and/or the paper(s) describing this package.

## Code of Conduct

Please note that the `iSEEdeseq2` project is released with a
[Contributor Code of
Conduct](http://bioconductor.org/about/code-of-conduct/). By
contributing to this project, you agree to abide by its terms.

## Development tools

-   Continuous code testing is possible thanks to [GitHub
    actions](https://www.tidyverse.org/blog/2020/04/usethis-1-6-0/)
    through *[usethis](https://CRAN.R-project.org/package=usethis)*,
    *[remotes](https://CRAN.R-project.org/package=remotes)*, and
    *[rcmdcheck](https://CRAN.R-project.org/package=rcmdcheck)*
    customized to use [Bioconductor’s docker
    containers](https://www.bioconductor.org/help/docker/) and
    *[BiocCheck](https://bioconductor.org/packages/3.16/BiocCheck)*.
-   Code coverage assessment is possible thanks to
    [codecov](https://codecov.io/gh) and
    *[covr](https://CRAN.R-project.org/package=covr)*.
-   The [documentation website](http://kevinrue.github.io/iSEEdeseq2) is
    automatically updated thanks to
    *[pkgdown](https://CRAN.R-project.org/package=pkgdown)*.
-   The code is styled automatically thanks to
    *[styler](https://CRAN.R-project.org/package=styler)*.
-   The documentation is formatted thanks to
    *[devtools](https://CRAN.R-project.org/package=devtools)* and
    *[roxygen2](https://CRAN.R-project.org/package=roxygen2)*.

For more details, check the `dev` directory.

This package was developed using
*[biocthis](https://bioconductor.org/packages/3.16/biocthis)*.

## Code of Conduct

Please note that the iSEEdeseq2 project is released with a [Contributor
Code of Conduct](http://bioconductor.org/about/code-of-conduct/). By
contributing to this project, you agree to abide by its terms.
