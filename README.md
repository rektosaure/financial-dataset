# Financial Dataset

A curated collection of financial, macroeconomic, market, company and reference datasets in CSV and JSON formats.

Designed for research, quantitative analysis, dashboards, notebooks and data-driven applications.

## What’s inside

The repository currently includes datasets covering:

- **Markets** — FX, commodities, equity indices, volatility and sector ETFs
- **Macroeconomics** — inflation, employment, GDP, PMI, sentiment and construction
- **Rates & Credit** — Treasury yields, policy rates, corporate credit and liquidity
- **Equities** — S&P constituents, sectors, industries, classifications and rankings
- **Companies** — profiles, fundamentals, valuation metrics and financial statements
- **Earnings** — earnings-call transcripts and related metadata
- **Crypto** — selected network and real-world-asset metrics

## Data catalog

Browse the complete human-readable catalog:

**[CATALOG.md](CATALOG.md)**

For programmatic discovery:

**[CATALOG.json](CATALOG.json)**

The machine-readable catalog contains dataset names, categories, descriptions, formats, file locations and refresh information when available.

## Quick start

### CSV with pandas

```python
import pandas as pd

df = pd.read_csv(
    "https://raw.githubusercontent.com/rektosaure/financial-dataset/main/macro-world/fx_d.csv"
)

print(df.head())
```

No repository clone is required when using raw GitHub URLs.

### JSON with Python

```python
import json
import urllib.request

url = (
    "https://raw.githubusercontent.com/"
    "rektosaure/financial-dataset/main/"
    "stockanalysis/AAPL.json"
)

with urllib.request.urlopen(url) as response:
    data = json.load(response)

print(data["profile"])
```

## Repository structure

```text
financial-dataset/
├── CATALOG.md
├── CATALOG.json
├── macro-crypto/
├── macro-us/
├── macro-world/
├── screener/
├── stockanalysis/
└── transcripts/
```

### `macro-us/`

US macroeconomic, monetary, rates, credit and market datasets.

### `macro-world/`

Global macroeconomic and market datasets including FX, commodities and equity indices.

### `macro-crypto/`

Selected cryptocurrency and blockchain-related datasets.

### `screener/`

Equity reference data, classifications, index constituents, sector and industry statistics and rankings.

### `stockanalysis/`

Company-level JSON files containing profiles, fundamentals, valuation data and financial information.

Example:

```text
stockanalysis/AAPL.json
```

### `transcripts/`

Company earnings-call transcripts and associated metadata.

Example:

```text
transcripts/AAPL.json
```

## Updates

Datasets are refreshed automatically according to the availability and update cycle of their respective upstream sources.

Not every refresh produces a repository change.

Historical observations may also change when an upstream source publishes revisions or corrections.

## Data notes

Missing CSV values and JSON `null` values should not be interpreted as zero.

Dates represent the observation period associated with the underlying dataset and may have different meanings depending on the source.

Coverage, frequency and field availability may vary between datasets.

## Sources and usage

This repository aggregates information originating from multiple public and third-party sources.

Source availability, methodology, access conditions and redistribution rights may differ between datasets.

Users are responsible for checking the applicable terms of the relevant upstream source before redistributing, republishing or commercially using any dataset.

## Disclaimer

The datasets may be incomplete, delayed, inaccurate or subject to revision.

They are provided for research and informational purposes only and should not be treated as financial, investment or trading advice.
