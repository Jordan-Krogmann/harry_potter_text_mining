
# Text Mining Harry Potter Books

## Overview

## Set Up

To start we will need to install a package that has all the text from
each book from the *Harry Potter* series. The package is not on
**CRAN**, so we will need install the package from github.

``` r
devtools::install_github("bradleyboehmke/harrypotter")
```

Next we will be using a list of packages that will help us manipulate
and process our text data.

``` r
library(harrypotter) # for the raw text
library(tidyverse)   # data manipulation
library(tidytext)    # for text mining
```

## Data

## Exploratory Data Analysis
