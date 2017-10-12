# Replication Materials for "A Review of Best Practice Recommendations for Text Analysis in R (and a User-Friendly App)"

## Materials

| Part | Text Analysis using Topic Modeling in R   |
| ------------------- | ------------------------------------------------------- |
| 1      | [Data Cleaning & Exploration](./01-datacleaning-exploration.Rmd) / [HTML](https://rawgit.com/wesslen/text-analysis-org-science/master/01-datacleaning-exploration.html) |
| 2      | [Topic Modeling with no covariates](./02-topicmodel-nocovariates.Rmd) / [HTML](https://rawgit.com/wesslen/text-analysis-org-science/master/02-topicmodel-nocovariates.html) |
| 3      | [Topic Modeling with covariates](./03-stm-covariates.Rmd) / [HTML](https://rawgit.com/wesslen/text-analysis-org-science/master/03-stm-covariates.html) |

Additionally, you can go to the GitHub for [topicApp](https://github.com/wesslen/topicApp/) for instructions on how to use the Shiny app instead.

## Setup and Preparation

### R Knowledge

These materials assumes you have basic knowledge of how to :

* Set your working directory
* Install R packages via CRAN
* Handle R dataframes with [`tidyverse`](http://tidyverse.org/) packages like [`ggplot`](http://ggplot2.tidyverse.org/), [`dplyr`](http://dplyr.tidyverse.org/), and [`readr`](http://readr.tidyverse.org/)
* [`rmarkdown`](http://rmarkdown.rstudio.com/articles_intro.html) knowledge
* [`quanteda`](http://quanteda.io/index.html) knowledge


### Preparation

You will need [R](https://cran.r-project.org/) and [RStudio](https://www.rstudio.com/) installed on your laptop. 

Also, please install these packages by running this code:

```{r}
packages <- c("tidyverse","stm","quanteda","RColorBrewer","wordcloud")

install.packages(packages)
```

### Downloading Materials

To download the materials, please click the "Clone or Download" button in the top right of this page. Then save the materials as a zip file onto your computer (e.g., Desktop). 

