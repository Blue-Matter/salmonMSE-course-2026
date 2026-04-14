
# salmonMSE workshop

Pacific Biological Station, Nanaimo, BC

April 22, 2026

## Course website (Github repository)

<https://github.com/Blue-Matter/salmonMSE-course-2026>

## Course description

This is a one-day course on the basic structure of salmonMSE, a
comprehensive decision support tool that evaluates and compares
different management levers for Pacific salmon. Presentation materials
will include an overview of the life cycle and features included in the
projection model. Demonstrations will cover basic inputs to a single
operating model, as well as more thorough walk-through of multiple model
runs to generate figures and performance outcomes to compare management
options. Feedback and guidance from participants can inform future
development of salmonMSE.

## Software installation

The R files and Markdown files are rendered in Rstudio IDE:
<https://posit.co/products/open-source/rstudio/>

The salmonMSE package (version 2.0.0) can be downloaded on CRAN:

``` r
install.packages("salmonMSE", dependencies = TRUE)
```

The source code for salmonMSE is located on Github:
<https://github.com/Blue-Matter/salmonMSE>

In case, there are any updates during the workshop, we can download a
developmental version on Github with:

``` r
# install.packages("remotes")
remotes::install_github("Blue-Matter/salmonMSE", dependencies = TRUE)
```
