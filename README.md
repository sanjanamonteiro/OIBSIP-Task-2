# Unemployment Rate Data Analysis in India

## Objective

This project analyzes the unemployment rates in India, focusing on data cleaning, visualization, and exploring the effects of Covid-19 on unemployment trends.

## Steps Performed

1. **Data Loading & Initial Exploration**
   - The dataset `Unemployment in India.csv` is loaded using pandas.
   - Initial exploration includes:
     - Displaying the first few rows (`head()`).
     - Checking column info and data types (`info()`).
     - Viewing summary statistics (`describe()`).
     - Checking for missing values.

2. **Data Cleaning**
   - Rows with missing (NaN) values are dropped to ensure data quality.
   - The shape of the DataFrame is printed before and after cleaning.

3. **Date Handling**
   - If a 'Date' column exists, it is converted to pandas datetime format for time series analysis.

4. **Exploratory Data Analysis (EDA)**
   - **Unemployment Rate Over Time**: Plots the unemployment rate as a time series (national average if available).
   - **Unemployment Rate by State/Region**: Plots the average unemployment rate for each state/region using a horizontal bar chart.

5. **Visualization**
   - Uses matplotlib and seaborn for attractive and informative plotting.
   - Includes grid lines and proper axis labels for readability.

## Tools Used

- **Python**: Programming language for data analysis.
- **pandas**: For data manipulation and cleaning.
- **matplotlib & seaborn**: For data visualization and plotting.

## Outcome

- The analysis provides insights into:
  - General trends in unemployment rates across India over time.
  - State/region-wise comparison of average unemployment rates.
  - Data cleaning steps improve reliability for exploration.
  - Visualizations highlight the impact of major events such as the Covid-19 pandemic on unemployment.

## Requirements

- pandas
- matplotlib
- seaborn

Install requirements with:
```bash
pip install pandas matplotlib seaborn
```
