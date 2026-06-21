# Statistical Inference on Global Health Data: A comprehensive analysis of the WHO Life Expectancy Dataset

## 📌 Project Overview
This repository contains a comprehensive statistical analysis of global life expectancy drivers. The project investigates how various economic, geographic, and health factors influence longevity across 2,864 global observations. The analysis rigorously compares classical parametric models with robust non-parametric alternatives to ensure mathematical validity.

## 🎯 Objectives
* To determine the impact of a nation's economic status (Developed vs. Developing) on life expectancy.
* To evaluate regional disparities in global longevity.
* To construct an optimal Multiple Linear Regression (MLR) model identifying the most significant predictors of life expectancy (e.g., Schooling, GDP, BMI, Adult Mortality).
* To validate findings using distribution-free, non-parametric statistical methods when classical assumptions are violated.

## 🛠️ Tech Stack & Tools
* **Language:** R
* **Environment:** R Markdown / RStudio
* **Key Libraries:** `dplyr`, `ggplot2`, `tidyverse`, `stargazer`, `corrplot`
* **Report Generation:** LaTeX / PDF

## 📊 Methodology Highlights
This project follows a strict statistical pipeline:
1. **Data Preprocessing:** Handled missing data, engineered dummy variables for economic status, and collapsed sparse regional categories.
2. **Parametric Testing:** Conducted Welch's Two-Sample T-tests, One-Way ANOVA, and backward stepwise Multiple Linear Regression.
3. **Diagnostic Auditing:** Evaluated Variance Inflation Factors (VIF) for multicollinearity and plotted model residuals to test OLS assumptions (Normality, Homoscedasticity, Linearity).
4. **Non-Parametric Validation:** Executed Mann-Whitney U, Kruskal-Wallis, and Spearman Rank Correlation tests to robustly confirm theoretical findings after detecting left-skewness and heteroscedasticity in the raw data.

## 📂 Repository Structure
* `data/` : Contains the raw and cleaned datasets.
* `scripts/` : R scripts and R Markdown files containing the analysis pipeline.
* `plots/` : Exported diagnostic and exploratory visualizations (Density curves, Q-Q plots, etc.).
* `report/` : The final compiled LaTeX report summarizing the findings.


## ✍️ Author
**[Aquintoms]**

