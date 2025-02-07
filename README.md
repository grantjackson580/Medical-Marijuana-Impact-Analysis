# Medical Marijuana Legalization Impact Analysis

## Overview
An empirical analysis of medical marijuana legalization's impact on unemployment rates, using Oklahoma and Kansas as case studies in a difference-in-differences framework.

## Project Highlights
- Implemented difference-in-differences (DiD) analysis using Python
- Analyzed unemployment data from 2015-2023
- Controlled for multiple economic indicators
- Found statistically significant treatment effect of 0.35 percentage points

## Data Sources
- Bureau of Labor Statistics: Monthly unemployment rates
- Bureau of Economic Analysis: State GDP and personal income
- U.S. Census Bureau: Educational attainment and demographics

## Methodology
- Primary analysis: Difference-in-differences estimation
- Controls: GDP, personal income, educational attainment
- Robustness checks: Parallel trends testing, autocorrelation analysis

## Key Findings
- Treatment effect (DiD coefficient): 0.3515 (p=0.036)
- R-squared: 0.235
- Significant control variables identified in GDP and education levels

## Installation & Usage
```bash
git clone https://github.com/yourusername/medical-marijuana-unemployment-analysis
cd medical-marijuana-unemployment-analysis
pip install -r requirements.txt


