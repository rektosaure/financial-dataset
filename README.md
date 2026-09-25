# Financial Dataset

Collection of financial, macroeconomic, market and company datasets in CSV and JSON formats.

This is an automated data publication repository. It does not calculate its own financial indicators, valuation metrics, trading signals, forecasts, scores or rankings.

When derived values are present, they are provided by the upstream source. Data may be validated, normalized or reformatted before publication.

## Datasets

| Directory | Content | Format | Update frequency |
| --- | --- | --- | --- |
| `macro-crypto/` | Cryptocurrency ecosystem and market data | CSV | Every 4 hours |
| `macro-us/` | U.S. macroeconomic and financial data | CSV | Every 4 hours |
| `macro-world/` | Global macro, commodities, FX and indices | CSV | Every 4 hours |
| `screener/` | Equity universes, classifications and provider-supplied rankings | CSV | Every 12 hours |
| `stockanalysis/` | Company profiles, financials, statistics and forecasts | JSON | Every 24 hours |
| `transcripts/` | Earnings-call transcripts by ticker | JSON | Every 24 hours |

## Structure

```text
financial-dataset/
├── macro-crypto/
├── macro-us/
├── macro-world/
├── screener/
├── stockanalysis/
└── transcripts/
```

Some macro datasets are available at different frequencies:

| Suffix | Frequency |
| --- | --- |
| `_d` | Daily |
| `_w` | Weekly |
| `_m` | Monthly |
| `_q` | Quarterly |

## Usage

CSV files can be loaded directly with pandas:

```python
import pandas as pd

df = pd.read_csv("macro-world/fx_d.csv")
```

JSON datasets are generally organized by ticker:

```python
import json

with open("stockanalysis/AAPL.json") as f:
    data = json.load(f)
```

Files can also be consumed directly through GitHub raw URLs without cloning the repository.

## Data notes

Update frequency refers to how often datasets are refreshed on a rolling basis. Updates are staggered throughout the day.

Missing CSV values or JSON `null` values should not be interpreted as zero.

Some datasets may be revised historically when upstream sources publish corrections or updated observations.

## Sources & licensing

The repository aggregates data from multiple public and third-party sources.

Source attribution, methodology and usage rights may differ between datasets. Users should verify the original source and its applicable terms before redistributing or using the data.

## Disclaimer

The data may be incomplete, delayed, inaccurate or subject to revision.

It is provided for private, research and informational use only. Users are responsible for assessing its suitability before relying on it for financial, investment or other decisions.
