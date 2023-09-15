
# Model and Algorithm Evaluation in Supervised Machine Learning (short course at the CEN 2023 Conference)

<!-- badges: start -->
<!-- badges: end -->

## Contents

This repository contains course materials from the **“Model and
Algorithm Evaluation in Supervised Machine Learning”** [short course at
the CEN 2023
Conference](https://cen2023.github.io/home/courses.html#Model_and_Algorithm_Evaluation_in_Supervised_Machine_Learning).
The html slides can be viewed here:

**<https://maxwestphal.github.io/evaluation_in_ml_cen_2023/>**

Author: Max Westphal (<max.westphal@mevis.fraunhofer.de>)

## License

This work is released under a [CC BY-SA
4.0](https://creativecommons.org/licenses/by-sa/4.0/) license.

## Issues

If you find errors or have suggestions for improvements, please create a
new issue here:

<https://github.com/maxwestphal/evaluation_in_ml_cen_2023/issues>

## Reproduction

If you are interested in reproducing the course materials (i.e. train
prediction models and produce the evaluation data), please conduct the
following steps:

- clone this repository:
  `git clone https://github.com/maxwestphal/evaluation_in_ml_cen_2023.git`
- install dependencies: `renv::activate()`
- re-produce pre-computed results: `source("scripts/_run.R)`
- render the file “slides.qmd”: `quarto::quarto_render()`

## R Version Info

``` r
R.Version()
```

    ## $platform
    ## [1] "x86_64-w64-mingw32"
    ## 
    ## $arch
    ## [1] "x86_64"
    ## 
    ## $os
    ## [1] "mingw32"
    ## 
    ## $crt
    ## [1] "ucrt"
    ## 
    ## $system
    ## [1] "x86_64, mingw32"
    ## 
    ## $status
    ## [1] ""
    ## 
    ## $major
    ## [1] "4"
    ## 
    ## $minor
    ## [1] "3.1"
    ## 
    ## $year
    ## [1] "2023"
    ## 
    ## $month
    ## [1] "06"
    ## 
    ## $day
    ## [1] "16"
    ## 
    ## $`svn rev`
    ## [1] "84548"
    ## 
    ## $language
    ## [1] "R"
    ## 
    ## $version.string
    ## [1] "R version 4.3.1 (2023-06-16 ucrt)"
    ## 
    ## $nickname
    ## [1] "Beagle Scouts"
