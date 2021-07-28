
<!-- README.md is generated from README.Rmd. Please edit that file -->

# R Shiny app for management data input

<!-- badges: start -->

<!-- badges: end -->

An app for keeping track of field activity in the [Field
Observatory](https://www.fieldobservatory.org) project. Built using
[Shiny](http://shiny.rstudio.com/) and
[Golem](https://thinkr-open.github.io/golem/), the application allows
farmers to enter information about common farming events like tillage,
sowing and harvest. These event data are stored in .json files, which
mostly follow the ICASA standards for agricultural
data.

## Installation

<!-- You can install the released version of fieldactivity from [CRAN](https://CRAN.R-project.org) with:

``` r
install.packages("fieldactivity")
``` 
-->

You can install the app from [GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("Ottis1/fieldactivity")
```

## Example

To run the app, call run\_app with a named argument to supply the folder
to store the generated files:

``` r
library(fieldactivity)
run_app(json_file_path = "~/my_json_file_folder")
```

<!-- What is special about using `README.Rmd` instead of just `README.md`? You can include R chunks like so:


```r
summary(cars)
#>      speed           dist       
#>  Min.   : 4.0   Min.   :  2.00  
#>  1st Qu.:12.0   1st Qu.: 26.00  
#>  Median :15.0   Median : 36.00  
#>  Mean   :15.4   Mean   : 42.98  
#>  3rd Qu.:19.0   3rd Qu.: 56.00  
#>  Max.   :25.0   Max.   :120.00
```

You'll still need to render `README.Rmd` regularly, to keep `README.md` up-to-date. `devtools::build_readme()` is handy for this. You could also use GitHub Actions to re-render `README.Rmd` every time you push. An example workflow can be found here: <https://github.com/r-lib/actions/tree/master/examples>.

You can also embed plots, for example:

<img src="man/figures/README-pressure-1.png" width="100%" />

In that case, don't forget to commit and push the resulting figure files, so they display on GitHub and CRAN. -->
