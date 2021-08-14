
<!-- README.md is generated from README.Rmd. Please edit that file -->

# desirability2

<!-- badges: start -->

[![Lifecycle:
experimental](https://img.shields.io/badge/lifecycle-experimental-orange.svg)](https://lifecycle.r-lib.org/articles/stages.html#experimental)
[![CRAN
status](https://www.r-pkg.org/badges/version/desirability2)](https://CRAN.R-project.org/package=desirability2)
[![Codecov test
coverage](https://codecov.io/gh/topepo/desirability2/branch/main/graph/badge.svg)](https://codecov.io/gh/topepo/desirability2?branch=main)
[![R-CMD-check](https://github.com/topepo/desirability2/workflows/R-CMD-check/badge.svg)](https://github.com/topepo/desirability2/actions)
<!-- badges: end -->

Desirability functions are simple but useful tools for simultaneously
optimizing several things at once. For each input, a translation
function is used to map the input values between zero and one where zero
is unacceptable and one is most desirable.

For example, [Kuhn and Johnson
(2019)](https://bookdown.org/max/FES/genetic-algorithms.html#coercing-sparsity)
use these functions during feature selection to help a genetic algorithm
choose which predictors to include in a model that simultaneously
improves performance and reduces the number of predictors.

The desirability2 package improves on the original [desirability
package](https://cran.r-project.org/package=desirability) by enabling
in-line computations that can be used with dplyr pipelines.

## Code of Conduct

Please note that the desirability2 project is released with a
[Contributor Code of
Conduct](https://contributor-covenant.org/version/2/0/CODE_OF_CONDUCT.html).
By contributing to this project, you agree to abide by its terms.
