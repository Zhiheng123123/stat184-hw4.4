# STAT 184 — hw4.3 Data Analysis

## About This Project
This repository contains my reproducible data analysis report for STAT 184 at Penn State, submitted as 
HW #4.3. The report is built in Quarto and rendered to PDF, which has three analysis.
1. Busiest Airports Analysis : Passenger traffic trends at six major 
   international airports from 2020 to 2025, visualized with a summary 
   table and a line plot.
2. Monte Carlo Numerical Integration: Estimation of the Beta(2, 2) 
   density integral using Monte Carlo sampling at four sample sizes, 
   shown through a small-multiple visualization.
3. Planning and Prompting GenAI Tools: A comparison between a 
   detailed, plan-based prompt and a generic prompt when using 
   Claude to tidy and visualize a dataset.

## Data Sources
1.Airport passenger traffic: Manually compiled from Wikipedia's annual 
  "World's busiest airports by passenger traffic" articles (2020–2025). 
2.Beta(2, 2) simulation: generated inside the QMD using base R's 
  `runif()` and the `dbeta()` density function. 
3.Calcium data (`calcium.csv`): Ongitudinal study of 31 women over 
  four years, measuring ulnar calcium via photon absorptiometry. Data 
  is from stat184 class.

## Current Plan
See [`PLAN.md`] for the full project and repository plan, including goals, needs, and step-by-step actions.

## Repository Organization
stat184-hw44/
-README.md        # Project overview
-PLAN.md          # Project and repo plan
-hw4_3.qmd        # Quarto source file
-hw4_3.pdf        # Rendered PDF output
-calcium.csv      # Data for section 3
-.gitignore

## Reproducing the Report
1. Clone this repository.
2. Open `hw4_3.qmd` in RStudio with Quarto installed.
3. Install the R packages `tidyverse` and `kableExtra` if not already 
   installed.
4. Click **Render**

## Contact
1.Author: Zhiheng Wang
2.Institution: Penn State University, College of Information Sciences 
  and Technology
3.GitHub: [@zhiheng123123](https://github.com/zhiheng123123)
