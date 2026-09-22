# College Graduation Rate - Regression Analysis in R

## Business Overview

Graduation rate is one of the clearest signals of an instituion's effectiveness. it affects a university's reputation, funding and accreditation standing and it is a key factor prospective students and their families weigh when choosing where to enrol. Understanding what actually drives graduation rate, beyond intuition or reputation alone, helps institutions identify which levers( financial aid, faculty investment, class sixe, alumni engagemnet) are worth prioritising.

## Problem Statement

Graduation rates vary widely across US universitites and it isn't obvious from raw numbers alone which institutions characteristics actually explain that variation and which are just noise. This project uses statistical modelling to move past surface-level assumptions and quantiy which factors genuinely predict graduation outcomes and how much of the variation they explain.

## Objectives

1. Quantify how much of the variation in graduation rate is explained by simple institutional labels versus the full set of available predictors.
2. Identify which specific features are the strongest and most statostically significant predictors of graduation rate.
3. Test whether a smaller, more efficient set of predictors can explain nearly as much variation as the full model, using formal variable selection.
4. Check the model's underlying assumptions (linearity,normality of residuals, homoscedasticity, influential outliers) and use that diagnosis to improve the fit through transformations and non-linear terms where the assumptions are violated.

## Approach

* **Exploratoty analysis** - summarising and visualisaing key financial and institutional variables.
* **Linear regression** - from a simple two-predictor model up to a full 16 predictor model, compared formally with ANOVA.
* **Model diagnostics** - residual vs. fitted, Q-Q, scale-location and leverage /Cook's distance plots to check assumptions and flag influential points.
* **Variables selection** - backwars stepwise selection, comparing RSS, adjusted R-squared, Cp and BIC
* **Model improvement** - polynomial terms and log transformations to address non-linearity and diagnostics.

### Files

| File                                                                               | Description                                        |
| ---------------------------------------------------------------------------------- | -------------------------------------------------- |
| [`MA717.Rmd`](MA717.Rmd)                                                           | R Markdown source. All code, output and analysis |
| [`college-graduation-rate-regression.pdf`](college-graduation-rate-regression.pdf) | Knitted output                                     |
| [`College.csv`](College.csv)                                                       | Dataset                                            |


   
