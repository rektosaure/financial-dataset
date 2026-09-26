# Financial Dataset

Collection of financial, macroeconomic, market, reference and company datasets in CSV and JSON formats.

The repository is updated automatically from multiple public and third-party data sources.

## Datasets

| Directory | Content | Format |
| --- | --- | --- |
| `macro-crypto/` | Cryptocurrency ecosystem and market data | CSV |
| `macro-us/` | U.S. macroeconomic, financial and economic-report data | CSV, JSON |
| `macro-world/` | Global macroeconomic, commodities, FX and index data | CSV |
| `screener/` | Equity universes, classifications, reference data and provider-supplied rankings | CSV |
| `stockanalysis/` | Company profiles, financials, statistics and forecasts by ticker | JSON |
| `transcripts/` | Earnings-call transcripts by ticker | JSON |

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

## Data frequency

Some macro datasets are available at several observation frequencies.

| Suffix | Frequency |
| --- | --- |
| `_d` | Daily |
| `_w` | Weekly |
| `_m` | Monthly |
| `_q` | Quarterly |
| `_a` | Annual |

These suffixes describe the frequency of the observations contained in the file, not how often the file itself is updated.

Not all datasets use frequency suffixes.

## Updates

Datasets are refreshed automatically according to the availability and update cycle of their upstream sources.

Refresh frequency varies between datasets. Some sources are checked several times per day, while others are updated daily or weekly.

A file is not necessarily modified on every refresh. Upstream sources may also revise previously published observations, causing historical values to change.

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

Missing CSV values and JSON `null` values should not be interpreted as zero.

Dates represent the observation period associated with the underlying data and may have different meanings depending on the dataset.

Coverage and field availability may vary by source, period and company.

Historical observations may change when upstream sources publish revisions or corrections.

## Sources & licensing

The repository aggregates data from multiple public and third-party sources.

Source attribution, methodology, availability and usage rights may differ between datasets.

Users should identify the relevant upstream source and verify its applicable terms before redistributing or commercially using the data.

## Disclaimer

The data may be incomplete, delayed, inaccurate or subject to revision.

It is provided for research and informational purposes only. Users are responsible for assessing its suitability before relying on it for financial, investment or other decisions.
