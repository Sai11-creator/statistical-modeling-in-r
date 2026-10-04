# Statistical Modeling in R: Multiple Linear Regression and ANCOVA

This repository contains an academic statistics project completed in R and awarded full marks. It presents two applied modeling case studies:

1. **Multiple linear regression on prostate cancer data** — exploratory analysis, manual OLS estimation, inference, variable selection, confidence and prediction intervals, and model diagnostics.
2. **ANCOVA for infusion-system alarm delays** — transformation of the flow-rate relationship, system-specific regression lines, nested-model testing, model selection, diagnostics, and confidence intervals.

## What this project demonstrates

- Exploratory data analysis in R
- Multiple linear regression
- Matrix-based OLS estimation
- Statistical inference and F-tests
- Confidence and prediction intervals
- AIC/BIC model selection
- Residual diagnostics
- ANCOVA and interaction terms
- Nested-model comparison
- Reproducible reporting with R Markdown

## Files

- `statistical_modeling_in_R.Rmd` — complete analysis and report
- `Prostate.txt` — prostate dataset expected by the analysis
- `perfusion.txt` — infusion-system dataset expected by the analysis

## R packages

The analysis uses the following packages in addition to base R:

```r
corrplot
MASS
lattice
```

To render the report from RStudio, open `statistical_modeling_in_R.Rmd` and use **Knit**. The source report is configured to support HTML, PDF, and Word output.

## Notes

The R code from the original academic submission has been preserved. The report structure and explanatory text have been rewritten in English for clarity and portfolio presentation.
