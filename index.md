---
title       : Motor Trend
subtitle    : Data Analysis
author      : Ashish Sehgal
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : standalone # {standalone, draft}
knit        : slidify::knit2slides
---

## Mtcars DataSet


1. The data was extracted from the 1974 Motor Trend US magazine.

2. Data has 32 Observations with 11 Variables.

3. Source: Henderson and Velleman (1981).

--- .class #id 

## Brief discription of dataset



```r
library(datasets)
str(mtcars)
```

```
## 'data.frame':	32 obs. of  11 variables:
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
```

--- .class #id 
## The APP

# App has three panel

1. Details:includes the details of the data set.

2. Analysis: Main Analysis of all the variable w.r.t variable mpg.

3. SourceCode: Includes the source code file link to github.

--- .class #id 
## Analysis Part

- Here we are analysing w.r.t "mpg"" vaiable so we have kept this as fixed and a dropbox is provide where we can select the variable w.r.t whome we need to analyse.

- Tabs are provided for *Boxplot* and *Regression Model* of selected variable in Dropbox with mpg.

- checkbox is provide to show Boxplot's outliers.

- plot: shows boxplot or liner regresstion model of variables.

--- .class #id 

## Visit the app


Visit the project at

(https://ashishsehgal.shinyapps.io/Shiny_project)

The Code is Open Source at

(https://github.com/AshishSehgal/Shiny_project)


