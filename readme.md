# Weather Data Exploratory Data Analysis (EDA)

This repository contains an Exploratory Data Analysis (EDA) of a weather dataset. The analysis is designed to provide insights into weather patterns, trends, and relationships between various weather parameters. The code is written in Python and leverages popular data science libraries such as Pandas, NumPy, Matplotlib, and Seaborn.

## Project Structure

- **1. Weather Data.csv**: The dataset containing weather records used in this analysis.
- **eda_weather_data.ipynb**: The Jupyter notebook containing all the analysis code and visualizations.
- **README.md**: This file providing an overview of the project.

## Analysis Overview

### 1. Data Overview and Cleaning

- **Loading the Data**: The dataset is loaded from a CSV file using Pandas.
- **Initial Inspection**: The dataset is inspected for data types, missing values, and duplicate records.
- **Data Cleaning**: Any necessary cleaning steps, such as handling missing values or removing duplicates, are applied.

### 2. Statistical Summary

- **Descriptive Statistics**: A statistical summary of the dataset is generated to understand the distribution of the data.
- **Outlier Detection**: Outliers are identified in the numerical columns using the Interquartile Range (IQR) method.

### 3. Data Visualization

- **Distribution Plots**: The distribution of key weather parameters, such as temperature, humidity, wind speed, and pressure, are visualized using histograms.
- **Correlation Heatmap**: A heatmap is created to visualize the correlations between different weather parameters.

### 4. Weather Patterns and Trends

- **Monthly Average Temperature**: A plot of the monthly average temperature is generated to observe seasonal trends.
- **Seasonal Temperature Patterns**: A bar chart shows the average temperature by month, highlighting seasonal variations.

## How to Run the Code

1. Clone the repository:

2. Install the required Python libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn
   ```

3. Run the Jupyter notebook:

   ```bash
   jupyter notebook weather_eda.ipynb
   ```

4. Follow the steps in the notebook to perform the analysis.
