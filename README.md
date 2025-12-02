# ERHS_535_Homework 5

# Homework 5 – Washington Post Homicides

This repository contains my work for Homework 5 from ***ERHS 535 (R Programming for Research)***.  
The homework uses the Washington Post dataset on homicides in major U.S. cities and applies all the knowledge learned in the class.

## Overview

The homework focuses on:

### Choice 2 – Monthly Homicides in Baltimore

- Filters the data to homicides in **Baltimore, MD**.
- Aggregates homicides to **monthly counts** and classifies months into:
  - **Winter** (November–April)
  - **Summer** (May–October)
- Computes a **centered moving average** of monthly homicides.
- Produces a time-series plot with:
  - Bars for monthly homicide counts.
  - A line for the moving average.
  - A red dashed vertical line for the **arrest of Freddie Gray**.
  - Seasonal coloring for summer vs winter months.

## Main files

- `ERH_535 HW5_JAGonzales.Rmd` – R Markdown file that imports the data, creates the figures, and includes short written descriptions.
- `ERH_535 HW5_JAGonzales.pdf` – PDF report knit from the R Markdown file.
- `homicide-data.csv` – Washington Post homicide data.

## How to reproduce the report

1. Open this project in RStudio.
2. Make sure `homicide-data.csv` is available in the `data/` folder.
3. Install needed packages if necessary:


Prepared by: JAGonzales
