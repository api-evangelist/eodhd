# EODHD

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Access historical end-of-day stock prices, intraday data, US stock options, and real-time prices with free and advanced plans. EODHD provides financial data for 150,000+ tickers, including stocks, ETFs, funds, and currencies worldwide, through 68+ REST endpoints, WebSocket streaming, an official OpenAPI 3.1.0 specification, an OAuth-secured MCP server with 86 tools, and a published Claude Skills plugin.

**Areas:** Finance · Market Data · Stock Options · Stocks · ETFs · Foreign Exchange · Cryptocurrency · Fundamentals · News · Real-Time · Financial Data

## EODHD on APIs.io

Everything profiled for EODHD is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/eodhd/](https://apis.io/providers/eodhd/)** — or go straight to one of the APIs or properties below.

### APIs (35)

- [EODHD Intraday Historical Data API](https://apis.io/apis/eodhd/intraday-historical-data-api/) — Provides intraday historical OHLCV data at 1-minute, 5-minute, and 1-hour intervals for US stocks and other supported markets, with multi-year lookbacks…
- [EODHD Live (Delayed) Stock Prices API](https://apis.io/apis/eodhd/live-prices-api/) — Returns live or 15-20 minute delayed stock quotes including last price, change, volume, and bid/ask data for stocks, ETFs, indices, and forex pairs across…
- [EODHD WebSockets Real-Time API](https://apis.io/apis/eodhd/websockets-api/) — Streams real-time trade and quote updates over WebSockets for US stocks, forex, and cryptocurrencies, allowing low-latency consumption of live market data.
- [EODHD Fundamental Data API](https://apis.io/apis/eodhd/fundamental-data-api/) — Provides company fundamentals including general info, financial statements (income statement, balance sheet, cash flow), earnings, valuation ratios, ETF…
- [EODHD Stock Options API](https://apis.io/apis/eodhd/options-data-api/) — Returns US stock options chain data with strikes, expirations, bid/ask, open interest, implied volatility, and Greeks (delta, gamma, theta, vega).
- [EODHD Technical Indicators API](https://apis.io/apis/eodhd/technical-indicators-api/) — Computes common technical indicators server-side, including SMA, EMA, RSI, MACD, Bollinger Bands, ATR, and stochastic oscillators, on top of the EODHD…
- [EODHD Economic Events Calendar API](https://apis.io/apis/eodhd/economic-events-api/) — Provides a global economic calendar of macroeconomic releases including country, event name, scheduled time, prior, forecast, and actual values.
- [EODHD Financial News and Sentiment API](https://apis.io/apis/eodhd/news-sentiment-api/) — Delivers financial news articles tagged by ticker symbol with sentiment scoring (positive, negative, neutral) for use in research, trading signals, and…
- [EODHD Exchanges and Symbols API](https://apis.io/apis/eodhd/exchanges-and-tickers-api/) — Lists supported exchanges and instruments with metadata including ticker, exchange code, name, type, and identifier mappings (CUSIP, ISIN, FIGI) to support…
- [EODHD Eod API](https://apis.io/apis/eodhd/eodhd-eod-api/) — The Eod API from EODHD — 1 operation(s) for eod.
- [EODHD Calendar API](https://apis.io/apis/eodhd/eodhd-calendar-api/) — Calendar events including earnings, IPOs, splits, dividends, and trends
- [EODHD CBOE API](https://apis.io/apis/eodhd/eodhd-cboe-api/) — CBOE index data and listings
- [EODHD Corporate Actions API](https://apis.io/apis/eodhd/eodhd-corporate-actions-api/) — Symbol changes and insider transactions
- [EODHD Credit & Sovereign Risk API](https://apis.io/apis/eodhd/eodhd-credit-sovereign-risk-api/) — Sovereign risk premiums, credit ratings, CDS spreads, and corporate credit metrics
- [EODHD Dividends & Splits API](https://apis.io/apis/eodhd/eodhd-dividends-splits-api/) — Dividend and split history
- [EODHD Economic Data API](https://apis.io/apis/eodhd/eodhd-economic-data-api/) — Economic events and macro indicators
- [EODHD End-of-Day Data API](https://apis.io/apis/eodhd/eodhd-end-of-day-data-api/) — Historical and current end-of-day price data
- [EODHD ESG API](https://apis.io/apis/eodhd/eodhd-esg-api/) — Environmental, Social, and Governance ratings (Investverte)
- [EODHD Exchanges API](https://apis.io/apis/eodhd/eodhd-exchanges-api/) — Exchange information and symbols
- [EODHD Fundamentals API](https://apis.io/apis/eodhd/eodhd-fundamentals-api/) — Fundamental data for stocks and companies
- [EODHD Indices API](https://apis.io/apis/eodhd/eodhd-indices-api/) — S&P/Dow Jones indices data and components
- [EODHD Interest Rates API](https://apis.io/apis/eodhd/eodhd-interest-rates-api/) — Reference rates, central bank policy rates, and funding-stress spreads
- [EODHD Intraday Data API](https://apis.io/apis/eodhd/eodhd-intraday-data-api/) — Intraday historical price data (time-based bars)
- [EODHD Investment Analytics API](https://apis.io/apis/eodhd/eodhd-investment-analytics-api/) — Risk scoring, bond analysis, bank financials, reports (PRAAMS)
- [EODHD Live (Delayed) Data API](https://apis.io/apis/eodhd/eodhd-live-delayed-data-api/) — Delayed real-time stock prices and US delayed quotes
- [EODHD Logos API](https://apis.io/apis/eodhd/eodhd-logos-api/) — Company and ticker logos
- [EODHD Market Data API](https://apis.io/apis/eodhd/eodhd-market-data-api/) — Market capitalization and other market data
- [EODHD News API](https://apis.io/apis/eodhd/eodhd-news-api/) — Financial news and sentiment analysis
- [EODHD Options API](https://apis.io/apis/eodhd/eodhd-options-api/) — Options contracts and pricing data
- [EODHD Sanctions API](https://apis.io/apis/eodhd/eodhd-sanctions-api/) — Sanctioned entities, vessels, programs, and sources (OFAC and others)
- [EODHD Screening API](https://apis.io/apis/eodhd/eodhd-screening-api/) — Stock screening tools
- [EODHD Technical API](https://apis.io/apis/eodhd/eodhd-technical-api/) — Technical analysis indicators
- [EODHD Tick Data API](https://apis.io/apis/eodhd/eodhd-tick-data-api/) — Historical and marketplace tick-level trade data
- [EODHD US Treasury API](https://apis.io/apis/eodhd/eodhd-us-treasury-api/) — US Treasury interest rates (bills, yields, long-term, real yields)
- [EODHD User API](https://apis.io/apis/eodhd/eodhd-user-api/) — User account and subscription information

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [EODHD WebSockets Real-Time API](https://apis.io/asyncapis/eodhd/eodhd-websockets-asyncapi/)

#### Event channels (4)

Individual events and webhooks the provider emits.

- [/ws/crypto](https://apis.io/channels/eodhd/ws-crypto/)
- [/ws/forex](https://apis.io/channels/eodhd/ws-forex/)
- [/ws/us](https://apis.io/channels/eodhd/ws-us/)
- [/ws/us-quote](https://apis.io/channels/eodhd/ws-us-quote/)

#### MCP servers (2)

Model Context Protocol servers that expose the API to agents.

- [eodhd](https://apis.io/servers/eodhd/eodhd/)
- [MCP Server announcement](https://apis.io/servers/eodhd/mcp-server-announcement/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Eodhd Agentic Access](https://apis.io/agentic-access/eodhd/eodhd-agentic-access/)

#### JSON Schema (1)

The data models the API reads and writes.

- [EodBar](https://apis.io/schemas/eodhd/eodhd-eodbar/)

#### JSON Structure (1)

Data models expressed in JSON Structure.

- [Eodhd Structure](https://apis.io/json-structure/eodhd/eodhd-structure/)

#### Collections (5)

Postman and Open Collection request collections.

- [EODHD End-Of-Day Historical Data Eod API](https://apis.io/collections/eodhd/open-eodhd-eod-api/)
- [EODHD End-Of-Day Historical Data API](https://apis.io/collections/eodhd/open-eodhd-eod-historical-data/)
- [EODHD Financial Data API](https://apis.io/collections/eodhd/open-eodhd-financial-data/)
- [EODHD End-Of-Day Historical Data Eod API](https://apis.io/collections/eodhd/postman-eodhd-eod-api/)
- [EODHD Financial Data API](https://apis.io/collections/eodhd/postman-eodhd-financial-data/)

#### Overlays (2)

OpenAPI overlays, including conversational phrasing for each operation.

- [Eodhd Eod Api Overlay](https://apis.io/overlays/eodhd/eodhd-eod-api-overlay/)
- [Eodhd Financial Data Overlay](https://apis.io/overlays/eodhd/eodhd-financial-data-overlay/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [EODHD — jsonschema rules](https://apis.io/rules/eodhd/eodhd-jsonschema-spectral-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Eodhd Authentication](https://apis.io/security/eodhd/eodhd-authentication/)
- [Eodhd Domain Security](https://apis.io/security/eodhd/eodhd-domain-security/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Eodhd Scopes](https://apis.io/scopes/eodhd/eodhd-scopes/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Eodhd Plans Pricing](https://apis.io/plans/eodhd/eodhd-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Eodhd Rate Limits](https://apis.io/rate-limits/eodhd/eodhd-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Eodhd Finops](https://apis.io/finops/eodhd/eodhd-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://eodhd.com/)
- [Documentation](https://eodhd.com/financial-apis/)
- [Getting started](https://eodhd.com/financial-apis)
- [API reference](https://eodhd.com/docs)
- [Pricing](https://eodhd.com/pricing)
- [Sign up](https://eodhd.com/register)
- [Support](https://forum.eodhd.com/)
- [Blog](https://eodhd.com/financial-apis-blog/)
- [Terms of service](https://eodhd.com/financial-apis/terms-conditions)
- [Privacy policy](https://eodhd.com/financial-apis/privacy-policy)
- [GitHub](https://github.com/EodHistoricalData)

## API Evangelist rating

**Kin Score 55.9** — strong · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 68.3 |
| Contract quality | 56.5 |
| Contract governance | 14.4 |
| Operational transparency | 26.3 |
| Developer ergonomics | 83.3 |
| Access clarity | 52.6 |

**Agent readiness 58.3** — agent-ready (gated down from agent-native)

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | na |
| MCP Server | templated |
| Auth Clarity | served (partial credit) |
| Idempotency | na |
| Error Semantics | derived (partial credit) |
| OpenAPI Examples | verified |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | derived (partial credit) |
| Agent Skills | yes |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | na |
| Delegated Identity | served (partial credit) |
| Protected Resource Metadata | verified |
| Dynamic Client Registration | yes |
| Agentic Commerce | — |
| Pagination Ratio | partial |
| Operation Distinctiveness | distinct |

**Regulatory alignment 38.0** — Securities & Market Data

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/eodhd/](https://apis.io/providers/eodhd/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for EODHD: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/eodhd/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
