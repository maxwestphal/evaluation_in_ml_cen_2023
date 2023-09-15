
# Model and Algorithm Evaluation in Supervised Machine Learning (short course materials from CEN 2023 Conference)

<!-- badges: start -->
<!-- badges: end -->

## Contents

This repository contains course materials from the

<center>

**“Model and Algorithm Evaluation in Supervised Machine Learning”**
</br> [short course at the CEN 2023
Conference](https://cen2023.github.io/home/courses.html#Model_and_Algorithm_Evaluation_in_Supervised_Machine_Learning).

</center>

The rendered html slides can be accessed here:

<center>

**<https://maxwestphal.github.io/evaluation_in_ml_cen_2023/>**

</center>

Author: [**Max Westphal**](https://www.linkedin.com/in/maxwestphal/)
(<max.westphal@mevis.fraunhofer.de>)

## License

This work is released under a [CC BY-SA
4.0](https://creativecommons.org/licenses/by-sa/4.0/) license.

## Issues

If you find an error or have suggestions for improvements, please create
a new issue here:

<https://github.com/maxwestphal/evaluation_in_ml_cen_2023/issues>

## Reproduction

If you are interested in reproducing the course materials (i.e. train
prediction models and produce the evaluation data), please conduct the
following steps:

- clone this repository:
  `git clone https://github.com/maxwestphal/evaluation_in_ml_cen_2023.git`
  \[terminal\]
- install dependencies: `renv::activate()` \[R\]
- re-produce pre-computed results: `source("scripts/_run.R)` \[R\]
- render the file “slides.qmd”: `quarto::quarto_render()` \[terminal\]

## R Version Info

``` r
str(R.Version())
```

    ## List of 15
    ##  $ platform      : chr "x86_64-w64-mingw32"
    ##  $ arch          : chr "x86_64"
    ##  $ os            : chr "mingw32"
    ##  $ crt           : chr "ucrt"
    ##  $ system        : chr "x86_64, mingw32"
    ##  $ status        : chr ""
    ##  $ major         : chr "4"
    ##  $ minor         : chr "3.1"
    ##  $ year          : chr "2023"
    ##  $ month         : chr "06"
    ##  $ day           : chr "16"
    ##  $ svn rev       : chr "84548"
    ##  $ language      : chr "R"
    ##  $ version.string: chr "R version 4.3.1 (2023-06-16 ucrt)"
    ##  $ nickname      : chr "Beagle Scouts"
