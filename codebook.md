`Course Project` Regression Models
================

-   π¨π»βπ» Author: Anderson H Uyekita
-   π Specialization: <a
    href="https://www.coursera.org/specializations/data-science-statistics-machine-learning"
    target="_blank" rel="noopener">Data Science: Statistics and Machine
    Learning Specialization</a>
-   π Course:
    <a href="https://www.coursera.org/learn/regression-models"
    target="_blank" rel="noopener">Regression Models</a>
    -   π§βπ« Instructor: Brian Caffo
-   π Week 4
    -   π¦ Start: Tuesday, 05 July 2022
    -   π Finish: Saturday, 09 July 2022
-   π Rpubs: [Interactive
    Document](https://rpubs.com/AndersonUyekita/regression-models_reproducible-research)
-   π Instructions: [Project Instructions](./instructions.md)
-   π README: [README.md](./README.md)

------------------------------------------------------------------------

## Codebook

According to the [R
Documentation](https://stat.ethz.ch/R-manual/R-devel/library/datasets/html/mtcars.html)

### Description

> Henderson and Velleman (1981) comment in a footnote to Table 1:
> βHocking \[original transcriber\]βs noncrucial coding of the Mazdaβs
> rotary engine as a straight six-cylinder engine and the Porscheβs flat
> engine as a V engine, as well as the inclusion of the diesel Mercedes
> 240D, have been retained to enable direct comparisons to be made with
> previous analyses.β

### Dimensions

-   Observations: 32
-   Variables: 11

### `str`

    ## 'data.frame':    32 obs. of  11 variables:
    ##  $ mpg : num  21 21 22.8 21.4 18.7 18.1 14.3 24.4 22.8 19.2 ...
    ##  $ cyl : num  6 6 4 6 8 6 8 4 4 6 ...
    ##  $ disp: num  160 160 108 258 360 ...
    ##  $ hp  : num  110 110 93 110 175 105 245 62 95 123 ...
    ##  $ drat: num  3.9 3.9 3.85 3.08 3.15 2.76 3.21 3.69 3.92 3.92 ...
    ##  $ wt  : num  2.62 2.88 2.32 3.21 3.44 ...
    ##  $ qsec: num  16.5 17 18.6 19.4 17 ...
    ##  $ vs  : num  0 0 1 1 0 1 0 1 1 1 ...
    ##  $ am  : num  1 1 1 0 0 0 0 0 0 0 ...
    ##  $ gear: num  4 4 4 3 3 3 3 4 4 4 ...
    ##  $ carb: num  4 4 1 1 2 1 4 2 2 4 ...

### Variables Description

-   `mpg` : Miles/(US) gallon
-   `cyl` : Number of cylinders
-   `disp` : Displacement (cu.in.)
-   `hp` : Gross horsepower
-   `drat` : Rear axle ratio
-   `wt` : Weight (1000 lbs)
-   `qsec` : 1/4 mile time
-   `vs` : Engine (0 = V-shaped, 1 = straight)
-   `am` : Transmission (0 = automatic, 1 = manual)
-   `gear` : Number of forward gears
-   `carb` : Number of carburetors

### Summary

    ##       mpg             cyl             disp             hp       
    ##  Min.   :10.40   Min.   :4.000   Min.   : 71.1   Min.   : 52.0  
    ##  1st Qu.:15.43   1st Qu.:4.000   1st Qu.:120.8   1st Qu.: 96.5  
    ##  Median :19.20   Median :6.000   Median :196.3   Median :123.0  
    ##  Mean   :20.09   Mean   :6.188   Mean   :230.7   Mean   :146.7  
    ##  3rd Qu.:22.80   3rd Qu.:8.000   3rd Qu.:326.0   3rd Qu.:180.0  
    ##  Max.   :33.90   Max.   :8.000   Max.   :472.0   Max.   :335.0  
    ##       drat             wt             qsec             vs        
    ##  Min.   :2.760   Min.   :1.513   Min.   :14.50   Min.   :0.0000  
    ##  1st Qu.:3.080   1st Qu.:2.581   1st Qu.:16.89   1st Qu.:0.0000  
    ##  Median :3.695   Median :3.325   Median :17.71   Median :0.0000  
    ##  Mean   :3.597   Mean   :3.217   Mean   :17.85   Mean   :0.4375  
    ##  3rd Qu.:3.920   3rd Qu.:3.610   3rd Qu.:18.90   3rd Qu.:1.0000  
    ##  Max.   :4.930   Max.   :5.424   Max.   :22.90   Max.   :1.0000  
    ##        am              gear            carb      
    ##  Min.   :0.0000   Min.   :3.000   Min.   :1.000  
    ##  1st Qu.:0.0000   1st Qu.:3.000   1st Qu.:2.000  
    ##  Median :0.0000   Median :4.000   Median :2.000  
    ##  Mean   :0.4062   Mean   :3.688   Mean   :2.812  
    ##  3rd Qu.:1.0000   3rd Qu.:4.000   3rd Qu.:4.000  
    ##  Max.   :1.0000   Max.   :5.000   Max.   :8.000

### Source

> Henderson and Velleman (1981), Building multiple regression models
> interactively. Biometrics, 37, 391β411.

### Exploratory

![](codebook_files/figure-gfm/unnamed-chunk-3-1.png)<!-- -->

![](codebook_files/figure-gfm/unnamed-chunk-4-1.png)<!-- -->

![](codebook_files/figure-gfm/unnamed-chunk-5-1.png)<!-- -->

------------------------------------------------------------------------

![](codebook_files/figure-gfm/unnamed-chunk-6-1.png)<!-- -->

![](codebook_files/figure-gfm/unnamed-chunk-7-1.png)<!-- -->

![](codebook_files/figure-gfm/unnamed-chunk-8-1.png)<!-- -->
