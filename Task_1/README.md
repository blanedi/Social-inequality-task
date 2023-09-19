
# Excercise 3: Social Inequality

**Author:** Cintya Huaire  
**Date:** 2023-02-23

## Overview

This Rmarkdown document explores social inequality, focusing on the relationship between marital status, education, and financial difficulties among females with children in the Philippines.

## Setup

```R
knitr::opts_chunk$set(echo = TRUE)
```

### Libraries

```R
library(tidyverse)
library(dplyr)
library(haven) 
library(descr) 
library(corrplot) 
library(stargazer)
library(knitr)
library(kableExtra)
library(janitor)
```

## Data Preparation

The data used in this analysis is sourced from GESIS (2019) and focuses on the ISSP 2019 "Social Inequality V" dataset. The data is filtered for the Philippines.

```R
data_issp <- read_dta("/Users/CINTYAHUAIRE1/Downloads/Data_Exercise03.dta")
data_philipines <- data_issp %>% filter(country == 608)
data_philipines <- data_philipines[,c("country","SEX","MARITAL","DEGREE","PCLASS","CLASS","CLASS_SPOUSE","HHCHILDR","HHTODD","ISCO08","SPISCO08","WORRY")]
```

## Analysis

### Excercise 3.1.a

The analysis begins by examining the correlation between social class and perceived class using Spearman's rank correlation coefficient, separated by gender.

### Excercise 3.1.b

The next step is to explore the correlation between spousal class and perceived social class.

### Excercise 3.2.a

This section focuses on analyzing financial difficulties among females with children, considering their marital status.

### Excercise 3.2.b

A linear probability model is estimated with financial difficulties as the dependent variable.


### Excercise 3.3

This section discusses the risk of poverty among unmarried parents and provides policy recommendations to reduce lone mothers' poverty.


### Excercise 3.4

A discussion on the concept of social class and poverty at the household level.


## Annex

The annex contains the full code and additional details of the analysis.

```R
library(tidyverse)
library(dplyr)
library(haven) 
[...]
```
