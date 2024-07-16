
# tempoR4SPISE2024

<!-- badges: start -->
<!-- badges: end -->

tempoR4SPISE2024
provides data, programs, and documentation 
for the SPISE-2024
*Advanced Workshop on Sensory Evaluation* 
(which took place from July 24, to July 25,
2022, inHo Chi Minh City Vietnam).


## Installation

You can install the development version of tempoR4SPISE2024 
 with the
following lines of code:

``` r
# if remotes is not installed, decomment the following line
# install.packages('remotes')
remotes::install_github('HerveAbdi/tempoR4SPISE2024')
```

To install the vignettes while installing the package, 
then run the
following commands:

``` r
remotes::install_github('HerveAbdi/tempoR4SPISE2024', 
  build_vignettes = TRUE,
  force = TRUE)
```

## List of functions

### Boot4Eigs    
Boostrap for eigenvalues.

### graph4epPCA    
create the graphs for a PCA analysis from `ExPosition` 
and generate the standard graphs and tables. 
Note: _Still Under Development_.

### OTAplot    
create the graphs for a PCA analysis from 'ExPosition' 
and generate the standard graphs and tables.
Note: _Still Under Development_.

### OTAplotInference    
create the graphs for a PCA analysis from 'ExPosition'
and generate the standard graphs and tables. 
Note: _Still Under Development_.

### PlotScreeWithCI    
plot the scree for the eigenvalues
of an SVD based multivariate analysis, 
and add bootstrap confidence intervals.

### PLSRplot    
core function to generate PLSR plots.

### saveAllGraphsInList2pptx    
saves all the graphics in a list into a PowerPoint file.

### TTAplot    
Core function to generate two-table analysis plots.

### TTAplotInference    
Core function to generate two-table analysis plots.

## List of data sets

To be updated soon ...


## Some Related Papers 

 * Principal Component Analysis [paper](inst/extdata/abdi-awPCA2010.pdf).
 * Partial Least Methods: A Review [paper](inst/extdata/abdi-PLSC_and_PLSR2012.pdf).
 * Canonical Correation Analysis [paper](inst/extdata/abdi2017-CanonicalCorrelationAnalysis.pdf).


## Example

This is a basic example which shows you how to solve a common problem:

``` r
library(tempoR4SPISE2024)
## basic example code
```

