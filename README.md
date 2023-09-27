# Pharmaceutical Analysis

## Overview

This repository contains an in-depth analysis of tumor data in mice, focusing on the effectiveness of four different drug regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. The study evaluated the final tumor volumes and their correlation with mouse weight, providing insights into potential anti-cancer treatments.

## Table of Contents

- [Data Preparation](#data-preparation)
- [Summary Statistics](#summary-statistics)
- [Bar and Pie Charts](#bar-and-pie-charts)
- [Quartiles, Outliers, and Boxplots](#quartiles-outliers-and-boxplots)
- [Line and Scatter Plots](#line-and-scatter-plots)
- [Conclusions](#conclusions)

## Data Preparation

The data was collected from a study involving 249 mice with SCC tumors. Duplicate entries and a single outlier were removed from the dataset, resulting in a clean dataset of 248 mice.

## Summary Statistics

Summary statistics were calculated for each drug regimen, including mean, median, variance, standard deviation, and SEM of the tumor volume.

## Bar and Pie Charts

Bar charts were generated to display the distribution of timepoints for each drug regimen. Pie charts were used to visualize the gender distribution among the mice in the study.

## Quartiles, Outliers, and Boxplots

The final tumor volumes for four treatment regimens (Capomulin, Ramicane, Infubinol, and Ceftamin) were analyzed. Quartiles and potential outliers were determined, and a boxplot was created to visualize the distribution of final tumor volumes.

## Line and Scatter Plots

A line plot displayed the tumor volume over time for a single mouse treated with Capomulin. Additionally, a scatter plot illustrated the relationship between mouse weight and the average observed tumor volume for the Capomulin regimen.

## Conclusions

- Capomulin and Ramicane demonstrated superior effectiveness in reducing final tumor sizes in mice.
- While Infubinol had one outlier with comparable final tumor volume to Capomulin and Ramicane, the majority of its final tumor volumes were notably higher and similar to those of Ceftamin.
- In summary, Capomulin and Ramicane proved to be the most successful in reducing tumor size in mice within this study.
- An interesting observation was made within the Capomulin group, where there exists a strong positive correlation between mouse weight and final tumor volume. This correlation is quantified with a correlation coefficient of 0.84 and an r-squared value of 0.71, indicating that as mouse weight increases, final tumor size tends to increase as well.

These findings provide valuable insights into the efficacy of different drug regimens and highlight the influence of mouse weight on tumor volume, contributing to our understanding of anti-cancer treatments in pre-clinical studies.

For detailed code and analysis, please refer to the Jupyter Notebook provided in this repository.
