

`rsample` contains a set of functions that can create different types of resamples and corresponding classes for their analysis. 
The goal is to have a modular set of methods that can be used across different R packages for:
 
 * traditional resampling techniques for estimating the sampling distribution of a statistic and
 * estimating model performance using a holdout set
 
The scope of `rsample` is to provide the basic building blocks for creating and analyzing resamples of a data set but does not include code for modeling or calculating statistics. The "Examples" vignette gives demonstrations of how `rsample` tools can be used.  

The package is still in development and is not yet on CRAN. To install it, use:

```r
if (packageVersion("devtools") < 1.6) {
  install.packages("devtools")
}
devtools::install_github("topepo/rsample")
```
