# Visualization of Iris Dataset by R

<img src="images/Three-species-of-IRIS-flower.png" width="1000" >

## Introduction



## Notebook

You can include R code in the document as follows:

```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = TRUE)
library(hrbrthemes)
library(tidyverse)
library(ggridges)
library(ggthemes)
library(cowplot)
library(viridis)
library(GGally)
```

``` r
dados <- read.csv("input/iris/Iris.csv")
head(dados, 6)
summary(dados)
```

## [To See The Complete Exercise](https://xweih.github.io/iris/)



