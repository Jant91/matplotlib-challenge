# Pymaceuticals Inc. Data Analysis

## Overview
Pymaceuticals Inc. is a pharmaceutical company studying cancer treatments in mice. This analysis examines their data to learn how various drugs affect tumor growth.

## Data and Tools
We used Python with libraries like matplotlib (for plotting), pandas (for data work), and scipy.stats (for stats).

```bash
python
import matplotlib.pyplot as plt
import pandas as pd
import scipy.stats as st
```

## Data Cleanup
Merged mouse metadata and study results.
Removed duplicate entries.

## Summary Statistics
Calculated average, median, variance, standard deviation, and SEM of tumor volumes for each drug regimen.
Organized these stats into a summary table.
## Bar and Pie Charts
Visualized the number of data points for each drug regimen with bar charts.
Illustrated the gender distribution of mice using pie charts.

## Quartiles, Outliers, and Boxplots
Analyzed final tumor volumes for four drug regimens (Capomulin, Ramicane, Infubinol, and Ceftamin).
Identified outliers using boxplots.

## Line and Scatter Plots
Plotted tumor volume over time for a mouse on Capomulin.
Explored the relationship between mouse weight and average tumor volume for Capomulin.

## Correlation and Regression
Checked how mouse weight relates to tumor volume using correlation and linear regression.
