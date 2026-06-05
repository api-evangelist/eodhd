# EODHD (eodhd)

Access historical end-of-day stock prices, intraday data, US stock options, and real-time prices with free and advanced plans. EODHD provides financial data for 150,000+ tickers, including stocks, ETFs, funds, and currencies worldwide.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/eodhd/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/eodhd/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Financial
- Market Data
- Stock Options
- Stocks

## Timestamps

- **Created:** 2025-02-24
- **Modified:** 2026-05-19

## APIs

### EODHD End-Of-Day Historical Data API

Returns end-of-day historical OHLCV data for stocks, ETFs, funds, indices, and currencies across global exchanges. Supports daily, weekly, and monthly periods with both raw and split/dividend-adjusted close prices.

- **Human URL:** [https://eodhd.com/financial-apis/api-for-historical-data-and-volumes](https://eodhd.com/financial-apis/api-for-historical-data-and-volumes)

#### Tags

- End Of Day
- Financial
- Historical Data
- Stocks

#### Properties

- [OpenAPI](openapi/eodhd-eod-historical-data-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/eodhd-eod-historical-data.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/eodhd-eod-historical-data.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://eodhd.com/financial-apis/api-for-historical-data-and-volumes)

### EODHD Intraday Historical Data API

Provides intraday historical OHLCV data at 1-minute, 5-minute, and 1-hour intervals for US stocks and other supported markets, with multi-year lookbacks depending on the resolution.

- **Human URL:** [https://eodhd.com/financial-apis/intraday-historical-data-api](https://eodhd.com/financial-apis/intraday-historical-data-api)

#### Tags

- Financial
- Historical Data
- Intraday
- Stocks

#### Properties

- [Documentation](https://eodhd.com/financial-apis/intraday-historical-data-api)
- [Postman Collection](collections/eodhd-eod-historical-data.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/eodhd-eod-historical-data.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### EODHD Live (Delayed) Stock Prices API

Returns live or 15-20 minute delayed stock quotes including last price, change, volume, and bid/ask data for stocks, ETFs, indices, and forex pairs across global exchanges.

- **Human URL:** [https://eodhd.com/financial-apis/live-realtime-stocks-api](https://eodhd.com/financial-apis/live-realtime-stocks-api)

#### Tags

- Financial
- Live Data
- Real Time
- Stocks

#### Properties

- [Documentation](https://eodhd.com/financial-apis/live-realtime-stocks-api)
- [Postman Collection](collections/eodhd-eod-historical-data.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/eodhd-eod-historical-data.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### EODHD WebSockets Real-Time API

Streams real-time trade and quote updates over WebSockets for US stocks, forex, and cryptocurrencies, allowing low-latency consumption of live market data.

- **Human URL:** [https://eodhd.com/financial-apis/new-real-time-data-api-websockets](https://eodhd.com/financial-apis/new-real-time-data-api-websockets)

#### Tags

- Financial
- Real Time
- Streaming
- WebSockets

#### Properties

- [Documentation](https://eodhd.com/financial-apis/new-real-time-data-api-websockets)
- [Postman Collection](collections/eodhd-eod-historical-data.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/eodhd-eod-historical-data.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### EODHD Fundamental Data API

Provides company fundamentals including general info, financial statements (income statement, balance sheet, cash flow), earnings, valuation ratios, ETF holdings, and mutual fund details.

- **Human URL:** [https://eodhd.com/financial-apis/stock-etfs-fundamental-data-feeds](https://eodhd.com/financial-apis/stock-etfs-fundamental-data-feeds)

#### Tags

- Financial
- Fundamentals
- Stocks

#### Properties

- [Documentation](https://eodhd.com/financial-apis/stock-etfs-fundamental-data-feeds)
- [Postman Collection](collections/eodhd-eod-historical-data.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/eodhd-eod-historical-data.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### EODHD Stock Options API

Returns US stock options chain data with strikes, expirations, bid/ask, open interest, implied volatility, and Greeks (delta, gamma, theta, vega).

- **Human URL:** [https://eodhd.com/financial-apis/stock-options-data](https://eodhd.com/financial-apis/stock-options-data)

#### Tags

- Derivatives
- Financial
- Options

#### Properties

- [Documentation](https://eodhd.com/financial-apis/stock-options-data)
- [Postman Collection](collections/eodhd-eod-historical-data.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/eodhd-eod-historical-data.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### EODHD Technical Indicators API

Computes common technical indicators server-side, including SMA, EMA, RSI, MACD, Bollinger Bands, ATR, and stochastic oscillators, on top of the EODHD historical price database.

- **Human URL:** [https://eodhd.com/financial-apis/technical-indicators-api](https://eodhd.com/financial-apis/technical-indicators-api)

#### Tags

- Analytics
- Financial
- Technical Indicators

#### Properties

- [Documentation](https://eodhd.com/financial-apis/technical-indicators-api)
- [Postman Collection](collections/eodhd-eod-historical-data.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/eodhd-eod-historical-data.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### EODHD Economic Events Calendar API

Provides a global economic calendar of macroeconomic releases including country, event name, scheduled time, prior, forecast, and actual values.

- **Human URL:** [https://eodhd.com/financial-apis/economic-events-data-api](https://eodhd.com/financial-apis/economic-events-data-api)

#### Tags

- Calendar
- Economic Data
- Financial

#### Properties

- [Documentation](https://eodhd.com/financial-apis/economic-events-data-api)
- [Postman Collection](collections/eodhd-eod-historical-data.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/eodhd-eod-historical-data.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### EODHD Financial News and Sentiment API

Delivers financial news articles tagged by ticker symbol with sentiment scoring (positive, negative, neutral) for use in research, trading signals, and news-driven workflows.

- **Human URL:** [https://eodhd.com/financial-apis/stock-market-financial-news-api](https://eodhd.com/financial-apis/stock-market-financial-news-api)

#### Tags

- Financial
- News
- Sentiment

#### Properties

- [Documentation](https://eodhd.com/financial-apis/stock-market-financial-news-api)
- [Postman Collection](collections/eodhd-eod-historical-data.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/eodhd-eod-historical-data.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### EODHD Exchanges and Symbols API

Lists supported exchanges and instruments with metadata including ticker, exchange code, name, type, and identifier mappings (CUSIP, ISIN, FIGI) to support symbol lookup and reference data workflows.

- **Human URL:** [https://eodhd.com/financial-apis/list-supported-exchanges](https://eodhd.com/financial-apis/list-supported-exchanges)

#### Tags

- Exchanges
- Financial
- Reference Data
- Symbols

#### Properties

- [Documentation](https://eodhd.com/financial-apis/list-supported-exchanges)
- [Postman Collection](collections/eodhd-eod-historical-data.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/eodhd-eod-historical-data.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/EodHistoricalData)
- [LinkedIn](https://www.linkedin.com/company/eodhd-apis)
- [Website](https://eodhd.com/)
- [Documentation](https://eodhd.com/financial-apis/)
- [Pricing](https://eodhd.com/pricing)
- [Marketplace](https://eodhd.com/marketplace)
- [Blog](https://eodhd.com/financial-apis-blog/)
- [Forums](https://forum.eodhd.com/)
- [Affiliate](https://eodhd.com/financial-apis/eodhd-affiliate-program)
- [Privacy Policy](https://eodhd.com/financial-apis/privacy-policy)
- [Terms of Service](https://eodhd.com/financial-apis/terms-conditions)
- [Integrations](https://eodhd.com/marketplace)
- [M C P Server](https://eodhd.com/financial-apis-blog/eodhd-mcp-server-update-75-tools-oauth-and-api-versioning)
- [Agent Skill](https://eodhd.com/financial-apis-blog/announcing-eodhd-claude-skills-teach-your-ai-the-entire-financial-api)
- [L L Ms Txt](https://eodhd.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
