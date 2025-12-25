# Diabetes Risk Patterns Analysis

## Overview
This repository contains a comprehensive statistical analysis of the Pima Indians Diabetes dataset. The project investigates clinical markers, physiological trends, and genetic predispositions associated with diabetes onset in female patients of Pima Indian heritage. The analysis is conducted using R, following the principles of "Storytelling with Data" to ensure clear and impactful communication of results.

## Project Structure
- `notebook/`: Contains the primary R analysis notebook.
  - `Diabetes_Analysis.ipynb`: Master analysis notebook with exploratory data analysis, hypothesis testing, and simulations.
- `docs/`: Core documentation and academic reports.
  - `report.tex`: Professional LaTeX source for the research report.
  - `report.pdf`: Compiled clinical report summarizing findings and statistical methodology.
  - `DSAI 307_ Project Description.md`: Reformatted course project requirements and guidelines.
- `figures/`: High-resolution analytical visualizations generated during the analysis.
- `data/`: Placeholder/Reference for the `diabetes_dataset.zip`.

## Key Analytical Components

### 1. Exploratory Data Analysis (EDA)
In-depth investigation of clinical markers with direct, definitive answers to key research questions:
- **Glucose Gap**: Confirmed significant elevation in diabetic cohorts.
- **Compound Risk (Q1)**: Age and Obesity interaction shows high BMI amplifies glucose trends as patients age.
- **Blood Pressure (Q2)**: Positive correlation with BMI, shifted higher by diabetic status.
- **Insulin Dynamics (Q3)**: Log-scale relationship confirms insulin resistance variance.
- **Obesity Proxy (Q4)**: Skinfold thickness confirmed as a robust proxy for central obesity.
- **Genetic Mapping (Q5)**: Diabetes Pedigree Function serves as a definitive hereditary marker for risk.


### 2. Statistical Inference & Hypothesis Testing
Rigorous validation of metabolic differences using Welch Two Sample t-tests.
- Focused on identifying statistically significant gaps in Glucose and BMI between cohorts.
- Significance level ($\alpha$) set at 0.05.

### 3. Monte Carlo Simulations
Examination of Confidence Interval (CI) behavior under varying sampling regimes ($n=10, 15, 100$).
- Analysis of CI width and coverage rates.
- Empirical verification of the Law of Large Numbers in a clinical context.

## Authors
- Amr Yasser
- Omar Hazem
- Youssed Mohamed
- Mohamed Mourad
- Hady Saeed

## Acknowledgments
- Dataset source: Pima Indians Diabetes Dataset (Kaggle).
- Course: DSAI 307 - Statistical Inference.
- Institution: Zewail City.