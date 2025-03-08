# Matplotlib Challenge

## Visualizing Data with Matplotlib

In this challenge, I applied my skills in Matplotlib to analyze a real-world dataset and visualize meaningful insights.

## Background

I've recently joined **Pymaceuticals, Inc.**, a pharmaceutical company focused on anti-cancer medications. We're screening potential treatments for squamous cell carcinoma (SCC), a common form of skin cancer.

As a senior data analyst, I had the opportunity to work with data from a recent animal study involving 249 mice with SCC tumors. The goal was to compare the performance of Capomulin, our drug of interest, against other treatment regimens.

## Challenge Overview

Here's a quick rundown of what I did:

1. **Prepared the Data**: Merged mouse metadata and study results into a single DataFrame, ensuring no duplicate time points.
2. **Generated Summary Statistics**: Calculated mean, median, variance, standard deviation, and SEM for tumor volume across different drug regimens.
3. **Created Bar Charts and Pie Charts**: Visualized the distribution of mouse ID/timepoints and gender distribution in the study using both Pandas and Matplotlib.
4. **Identified Outliers and Created Box Plots**: Analyzed the final tumor volume for promising treatments, determined outliers, and visualized the distribution with box plots.
5. **Plotted Line and Scatter Plots**: Generated a line plot for a selected mouse treated with Capomulin and a scatter plot of mouse weight vs. average tumor volume.
6. **Calculated Correlation and Regression**: Analyzed the correlation between mouse weight and tumor volume, and plotted the linear regression model.

## Instructions

### Prepare the Data

- Merged the `mouse_metadata` and `study_results` DataFrames.
- Identified and removed any duplicate time points.
- Confirmed the number of unique mice IDs after cleaning the data.

### Generate Summary Statistics

- Created a DataFrame to calculate summary statistics (mean, median, variance, standard deviation, SEM) for each drug regimen.

### Create Bar Charts and Pie Charts

- Visualized the total number of rows (Mouse ID/Timepoints) for each drug regimen with both Pandas and Matplotlib.
- Visualized the gender distribution of the mice using both Pandas and Matplotlib.

### Calculate Quartiles, Find Outliers, and Create a Box Plot

- Analyzed the final tumor volume for Capomulin, Ramicane, Infubinol, and Ceftamin treatments.
- Determined outliers and visualized the distribution with box plots.

### Create a Line Plot and a Scatter Plot

- Plotted tumor volume vs. time point for a selected mouse treated with Capomulin.
- Plotted mouse weight vs. average tumor volume for the Capomulin treatment regimen.

### Calculate Correlation and Regression

- Calculated the correlation coefficient and linear regression model between mouse weight and average tumor volume.
- Plotted the linear regression model on the scatter plot.

## Conclusion

This challenge provided a comprehensive analysis of the SCC treatment study, highlighting the effectiveness of Capomulin and other regimens. The visualizations and statistical analyses offer valuable insights for future research and development.

---

