
RStartHere
==========

A guide to some of the most useful R Packages that we know about, organized by their role in data science.

[Click here to suggest packages.](https://github.com/rstudio/RStartHere/edit/master/README.Rmd)

Data Science Workflow
---------------------

Each data science project is different, but each follows the same general steps. You:

!["The data science workflow"](data-science.png)

1.  [Import](#import) your data into R
2.  [Tidy](#tidy) it
3.  Understand your data by iteratively
    1.  [visualizing](#visualize)
    2.  [tranforming](#transform) and
    3.  [modeling](#modelinfer) your data

4.  [Infer](#infer) how your understanding applies to other data sets (*including future data, i.e. predictions*)
5.  [Communicate](#communicate) your results to an audience, or
6.  [Automate](#automate) your analysis for easy reuse
7.  [Program](#program) the whole way through, since you do each of these things on a computer

Below we list the most useful R packages that we know of for each step.

Import
------

These packages help you import data into R and save data.

-   feather
-   readr
-   readxl
-   haven
-   httr
-   rvest
-   xml2
-   webreadr
-   cellranger
-   DBI
-   RMySQL
-   RPostgres
-   RSQLite
-   bigrquery
-   dplyr
-   PivotalR
-   RCurl
-   sparkr

Tidy
----

These packages help you wrangle your data into a form that is easy to analyze in R.

-   tidyr
-   dplyr
-   fortify
-   broom

Visualize
---------

These packages help you visualize your data.

-   bigvis
-   ggplot2
-   scales
-   ggthemes
-   extrafont
-   lvplot
-   ggmap
-   ggvis
-   ggstat
-   gggeom
-   manipulate
-   htmlwidgets
-   leaflet
-   dygraphs
-   plotly
-   rbokeh
-   Highcharter
-   visNetwork
-   networkD3
-   d3heatmap
-   rCharts
-   threejs
-   rglwidget
-   DiagrammeR
-   MetricsGraphics

Transform
---------

These packages help you transform your data into new types of data.

-   dplyr
-   stringr
-   lubridate
-   strptimer
-   plyr
-   tibble

Model/Infer
-----------

These packages help you build models and make inferences. Often the same packages will focus on both topics.

-   R (base R)
-   meifly
-   classify
-   clusterfly
-   broom
-   lme4
-   caret
-   glmnet

Communicate
-----------

These packages help you communicate the results of data science to your audiences.

-   rmarkdown
-   knitr
-   flexdashboard
-   bookdown
-   rticles
-   tufte
-   DT
-   staticdocs

Automate
--------

These packages help you create data science products that automate your analyses.

-   shiny
-   shinydashboards
-   shinythemes
-   shinySignals
-   shinyapps
-   shinyAce
-   shinyjs
-   miniUI
-   rsconnect
-   plumber
-   countdown
-   rstudioapi

### Program

These packages make it easier to program with the R language.

-   RStudio IDE
-   devtools
-   magrittr
-   packrat
-   testthat
-   assertthat
-   roxygen2
-   lazyeval
-   purrr
-   monads
-   memoise
-   hadladdin
-   profr
-   profvis
-   lineprof
-   pryr
-   rcpp
-   R6
-   htmltools
-   vtest
-   httpuv

Data
----

These packages contain data sets to use as training data or toy examples.

-   babynames
-   neiss
-   yrbss
-   nycflights13
-   hflights
-   USAboundaries
-   rworldmap
-   usdanutrients
-   fueleconomy
-   nasaweather
-   mexico-mortality
-   data-movies
-   pop-flows
-   data-housing-crisis
-   gun-sales
-   stationaRy
-   ggenealogy
-   15-state-of-the-union
