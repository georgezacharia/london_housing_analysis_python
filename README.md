# London Housing Analysis with Python

## Introduction
This project involves analyzing housing data sourced from Kaggle to understand trends in average housing prices and the number of houses sold in London over time. By leveraging various data analysis techniques, we aim to uncover valuable insights into the housing market, particularly focusing on the average housing prices and the number of transactions in different areas.

## Tools Used
- **Python**: The primary programming language used for data analysis.
- **Pandas**: A powerful library for data manipulation and analysis.
- **Matplotlib**: A visualization library for creating plots and graphs.
- **Seaborn**: A statistical data visualization library that enhances Matplotlib plots.
- **Jupyter Notebook**: The environment used for interactive coding and visualization.

## Source of Dataset
The dataset utilized for this analysis is sourced from [Kaggle](https://www.kaggle.com/), providing a variety of housing-related data for analysis.

## Data Import
- **Importing the Necessary Libraries**: The essential libraries for data manipulation and visualization are imported.
- **Load the Dataset**: The housing dataset is loaded into a Pandas DataFrame.
- **Display the First Few Rows**: The first few rows of the DataFrame are displayed to understand its structure and contents.

## Initial Exploration
- **Checking Data Types**: The data types of each column are checked to ensure they are as expected.
- **Summary Statistics**: Summary statistics for the numerical columns are generated to understand the central tendency and dispersion.
- **Checking for Missing Values**: An assessment of the dataset for any missing values is conducted.
- **Filling Missing Values**: Missing values are filled using the median to maintain the integrity of the data.

## Data Analysis
### Trend of Average Housing Prices Over Time
- **Converting Date Column to Datetime**: The date column is converted to a datetime format for accurate time series analysis.
- **Plotting the Trend**: A plot is created to visualize the trend of average housing prices over time.

### Number of Houses Sold Over Time
- **Plotting Houses Sold Trend**: A plot is generated to analyze the trend of the number of houses sold over time.

### Trend of Number of Crimes Over Time
- **Plotting the Trend**: A plot is created to visualize the trend of the number of crimes recorded over time. This analysis helps identify any significant fluctuations or patterns in crime rates, which may correlate with housing prices and sales trends.
  
 ### Correlation Matrix
- **Purpose**: The correlation matrix is generated to identify relationships between numerical variables in the dataset, helping to understand how various factors are interrelated.
- **Visualization**: A heatmap is created to represent the correlation coefficients visually. This helps to quickly identify strong positive or negative correlations, which can inform further analysis or model development.

### Maximum and Minimum Analysis
- **Average Price per Year**: The maximum and minimum average housing prices per year in England are calculated and displayed.
- **Crimes Recorded per Area**: The maximum and minimum number of crimes recorded per area are analyzed to provide insights into the relationship between crime and housing prices.

## Conclusion
This analysis provides a comprehensive overview of the London housing market, revealing trends in housing prices and sales over time. The findings can serve as a valuable resource for prospective buyers, real estate professionals, and policymakers interested in understanding the dynamics of the housing market in London.
