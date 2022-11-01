# Providence College R Workshop

This repository contains material for a workshop for learning the basic Statistics and Data Science methods using R. 


## Schedule

<br>

### Day 1 (11/5/22): The basics of using R to analyze data

1. Basics of R: navigating R/R Studio, basic programming and data structures, functions
2. Basic statistics: statistics and plots for categorical and quantitative data
3. Basic statistical methods: hypothesis tests and confidence intervals, resampling methods
4. Basic statistical modeling: regression models, analysis of variance models

<br>

### Day 2 (11/6/22): Data Science in R

1. Data manipulation using dplyr
2. Data visualization using ggplot
3. Additional topics: joining data and spatial mapping
4. Overview of more advanced features: data scraping, interactive applications


<br>


## Installing the rworkshop package

To install the `rworkshop` package that contains functions that are useful
for the workshop run the function below.

Note: we recommend you cut and paste all these commands to avoid typos.

``` r
install.packages("devtools")
devtools::install_github("emeyers/rworkshop")
```

## Initial setup using the rworkshoppackage

Once you have installed the rworkshop package, you can use this package to
install other packaged required by the class as well as LaTeX using the
`rworkshop:::initial_setup()` function shown below.

Notes:

1.  If any dialog boxes pop up, just click “ok” on them to proceed.
2.  This function might take several minutes to run so please be
    patient.
3.  If it asks you to update any existing package you can do so
    (recommended) or you can skip this.
4.  When the function is done running, if it asks you to restart R,
    please close and then reopen R Studio.

<!-- end list -->

``` r
rworkshop:::initial_setup()
```

#### Testing LaTeX has been installed

To test that LaTeX has correctly installed on your system you can run
the following command:

``` r
tinytex:::is_tinytex()
#> [1] TRUE
```

If the function returns TRUE, then you have successfully installed
LaTeX.

## Class material

All class material is in the
[ClassMaterial](https://github.com/emeyers/rworkshop/tree/main/ClassMaterial)
directory. In particular the
[ClassMaterial/slides](https://github.com/emeyers/rworkshop/tree/main/ClassMaterial/slides)
directory contains the class slides which can be useful to review what
was covered in class (these will be posted prior to the start of the workshop). 


## Resources

* [R in Action by Robert Kabacoff]()http://www.cs.uni.edu/~jacobson/4772/week11/R_in_Action.pdf is a great text for the basics of R that we will cover on the first day of the workshop.
* [R for Data Science](https://r4ds.had.co.nz/) is a great text for learning Data Science analyses in R that we will cover on the second day of the workshop.

Other useful textbooks/resources that are free online are: 
* [Open Intro](https://www.openintro.org/)
* [Beyond multiple regression](https://bookdown.org/roback/bookdown-BeyondMLR/)
* [Modern Data Science with R](https://mdsr-book.github.io/mdsr2e/)
* [Modern Dive](https://moderndive.com/)
* [Data Science in a Box](https://datasciencebox.org/)


