Financial Dataset Data Card (Yahoo Finance)

## 1. Source of Data
Data is collected using the Yahoo Finance API through the Python library `yfinance`.

Yahoo Finance provides historical stock market data including:
- Open price
- High price
- Low price
- Close price
- Volume

---

## 2. Dataset
The dataset includes 5 NASDAQ companies:

- Apple (AAPL)
- Microsoft (MSFT)
- Amazon (AMZN)
- Tesla (TSLA)
- NVIDIA (NVDA)

Each company has a different time period (1–5 years).

---

## 3. Data Description
Daily stock data includes:
- Date
- Open
- High
- Low
- Close
- Volume

---

## 4. KPIs (Data Quality)

We evaluate dataset quality using:

### Completeness
Checks missing values.

### Latency
How recent the data is.

### Accuracy
Close price must be between High and Low.

### Consistency
Checks logical correctness of values.

---

## 5. Results
(Insert your KPI table from notebook)

Example:

| Ticker | Completeness | Latency | Accuracy | Consistency |
|--------|--------------|----------|----------|-------------|
| AAPL   | 0.xx         | xx       | 0.xx     | 0.xx        |

---

## 6. Visualization
Includes:
- Stock price charts
- Time series analysis

---

## 7. Conclusion
The dataset from Yahoo Finance is high quality and suitable for machine learning tasks such as forecasting and financial analysis.
