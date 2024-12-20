# Project: Goldman Sachs Stock Market Analysis (1999-2022)

## Overview

This project analyzes the stock market performance of Goldman Sachs over the period 1999 to 2022 using data sourced from Kaggle. The analysis involves data cleaning using SQL and visualization using Power BI to provide insights into the stock's performance, volatility, and trends during different crisis periods, particularly focusing on the 2008 financial crisis.

## Dataset

- **Source**: Kaggle
- **Period**: 1999-2022
- **Columns**: Date, Open, High, Low, Close, Adj Close, Volume

## Analysis Phases

### 1. Data Collection and Cleaning

- Data was imported into PostgreSQL for cleaning and preparation.
- Null values were removed and data formatting ensured for analysis.

### 2. Data Upload and Visualization

- Cleaned data (`gs_1999-2022.csv`) was uploaded to Power BI.
- Visualizations included line charts, bar charts, and moving averages to highlight trends and insights.

### 3. Categorized Analysis

Data was categorized into three periods:

- **Pre-Crisis**: 1999-2007
- **During Crisis**: 2008-2009
- **Post-Crisis**: 2010-2022

## Key Findings

### Pre-Crisis Period (1999-2007)

- **Average Values**:
  - Open: 244.9k
  - High: 248.3k
  - Low: 241.6k
  - Close: 246.8k
  - Volume: 9.0 billion

### During Crisis Period (2008-2009)

- **Average Values**:
  - Open: 38.5k
  - High: 39.5k
  - Low: 37.5k
  - Close: 38.5k
  - Volume: 2.5 billion

### Post-Crisis Period (2010-2022)

- **Average Values**:
  - Open: 642.6k
  - High: 649.5k
  - Low: 635.7k
  - Close: 643.8k
  - Volume: 17.1 billion

## Percentage Change Analysis

### From Pre-Crisis to During Crisis

- Open: -84.29%
- High: -84.11%
- Low: -84.49%
- Close: -84.39%
- Volume: -72.22%

### From During Crisis to Post-Crisis

- Open: +1566.75%
- High: +1545.57%
- Low: +1592.80%
- Close: +1575.32%
- Volume: +580.00%

## Insights and Conclusion

The analysis highlights the significant impact of the 2008 financial crisis on Goldman Sachs' stock performance, with a sharp decline in average values during the crisis followed by substantial recovery and growth in the post-crisis period. Key insights include long-term resilience despite short-term volatility, increased trading volumes, and investor confidence post-crisis.

## Recommendations

Based on the analysis, consider monitoring market trends closely, particularly during economic downturns, to capitalize on recovery periods effectively.
