## Wessel ter Laak

Python developer — data pipelines, backend services, web scraping, and AI-agent tooling.
Freelance portal: [wesseltl.github.io](https://wesseltl.github.io)

I spent six years working in molecular diagnostics labs before moving into software, and that's where
I got careful with data: check it, reproduce it, don't trust a number you can't back up. Everything in
these repos runs and has tests. Based in Hoofddorp, NL. Open to freelance and data/backend work.

### Tech

`Python` · `SQL` · websockets / real-time data · ETL & aggregation · `pandas` / `NumPy` · REST APIs ·
`SQLite` · `Git` · `Docker` · unit testing · AI-agent workflows

### Projects

**[crypto-data-platform](https://github.com/wesseltl/crypto-data-platform)** — real-time market-data pipeline
Websocket collector → SQLite → OHLCV/VWAP aggregation → query API + live dashboard, with analytics
(volatility forecasting, anomaly detection). Idempotent ingestion, unit-tested, Dockerized.
*(Domain: crypto market data.)*
▶ **Live demo → https://wesseltl.github.io/crypto-data-platform/**

**[data-cleaner-agent](https://github.com/wesseltl/data-cleaner-agent)** — agentic data-cleaning workflow
A planner (rule-based, or an LLM) decides which cleaning steps a messy dataset needs. The actual
transformations are done by plain tested Python functions, so the model never touches the data
directly. Unit-tested.

**[dex-sim](https://github.com/wesseltl/dex-sim)** — AMM / DEX mechanics simulator
Constant-product (Uniswap v2) and concentrated-liquidity (v3) pools: swaps, slippage, price impact
and capital efficiency — exact `Decimal` math, unit-tested. A simulation, not a deployed exchange.

**[crypto-tax](https://github.com/wesseltl/crypto-tax)** — crypto tax valuation engine
A country-neutral core (ingest → holdings → prices) plus per-country rules plugins (Netherlands box 3
first). Exact `Decimal` money handling, a swappable price source, unit-tested.

**[ml-validation-pipeline](https://github.com/wesseltl/ml-validation-pipeline)** — honest ML validation
Walk-forward validation and permutation nulls, written from scratch in NumPy, to check whether a
result is real or just noise.

**[product-scraper](https://github.com/wesseltl/product-scraper)** — dependency-light web scraper
Paginated crawling with retry/backoff, polite rate-limiting, and clean CSV output.

### Contact

wesseltl@gmail.com
