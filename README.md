# Module3R

Learn Machine Learning in the browser or locally in your RStudio IDE with interactive tutorials!

## Installation

You can install the development version from [GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("Sydney-Informatics-Hub/Module3R")
```

## How to run the tutorials

You can start any tutorial with:

``` r
learnr::run_tutorial("tutorial-of-choice", package = "Module3R")
```

For example:

``` r
learnr::run_tutorial("Part-1", package = "Module3R")
```

## List of available tutorials

| Tutorial | Description                                                       |
|:--------------|:--------------------------------------------------------|
| `Part 1`  | Ames housing dataset - Predict selling prices                     |
| `Part 2`  | Pima Indian Women's diabetes dataset - Predicting diabetes status |

## Code of Conduct

Please note that this package is released with a [Code of
Conduct](https://pages.github.sydney.edu.au/informatics/sih_codeofconduct/).
By contributing to this package, you agree to abide by its terms.
