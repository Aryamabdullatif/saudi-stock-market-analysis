# Saudi Stock Market Analysis

This project explores stock market behavior in the Saudi Stock Exchange (Tadawul) using exploratory data analysis techniques.

## Objectives

The goal of this project is to analyze stock market performance, identify patterns in trading activity, and understand relationships between different market variables.

## Dataset

The dataset contains historical trading data from the Saudi Stock Exchange (Tadawul).

Main features include:

- open
- high
- low
- close
- volume_traded
- value_traded
- no_trades
- sector
- change
- perc_change

## Analysis Performed

The analysis includes several stages:

### Data Cleaning
- Checking missing values
- Checking duplicate records
- Verifying data types

### Feature Engineering
- Calculating daily stock returns using percentage change

### Top Gainers & Losers
- Identifying the best and worst performing companies based on percentage price change

### Volatility Analysis
- Measuring stock volatility using the standard deviation of daily returns

### Trading Activity Analysis
- Analyzing average trading volume across different days of the week

### Sector Analysis
- Examining the distribution of companies across different sectors

### Correlation Analysis
- Investigating relationships between price variables and trading activity indicators

### Dashboard
- Creating a visual dashboard summarizing key insights from the analysis

## Key Findings

- Price variables (open, high, low, close) show extremely strong correlations.
- Trading activity indicators (volume, value traded, number of trades) are strongly related.
- The Financial sector dominates the Saudi stock market in terms of number of companies.
- Some companies exhibit significantly higher volatility than others.
- Trading volume varies across days of the week.

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

## Author

  Aryam Aljarallah
