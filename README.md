# NWSL Player Impact & Efficiency Analysis (2024)
This project analyzes player performance in the 2024 NWSL season with custom metrics and regression models to identify key offensive contributors.

# Dataset
Sourced from Kaggle - NWSL 2024 Player Stats.

# How to Run
1. Clone this repo
2. Place the data file in the `data/` folder
3. Open and knit `nwsl_analysis.Rmd`
4. View the HTML report

**Overview**
This project analyzes 2024 NWSL player statistics to evaluate offensive performnace and effiviency. The goal was to identify key predictors of goal production and develop a custom player ranking metric.

**Tools Used**
- R
- dplyr
- ggplot2
- Linear Regression

**Key Features**
- Data cleaning and filtering (300+ minutes threshold)
- Engineered goal conversion and contribution metrics
- Designed a weighted Player Impact Score
- Built regression model to evaluate scoring predictors
- Created visualizations to rank top-performing players

**Key Insight**
Offensive impact is driven by a combination of shot volume and finishing efficiency, rather than playing time alone.
