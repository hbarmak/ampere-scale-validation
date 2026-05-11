# ampere-scale-validation
Reproducible psychometric validation pipeline for the AMPERE Scale using R, Quarto, EFA, CFA, Rasch modeling, and survey-quality checks.
# AMPERE Scale Validation

## Project Overview

The AMPERE Scale is a domain-specific instrument designed to measure adaptive and maladaptive perfectionism among engineering students.

This repository demonstrates a fully reproducible psychometric validation workflow using R and Quarto, including:

- Data cleaning and quality checks
- Missing data review
- Reliability analysis
- Exploratory Factor Analysis
- Confirmatory Factor Analysis
- Rasch modeling
- Validity evidence using related perfectionism and decision-making constructs
- Exported tables and figures for reporting

## Why This Project Matters

Engineering students often experience high standards, pressure, fear of mistakes, and decision avoidance. This project shows how survey data can be transformed into interpretable psychometric evidence and actionable student-support insights.

## Guiding Question

How can adaptive and maladaptive perfectionism in engineering students be measured reliably and interpreted in relation to decision avoidance?

## Tools Used

- R
- Quarto
- lavaan
- psych
- mirt or eRm
- tidyverse
- ggplot2
- semPlot
- SQL
- Power BI-ready outputs

## Repository Structure

[explain folders here]

## Reproducibility

To reproduce the analysis:

```r
renv::restore()
source("scripts/00_generate_simulated_data.R")
source("scripts/02_clean_data.R")
source("scripts/05_efa.R")
source("scripts/06_cfa.R")
source("scripts/07_rasch_analysis.R")
