# Practical Statistics for Data Scientists

This repository contains Python code reproductions, theoretical explanations, and chapter summaries based on the book **Practical Statistics for Data Scientists: 50+ Essential Concepts Using R and Python** (2nd Edition) by Peter Bruce, Andrew Bruce, and Peter Gedeck (O'Reilly, 2020).

This work is an individual assignment for the Machine Learning and Deep Learning enrichment class.

## Repository Structure

```
Practical-Statistics-for-Data-Scientists/
├── data/                                                   # Datasets from the official book repository
├── Chapter1_Exploratory_Data_Analysis.ipynb
├── Chapter2_Data_and_Sampling_Distributions.ipynb
├── Chapter3_Statistical_Experiments_and_Significance_Testing.ipynb
├── Chapter4_Regression_and_Prediction.ipynb
└── README.md
```

Each notebook contains:
- Reproduced Python code from the chapter, with outputs
- Theoretical explanations of each concept
- Interpretation of the results
- A summary of the chapter

## Chapter Overview

### Chapter 1: Exploratory Data Analysis
Introduces the first step of any data science project: understanding the data. Covers the types of structured data (numeric and categorical), rectangular data, estimates of location (mean, trimmed mean, median, weighted estimates), estimates of variability (standard deviation, MAD, IQR, percentiles), and visualizing distributions with boxplots, histograms, and density plots. It also covers exploring categorical data (bar charts, mode, expected value), correlation, and techniques for exploring two or more variables such as hexagonal binning, contour plots, contingency tables, violin plots, and conditioning.

### Chapter 2: Data and Sampling Distributions
Explains how samples relate to the population they come from. Covers random sampling, sample bias and selection bias, regression to the mean, the sampling distribution of a statistic, the Central Limit Theorem, and the standard error. Introduces the bootstrap for estimating uncertainty and building confidence intervals, and reviews common distributions: normal (with QQ-plots), long-tailed, Student's t, binomial, chi-square, F, Poisson, exponential, and Weibull.

### Chapter 3: Statistical Experiments and Significance Testing
Covers how to design experiments and decide whether an observed effect is real or due to chance. Topics include A/B testing, hypothesis tests, permutation tests, statistical significance and p-values, Type 1 and Type 2 errors, t-tests, multiple testing, degrees of freedom, ANOVA and the F-statistic, the chi-square test, multi-arm bandit algorithms, and power and sample size calculation.

### Chapter 4: Regression and Prediction
Covers linear regression as a tool for prediction and explanation. Topics include simple and multiple linear regression, model assessment (RMSE, R-squared), cross-validation, stepwise model selection with AIC, weighted regression, confidence and prediction intervals, factor variables and dummy coding, correlated predictors, multicollinearity, confounding variables, interactions, regression diagnostics (outliers, influential values, heteroskedasticity, partial residual plots), and nonlinear extensions such as polynomial regression, splines, and generalized additive models (GAM).

### Chapter 5: Classification
*Coming soon.*

### Chapter 6: Statistical Machine Learning
*Coming soon.*

### Chapter 7: Unsupervised Learning
*Coming soon.*

## How to Run

1. Clone this repository:
git clone https://github.com/prcliaprianaa/Practical-Statistics-for-Data-Scientists.git

2. Install the required libraries:
pip install pandas numpy scipy matplotlib seaborn statsmodels scikit-learn wquantiles dmba pygam jupyter

3. Open any notebook in Jupyter or VS Code and run all cells. The datasets are already included in the `data/` folder.

## Notes

Some code has been slightly adapted from the original book code to work with recent library versions (e.g., pandas 3), such as replacing deprecated functions and using explicit data types for dummy variables.

## References

- Bruce, P., Bruce, A., & Gedeck, P. (2020). *Practical Statistics for Data Scientists: 50+ Essential Concepts Using R and Python* (2nd ed.). O'Reilly Media.
- Official code and data repository: https://github.com/gedeck/practical-statistics-for-data-scientists

Theoretical explanations were written with the assistance of an LLM, as permitted by the assignment, and reviewed by the author.