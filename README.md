# Module-5-Challenge

## Data Preparation

### Merging DataFrames
- Merged mouse_metadata and study_results DataFrames into a single DataFrame.

### Identifying and Removing Duplicates
- Displayed the number of unique mice IDs in the data.
- Identified and displayed any mouse ID with duplicate time points.
- Created a new DataFrame with duplicate data removed.

## Summary Statistics

### Summary Statistics DataFrame
- Created a DataFrame of summary statistics including mean, median, variance, standard deviation, and SEM of tumor volume for each drug regimen.

## Bar Charts and Pie Charts

### Bar Charts
- Generated two bar charts showing the total number of rows (Mouse ID/Timepoints) for each drug regimen throughout the study.
    - First bar chart created with Pandas DataFrame.plot() method.
    - Second bar chart created with Matplotlib's pyplot methods.

### Pie Charts
- Generated two pie charts showing the distribution of female versus male mice in the study.
    - First pie chart created with Pandas DataFrame.plot() method.
    - Second pie chart created with Matplotlib's pyplot methods.

## Quartiles, Outliers, and Box Plot

### Calculating Quartiles and Finding Outliers
- Calculated final tumor volume for each mouse across four promising treatment regimens.
- Calculated quartiles and IQR to determine potential outliers.

### Box Plot
- Generated a box plot showing the distribution of final tumor volume for all mice in each treatment group.
- Highlighted potential outliers in the plot.

## Line Plot and Scatter Plot

### Line Plot
- Selected a single mouse treated with Capomulin and generated a line plot of tumor volume versus time point.

### Scatter Plot
- Generated a scatter plot of mouse weight versus average observed tumor volume for the entire Capomulin treatment regimen.

## Correlation and Regression

### Correlation and Linear Regression
- Calculated the correlation coefficient and linear regression model between mouse weight and average observed tumor volume for the Capomulin treatment regimen.
- Plotted the linear regression model on top of the scatter plot.

