## Wessel ter Laak

Python developer working on data pipelines, backend services, web scraping, and AI-agent tooling.
Freelance portal: [wesseltl.github.io](https://wesseltl.github.io)

I spent six years working in molecular diagnostics labs before moving into software, and that's where
I got careful with data: check it, reproduce it, don't trust a number you can't back up. Based in
Hoofddorp, NL. Open to freelance and data/backend work.

### Tech

`Python` · `SQL` · websockets / real-time data · ETL & aggregation · `pandas` / `NumPy` · REST APIs ·
`SQLite` · `Git` · `Docker` · unit testing · AI-agent workflows

### MCP tools for AI agents

A set of MCP servers that give AI agents reliable access to real, messy data. All published on PyPI and
listed in the official MCP registry. Throughout: the model decides, tested code reads the data, so
values are never guessed.

**[excel-mcp](https://github.com/wesseltl/excel-mcp)**: read real messy `.xlsx` from an agent
Multiple sheets, auto-detects the header row under title rows, forward-fills merged cells.
`pip install excel-agent-mcp`

**[pdf-mcp](https://github.com/wesseltl/pdf-mcp)**: extract text and tables from PDFs
Invoices, reports, statements as clean rows instead of a flattened blob. `pip install pdf-agent-mcp`

**[data-cleaner-agent](https://github.com/wesseltl/data-cleaner-agent)**: agentic CSV cleaner
The LLM picks which cleaning steps to run; plain tested Python does the transforms, so the model never
touches the data directly. `pip install agentic-csv-cleaner`

**[crypto-price-mcp](https://github.com/wesseltl/crypto-price-mcp)**: live crypto prices for agents
Current prices and candles, so an agent can answer "what's BTC at right now?" instead of guessing.
`pip install hyperliquid-price-mcp`

### Other projects

**[crypto-data-platform](https://github.com/wesseltl/crypto-data-platform)**: real-time market-data pipeline
Websocket collector → SQLite → OHLCV/VWAP aggregation → query API + live dashboard, with analytics
(volatility forecasting, anomaly detection). Idempotent ingestion, unit-tested, Dockerized.
*(Domain: crypto market data.)*
▶ **Live demo → https://wesseltl.github.io/crypto-data-platform/**

**[dex-sim](https://github.com/wesseltl/dex-sim)**: AMM / DEX mechanics simulator
Constant-product (Uniswap v2) and concentrated-liquidity (v3) pools: swaps, slippage, price impact
and capital efficiency, with exact `Decimal` math and tests. It's a simulation, not a deployed exchange.

**[crypto-tax](https://github.com/wesseltl/crypto-tax)**: crypto tax valuation engine
A country-neutral core (ingest → holdings → prices) plus per-country rules plugins (Netherlands box 3
first). Exact `Decimal` money handling, a swappable price source, unit-tested.

**[ml-validation-pipeline](https://github.com/wesseltl/ml-validation-pipeline)**: honest ML validation
Walk-forward validation and permutation nulls, written from scratch in NumPy, to check whether a
result is real or just noise.

**[product-scraper](https://github.com/wesseltl/product-scraper)**: dependency-light web scraper
Paginated crawling with retry/backoff, polite rate-limiting, and clean CSV output.

### Contact

wesseltl@gmail.com
