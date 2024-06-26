# ETC5513: Assignment 1 - Public Expenditure on Education

## Overview

This repository contains the work and materials for Assignment 1 of the ETC5513 unit (Collaborative and reproducible practices), focusing on analyzing public expenditure on education across various countries. 

The aim is to understand how education spending as a share of government expenditure and GDP relates to population size and to identify disparities in education funding among different countries.

## Contents
- **Introduction:** Outlines the significance of education expenditure and its role in economic growth and development.
- **Research Question:** Investigates how a country’s spending on education correlates with its population size.
- **Data Set Introduction:** Describes the dataset used for analysis, including the variables and their characteristics.
- **Data Set Description:** Provides a summary and detailed description of the dataset, including the number of observations and variables.
- **Results:** Presents the findings from the analysis, including visualizations and interpretations of the data.
- **Conclusion:** Summarizes the key insights and potential factors influencing education spending decisions by governments.

## Data
The dataset, renamed as `education`, includes:
- Government expenditure on education as a percentage of total government expenditure.
- Government expenditure on education as a percentage of GDP.
- Population size of each country (historical estimates).
- Coverage from 1980 to 2018, with some missing data filtered out.

## Analysis
The analysis involves:
- Filtering and renaming variables in the dataset.
- Summarizing the dataset to understand the distribution of education spending across different countries.
- Visualizing the relationship between education spending and GDP, and analyzing how it varies with population size.

## Key Findings
- A positive correlation exists between countries that spend a large share of their income on education and their education prioritization within government budgets.
- No obvious pattern between population sizes and education prioritization.
- Larger countries tend to spend a smaller proportion of their government expenditure on education compared to smaller countries.
- High variability in education spending within the same population size group, indicating other influencing factors.

## Conclusion
Population size alone may not be a major determinant of education spending. Other factors such as economic development, available resources, government priorities, and demographic variables may have a greater influence. Further research is needed to explore these factors and their significance.

## How to Use This Repository
1. Clone the repository to your local machine.
2. Load the dataset (`educationspending.csv`) and the R script provided.
3. Run the analysis code to reproduce the results and visualizations.
4. Review the README and documentation for a detailed understanding of the project.

## Dependencies
- R
- tidyverse
- ggplot2
- knitr
- kableExtra
