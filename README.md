
<!-- README.md is generated from README.Rmd. Please edit that file -->

# libminer

<!-- badges: start -->

<!-- badges: end -->

The goal of libminer is to …

## Installation

You can install the development version of libminer from
[GitHub](https://github.com/) with:

``` r
# install.packages("pak")
pak::pak("suarezalvarez/libminer")
```

## Example

This is a basic example which shows you how to solve a common problem:

``` r
library(libminer)
## basic example code
lib_summary()
#>                                                                                         Library
#> 1 /private/var/folders/bb/0fwfd_8s1t57knpddzjphwb9dc1vjs/T/RtmpHsxUr7/temp_libpath154c337e10257
#> 2                                             /Users/marsua/miniforge3/envs/raukr/lib/R/library
#>   n_packages
#> 1          1
#> 2        338
lib_summary(sizes = TRUE)
#>                                                                                         Library
#> 1 /private/var/folders/bb/0fwfd_8s1t57knpddzjphwb9dc1vjs/T/RtmpHsxUr7/temp_libpath154c337e10257
#> 2                                             /Users/marsua/miniforge3/envs/raukr/lib/R/library
#>   n_packages lib_size
#> 1          1   37.09K
#> 2        338  682.31M
```
