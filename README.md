
# World Bank Economic Analysis

## Overview
This project analyzes global economic trends using data from the World Bank. It explores GDP trends, population growth, and life expectancy and applies forecasting and clustering techniques to identify trends and group countries by economic indicators.

## Project Structure
- **data**: Contains the dataset (`world_bank_data.csv`) used in the analysis.
- **R**:
  - `1_data_preprocessing.R`: Preprocesses and cleans the data.
  - `2_exploratory_analysis.R`: Conducts exploratory data analysis (EDA).
  - `3_time_series_forecasting.R`: Builds time series models to forecast economic indicators.
  - `4_country_clustering.R`: Clusters countries based on economic indicators.

## Data Preprocessing
The dataset was filtered for relevant years, missing values were handled, and columns were standardized to improve data quality.

## Methods
1. **Time Series Forecasting**: Forecasts future GDP for selected countries using ARIMA.
2. **Country Clustering**: Clusters countries by GDP, life expectancy, and population growth.

## Results
- **GDP Trends**: Observed GDP growth trends over time for countries like the United States, China, and India.
- **Population Growth**: Analyzed population growth rates, revealing contrasting trends between countries.
- **Country Clusters**: Identified groups of countries with similar economic characteristics.

## Requirements
- R version 4.0 or higher
- Libraries: `dplyr`, `readr`, `ggplot2`, `forecast`, `cluster`


