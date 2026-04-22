
# salmonMSE workshop

Pacific Biological Station, Nanaimo, BC

April 22, 2026

[Agenda](https://docs.google.com/document/d/1vg3pELJrL4m9CZXUUASMj_JWnyb4beDJ/edit)

## Course website (Github repository)

<https://github.com/Blue-Matter/salmonMSE-course-2026>

## Course description

This is a one-day course on the basic structure of salmonMSE, a
comprehensive decision support tool that evaluates and compares
different management levers for Pacific salmon.

Presentation materials will include an overview of the life cycle and
features included in the projection model.

Demonstrations will cover basic inputs to a single operating model, as
well as a more thorough walk-through of multiple model runs to generate
figures and performance outcomes to compare management options.

Exercises are written in Markdown and can be rendered on local
computers:
<https://github.com/Blue-Matter/salmonMSE-course-2026/tree/main/exercises>
(it is presumed that users will download or clone the entire repository)

Feedback and guidance from participants can inform future development of
salmonMSE.

## Presentations

[**1. Introduction to
salmonMSE**](https://drive.google.com/file/d/1lpIjrEL3_3HNr5EN-CvpPc-HlHuVQc9f/view?usp=sharing) -
presented by C. Holt, April 17, 2026

**2. Workshop presentation**:

[PDF
version](https://drive.google.com/open?id=1FIMyFBlXofG63XVDg5RI9iWjIwC1rurg&usp=drive_fs) -
easier to access URLs

[Powerpoint
version](https://docs.google.com/presentation/d/1oEv8GoKZPtECqwL1RHZzDRwG1P6xlcVb/edit?usp=sharing)

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
