<p align="center">
  <a href="https://www.kaggle.com/code/hassanjameelahmed/uber-stock-performance-analysis-2019-2026" target="_blank">
    <img src="2002.png" alt="Uber" alt="Uber" width="500">
  </a>
</p>
<br>

# Project Requirements Document (PRD): Uber Stock Performance Analysis (2019-2026)

## 1. Project Overview

This project aims to provide a comprehensive analysis of Uber Technologies, Inc. (UBER) stock performance from its IPO period in 2019 through early 2026. The dataset serves as a foundational resource for financial analysts, data scientists, and investors to understand market trends, volatility, and the long-term growth trajectory of one of the world's leading mobility platforms.

## 2. SEO-Optimized Project Details

- **Project Name:** Uber Stock Market Performance Analysis & Forecasting (2019-2026)
- **Description:** A detailed historical dataset and analytical framework exploring Uber's stock price volatility, trading volumes, and market trends. This project provides insights into Uber's financial journey from its early post-IPO days to the modern 2026 market landscape, suitable for predictive modeling and technical analysis.

## 3. Kaggle Dataset Information

### Top 5 Tags

1. `Finance`
2. `Stock Market`
3. `Data Visualization`
4. `Time Series Analysis`
5. `Uber`

### Column Details

| Column     | Detail            | Description                                                         |
| :--------- | :---------------- | :------------------------------------------------------------------ |
| **Date**   | Date (MM/DD/YYYY) | The specific trading day.                                           |
| **Open**   | Numeric (Float)   | The price at which the stock first traded when the exchange opened. |
| **High**   | Numeric (Float)   | The highest price the stock reached during the trading day.         |
| **Low**    | Numeric (Float)   | The lowest price the stock reached during the trading day.          |
| **Close**  | Numeric (Float)   | The final price at which the stock traded when the exchange closed. |
| **Volume** | Numeric (Integer) | The total number of shares traded during the day.                   |

## 4. Dataset Scope & Coverage

- **Coverage:** 100% of trading days within the specified period (excluding weekends and market holidays).
- **Temporal Scope:**
  - **Start Date:** 05/10/2019 (IPO Period)
  - **End Date:** 01/30/2026
- **Geospatial Scope:**
  - **Country:** USA
  - **Primary Exchange:** New York Stock Exchange (NYSE)
  - **Relevant City:** San Francisco, CA (Headquarters)

## 5. Provenance & Methodology

- **Provenance:** This data is sourced from public financial market records, primarily aggregated through the **NYSE (New York Stock Exchange)** and secondary verification via **Yahoo Finance**.
- **Collection Methodology:** The data was collected using automated web-scraping and API integration tools to pull daily OHLCV (Open, High, Low, Close, Volume) records.
- **Transformations:**
  - Standardization of date formats to MM/DD/YYYY.
  - Precision alignment for stock price columns (up to 8 decimal places where applicable).
  - Data cleaning to ensure no missing values for trading days.

## 6. Challenges & Problem Development

### Biggest Problems and Challenges

1.  **Market Volatility:** Uber has faced significant price swings due to regulatory changes and shifts in the gig economy.
2.  **External Factors:** Global events (e.g., pandemic recovery) have disproportionately affected mobility vs. delivery segments.
3.  **Data Consistency:** Aligning adjusted close prices with historical splits or dividends (though UBER has not paid dividends recently, market adjustments are constant).
4.  **Forecasting Accuracy:** High noise levels in delivery and freight sector competition make long-term trend prediction difficult.
5.  **Regulatory Sensitivity:** Local government decisions in major markets (NYC, London, California) cause abrupt price movements.

### Problem Development (Step-by-Step)

1.  **IPO Launch (2019):** Uber entered the public market with high expectations but immediate pressure to prove profitability.
2.  **The Shift (2020-2021):** The global pandemic severely impacted the ride-sharing business, leading to a pivot toward "Uber Eats" (Delivery) dominance.
3.  **Inflationary Pressures (2022-2023):** Rising fuel costs and labor shortages challenged the cost structure, forcing a focus on operational efficiency.
4.  **Profitability Milestone (2024):** Uber achieved its first GAAP operating profit, marking a transition from a growth story to a sustainable business model.
5.  **Maturity phase (2025-2026):** The current focus has shifted to autonomous vehicle integration and high-margin advertising revenue, reflected in the 2026 stock valuations.

## 7. Data Source & Link

- **Source:** Yahoo Finance / NYSE
- **Link:** [https://finance.yahoo.com/quote/UBER/history/](https://finance.yahoo.com/quote/UBER/history/)
