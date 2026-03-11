# Statistical Analysis of Child Car Seat Sales

**Author:** Dominik Truchly  
**Date:** December 2024  
**Language:** R (R Markdown)

## Overview

This project performs a series of statistical analyses on a Child Car Seats dataset, covering hypothesis testing, correlation, regression, and classification techniques. It was completed as part of a statistics course assignment.

## Dataset

`data/ChildCarSeats.csv` — contains retail sales data for child car seats across different stores, including variables such as `Sales`, `Price`, `CompPrice`, `Advert`, `City`, and `Expensive`.

## Tasks

| Task | Method |
|------|--------|
| **Task 1** | One-way ANOVA — effect of advertisement type on sales; assumptions checked via Levene's test, Shapiro-Wilk test, and Tukey's HSD post-hoc test |
| **Task 2** | Pearson correlation matrix and variance-covariance matrix for Sales, Price, and CompPrice |
| **Task 3** | Contingency table and odds ratio analysis — association between `City` and `Expensive` |
| **Task 4** | Multiple linear regression — Sales predicted from Price and City; model diagnostics and prediction intervals |
| **Task 5** | Logistic regression — probability of a car seat being `Expensive` based on Sales |
| **Task 6** | Non-parametric comparison of Price and CompPrice medians using the Wilcoxon signed-rank test |

## Files

- `analysis.Rmd` — R Markdown source code with all analyses and explanations
- `report.html` — Rendered HTML report with outputs, plots, and interpretations


## Libraries Used

`dplyr`, `tidyr`, `ggplot2`, `Hmisc`, `ppcor`, `GGally`, `ggcorrplot`, `gridExtra`, `agricolae`, `car`, `nortest`
