# Mouse Tumor Volume Analysis

## Overview
This repository contains the analysis of tumor volumes in mice subjected to different drug regimens, including Capomulin, Ramicane, Infubinol, and Ceftamin. The study aims to understand the effectiveness of these treatments on tumor growth.

## Data
The analysis is based on two key datasets:
1. `Mouse_metadata.csv`: Contains information about the mice, including mouse ID, drug regimen, sex, age, and weight.
2. `Study_results.csv`: Records the results of the study, including tumor volume measurements at various timepoints.

## Analysis
The analysis includes the following key components:
- **Data Cleaning**: Identifying and removing duplicate data entries.
- **Summary Statistics**: Computing statistical measures such as mean, median, variance, standard deviation, and SEM of the tumor volumes for each drug regimen.
- **Bar and Pie Charts**: Visualizing the data distribution, including the number of measurements for each drug regimen and the distribution of female versus male mice.
- **Box Plots**: Comparing the final tumor volumes across the four treatment regimens.
- **Line Plot**: Observing tumor volume changes over time for a single mouse treated with Capomulin.
- **Scatter Plot and Correlation**: Analyzing the relationship between mouse weight and average tumor volume in the Capomulin regimen.

## Findings
Key findings of the study include:
- The effectiveness of Capomulin and Ramicane in reducing tumor size.
- A strong correlation between mouse weight and tumor volume in the Capomulin treatment.
- Identification of potential outliers in the Infubinol regimen.

## Technologies Used
- Python
- Pandas Library
- Matplotlib for visualizations
- Jupyter Notebooks
