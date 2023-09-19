# Excercise 7: Social Inequality

## Overview

This repository contains an analysis of social inequality with a focus on Intimate Partner Violence (IPV) in India. The analysis is based on the Demographics and Health Survey (DHS) database.

**Author:** Cintya Huaire  
**Date:** 2023-04-04

## Dependencies

The following R libraries are required to run the analysis:

- tidyverse
- dplyr
- haven
- descr
- corrplot
- stargazer
- knitr
- kableExtra

## Data Preparation

The data used in this analysis is sourced from the DHS database. The dataset is loaded from a local path and then cleaned to remove any missing values. Several new variables are created to aid in the analysis, including IPV, ETHNIC, CLASS, AGE, and CHILDREN.

## Analysis

The analysis is divided into three main sections:

1. **Option A**
    - A.a) Examines the share of women who report having experienced IPV.
    - A.b) Investigates the relationship between IPV and two demographic factors: education and number of children.
    - A.c) Discusses the intersectional approach to understanding IPV and its implications for policy recommendations.

2. **Annex**
    - Contains the data loading and preparation steps in detail.

## Figures

- Fig.1: Share of women who report having experienced IPV.
- Fig.2: Percentage of women that reported IPV per education attained.
- Fig.3: Percentage of mothers per number of children that reported IPV.

## References

- Bhattacharya S, Singh A, Mahapatra B. Intimate partner violence in India: An epidemiological review. Int J Community Med Public Health 2019; 6:2150-2157.
- Devries KM, Mak JY, García-Moreno C, et al. Global health. The global prevalence of intimate partner violence against women. Science 2013; 340:1527-1528.
- Fulu, E., Warner, X., Miedema, S., Jewkes, R., Roselli, T. and Lang, J.(2013). Why Do Some Men Use Violence Against Women and How Can We Prevent It? Quantitative Findings from the United Nations Multi-country Study on Men and Violence in Asia and the Pacific. Bangkok: UNDP, UNFPA, UN Women and UNV.
- [UN Women. (2019). Facts and figures: Ending violence against women.](https://www.unwomen.org/en/what-we-do/ending-violence-against-women/facts-and-figures)

