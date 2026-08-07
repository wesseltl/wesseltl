## Hi, I'm Wessel 👋

**Data / Backend Engineer — Python · real-time data · automation**

I build the infrastructure data-driven products run on: real-time ingestion, storage, aggregation, and
clean APIs — backed by a portfolio of working, tested projects. My background is in molecular
life-science (diagnostics, sequencing, GMP-grade rigor), where I learned to treat data carefully:
validate it, question it, and never trust a result I can't reproduce. Now focused on data / backend
engineering, with a particular interest in crypto market-data infrastructure.

📍 Hoofddorp, Netherlands

### 🔧 What I work with

`Python` · `SQL` · real-time data (websockets) · ETL & aggregation · `pandas` / `NumPy` · REST APIs ·
`SQLite` · `Git` · `Docker` · unit testing · honest out-of-sample validation

### 📦 Featured projects

**[crypto-data-platform](https://github.com/wesseltl/crypto-data-platform)** — real-time crypto market-data pipeline
Websocket trade collector → SQLite → OHLCV/VWAP aggregation → query API + live candlestick dashboard,
with honest analytics (volatility forecasting, anomaly detection) and risk-based position sizing.
Idempotent ingestion, unit-tested, Dockerized.
▶ **Live demo → https://wesseltl.github.io/crypto-data-platform/**

**[data-cleaner-agent](https://github.com/wesseltl/data-cleaner-agent)** — agentic data-cleaning workflow
A planner (rule-based or LLM) reasons about messy data and picks the cleaning steps; deterministic
tools do the actual transformation — the model plans, trusted code executes. Unit-tested.

**[dex-sim](https://github.com/wesseltl/dex-sim)** — AMM / DEX mechanics simulator
Constant-product (Uniswap v2) and concentrated-liquidity (v3) pools: swaps, slippage, price impact
and capital efficiency — exact `Decimal` math, unit-tested. A simulation, not a deployed exchange.

**[crypto-tax](https://github.com/wesseltl/crypto-tax)** — crypto tax valuation engine
A country-neutral core (ingest → holdings → prices) plus per-country rules plugins (Netherlands box 3
first). Exact `Decimal` money handling, a swappable price source, unit-tested.

**[ml-validation-pipeline](https://github.com/wesseltl/ml-validation-pipeline)** — honest ML validation
From-scratch (NumPy) walk-forward validation and permutation nulls — built to tell real signal from
noise. Rigor over black-box models.

**[product-scraper](https://github.com/wesseltl/product-scraper)** — dependency-light web scraper
Paginated crawling with retry/backoff, polite rate-limiting, and clean CSV output.

### 📫 Reach me

wesseltl@gmail.com
