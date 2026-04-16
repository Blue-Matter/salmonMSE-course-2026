
# salmonMSE workshop

Pacific Biological Station, Nanaimo, BC

April 22, 2026

## Course website (Github repository)

<https://github.com/Blue-Matter/salmonMSE-course-2026>

## Course description

This is a one-day course on the basic structure of salmonMSE, a
comprehensive decision support tool that evaluates and compares
different management levers for Pacific salmon.

Presentation materials will include an overview of the life cycle and
features included in the projection model. Demonstrations will cover
basic inputs to a single operating model, as well as more thorough
walk-through of multiple model runs to generate figures and performance
outcomes to compare management options.

Feedback and guidance from participants can inform future development of
salmonMSE.

## Software installation

The R files and Markdown files are rendered in Rstudio IDE:
<https://posit.co/products/open-source/rstudio/>

The course will require version 2.1.0 of salmonMSE which is available on
Github:

``` r
# install.packages("remotes")
remotes::install_github("Blue-Matter/salmonMSE", dependencies = TRUE)
```

The source code for salmonMSE is at:
<https://github.com/Blue-Matter/salmonMSE>

Note: salmonMSE is also available on CRAN with
`install.packages("salmonMSE")` but the CRAN version may not be up to
date when the course starts.

Other packages will be useful in the markdown exercises in this
repository:

``` r
install.packages("here")
install.packages("EnvStats")
install.packages("cowplot")
```
