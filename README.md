# README for `main.ipynb`

## Overview

This project aims to explore and analyze relationships between screen time, sleep patterns, and weather conditions. The analysis is conducted using Python in a Jupyter Notebook (`main.ipynb`). The data used includes three datasets: `screen_time.csv`, `sleep.csv`, and `weather.csv`. This README outlines the purpose, data sources, structure, and instructions for running the notebook.

## Project Goals

1. Analyze the impact of screen time on sleep quality and duration.
2. Investigate correlations between weather conditions and screen time or sleep patterns.
3. Provide visualizations and insights to improve lifestyle decisions.

## Datasets

### 1. `screen_time.csv`
- **Description**: Contains daily screen time usage data.
- **Key Columns**:
  - `Date`: The date of screen time record.
  - `ScreenTime`: Total screen time in hours.

### 2. `sleep.csv`
- **Description**: Includes daily sleep duration and quality.
- **Key Columns**:
  - `Date`: The date of sleep record.
  - `SleepDuration`: Duration of sleep in hours.
  - `SleepQuality`: Sleep quality score (e.g., 1-10 scale).

### 3. `weather.csv`
- **Description**: Provides weather conditions for corresponding dates.
- **Key Columns**:
  - `Date`: The date of weather record.
  - `Temperature`: Daily average temperature in degrees Celsius.
  - `Condition`: Weather condition (e.g., sunny, rainy, cloudy).

## Structure of the Notebook

1. **Data Loading and Preprocessing**  
   - Load the datasets using pandas.
   - Clean and preprocess the data for analysis (e.g., handling missing values, ensuring date alignment).

2. **Exploratory Data Analysis (EDA)**  
   - Analyze individual datasets using descriptive statistics and visualizations.
   - Examine correlations between screen time, sleep, and weather.

3. **Visualizations**  
   - Generate plots (e.g., line charts, scatter plots) to reveal patterns and trends.

4. **Insights and Recommendations**  
   - Summarize findings from the analysis.
   - Provide actionable recommendations based on observed trends.

## Key Findings

- The analysis highlights potential links between high screen time and poor sleep quality.
- Weather conditions, particularly temperature, appear to influence both screen time and sleep duration.

## Future Work

- Incorporate additional features such as physical activity or diet to enhance analysis.
- Use machine learning models and larger datasets to predict sleep quality based on screen time and weather.