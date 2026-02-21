# Top 5 saudi stock dashboard

## Project Overview

This project presents an interactive investment dashboard analyzing the performance, growth, and risk of major Saudi stock market companies. The objective is to help investors and stakeholders quickly evaluate investment quality, compare company performance, and understand price trends over time.

The dashboard focuses on answering key investment questions:

- Which companies show the strongest average performance?
- Which companies have higher or lower risk (volatility)?
- What is the historical price trend for each company?
- Which companies offer more stable investment opportunities?

By combining performance, growth, and risk metrics, the dashboard provides a clear and actionable overview to support investment decision-making.

## Data Source

The dataset contains historical stock price data for major Saudi companies, including:

- Company name
- Closing price
- Date
- Historical price records over multiple years

From this raw data, additional metrics were calculated, including:

- Average price (performance indicator)
- Maximum price (peak performance)
- Minimum price (worst price point)
- Volatility (risk indicator)
- Investment Quality Score (performance relative to risk)


## Steps & Methodology

The following steps were performed:

## Data Preparation

- Cleaned and formatted date fields to enable time-series analysis
- Converted numeric fields to correct data types for calculations
- Structured data for time-series visualization
- Ensured consistency across all company records
- Added company names to the dataset to enable company-level comparison and filtering

## Calculated Metrics

Custom calculated fields were created:

- Average Price → investment performance indicator
- Max Price → highest achieved value
- Min Price → lowest price point (risk exposure)
- Volatility → standard deviation of price (risk measurement)
- Investment Quality Score → performance relative to volatility

These metrics allow direct comparison between companies.

## Tool Selection

Looker Studio was used because it provides:
- Interactive filtering
- Real-time dashboard capabilities
- Professional visualization components
- Easy sharing via live dashboard links

## Dashboard Design Decisions

The dashboard was structured into key sections:

- Top KPI Cards:

  - Investment Quality Score
  - Volatility
  - 5-Year Growth
  - Worst Price Point

- Visual Analysis:

  - Risk comparison across companies
  - Price trend over time
  - Company performance ranking

- Summary Table:

  - High Price
  - Low Price
  - Average Price
  - Volatility


## Key Insights

Several important insights were identified:

- Al Rajhi Bank shows the strongest overall performance based on average price.
- Aramco demonstrates relatively lower volatility, indicating more stable performance.
- Higher average price does not always mean lower risk.
- Some companies show stronger growth trends but also higher volatility.
- This highlights the importance of evaluating both performance and risk together.


## Live Dashboard

View the interactive dashboard here:
(https://lookerstudio.google.com/s/ryNBeEkPVkI)



## Assumptions & Limitations

- Assumptions:

  - Closing price was used as the primary performance indicator
  - Volatility was calculated using standard deviation
  - Historical price reflects investment performance trends

- Limitations:

  - External market factors were not included
  - Dataset is limited to selected companies
  - Future improvements could include more financial indicators and predictive analysis.
