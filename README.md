# Exploratory Data Analysis of the Real Estate Market

## Project Overview

This project performs Exploratory Data Analysis (EDA) on a real estate market dataset containing housing prices, rental prices, listings, mortgage rates, and district-level information.

The project aims to identify trends, patterns, relationships, and anomalies within the housing market using statistical analysis and data visualization techniques.

---

# Objectives

* Understand the dataset structure and variables
* Analyze missing values and data quality issues
* Identify trends and patterns in housing prices
* Explore correlations between economic indicators and property prices
* Detect outliers and anomalies
* Perform district-wise market analysis
* Conduct statistical hypothesis testing

---

# Dataset Information

| Attribute    | Value                   |
| ------------ | ----------------------- |
| Rows         | 9804                    |
| Columns      | 13                      |
| Dataset Type | Real Estate Market Data |

---

# Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* SciPy
* Jupyter Notebook

---

# Libraries Used

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
from scipy.stats import ttest_ind
```

---

# Exploratory Data Analysis Performed

## Data Understanding

* Dataset structure analysis
* Variable type identification
* Column renaming

## Data Cleaning

* Missing value analysis
* Handling null values

## Statistical Analysis

* Descriptive statistics
* Correlation analysis
* Hypothesis testing

## Visualizations

* Correlation heatmaps
* Histograms
* Boxplots
* Time-series trend analysis
* District-wise comparisons

---

# Key Findings

* Property prices increased steadily from 2020 to 2026.
* Newbuild properties are generally more expensive than secondary properties.
* Strong positive correlations exist among property price variables.
* Mortgage rates closely follow central bank key rates.
* Premium districts exhibit significantly higher housing prices.
* Luxury properties create visible outliers in price distributions.
* Statistical testing confirmed significant differences between property categories.

---

# Hypothesis Testing

## Null Hypothesis (H0)

There is no significant difference between secondary property prices and newbuild property prices.

## Alternative Hypothesis (H1)

There is a significant difference between secondary property prices and newbuild property prices.

### Result

The p-value obtained from the t-test was significantly below 0.05, leading to rejection of the null hypothesis.

---

# Visualizations Included

* Missing Value Heatmap
* Correlation Heatmap
* Histograms
* Property Price Boxplots
* Property Price Trends Over Time
* District-Wise Price Analysis

---

# Project Structure

```text
real-estate-eda-project/
│
├── EDA_Project.ipynb
├── dataset.csv
├── report.pdf
├── README.md
└── images/
```

---

# Conclusion

The exploratory data analysis successfully identified major trends, correlations, and geographic differences within the housing market dataset.

The project demonstrates how data analysis and visualization techniques can be used to derive meaningful insights from real-world real estate data.

---

# Future Scope

Possible future improvements include:

* Predictive modeling of housing prices
* Time-series forecasting
* Machine learning applications
* Inflation-adjusted price analysis
* Geographic clustering analysis
