# Financial Dataset

Collection of financial, macroeconomic, market and company datasets in CSV and JSON formats.

## Datasets

| Directory        | Content                                        | Format | Update frequency |
| ---------------- | ---------------------------------------------- | ------ | ---------------- |
| `macro-us/`      | U.S. macroeconomic and financial data          | CSV    | Every 4 hours    |
| `macro-world/`   | Global macro, commodities, FX and indices      | CSV    | Every 4 hours    |
| `screener/`      | Equity universes, classifications and rankings | CSV    | Every 12 hours   |
| `stockanalysis/` | Company profiles and security metadata         | JSON   | Every 24 hours   |
| `transcripts/`   | Earnings-call transcripts by ticker            | JSON   | Every 24 hours   |

## Structure

```text
financial-dataset/
├── macro-us/
├── macro-world/
├── screener/
├── stockanalysis/
└── transcripts/
```

Some macro datasets are available at different frequencies:

| Suffix | Frequency |
| ------ | --------- |
| `_d`   | Daily     |
| `_w`   | Weekly    |
| `_m`   | Monthly   |
| `_q`   | Quarterly |

## Usage

CSV files can be loaded directly with pandas:

```python
import pandas as pd

df = pd.read_csv("macro-world/fx.csv")
```

JSON datasets are generally organized by ticker:

```python
import json

with open("stockanalysis/AAPL.json") as f:
    data = json.load(f)
```

Files can also be consumed directly through GitHub raw URLs without cloning the full repository.

## Data notes

Update frequency refers to how often the datasets are refreshed on a rolling basis. Updates are staggered throughout the day and do not all occur simultaneously.

Missing CSV values or JSON `null` values should not be interpreted as zero.

Some datasets may be revised historically as upstream sources publish corrections or updated observations.

## Sources & licensing

The repository aggregates data from multiple public and third-party sources.

Source attribution, methodology and usage rights may differ between datasets. Users should verify the original source and its applicable terms before redistributing or using the data commercially.

## Disclaimer

The data may be incomplete, delayed, inaccurate or subject to revision.

The data is provided for private, research and informational use only. Users are solely responsible for assessing its suitability and should exercise their own judgment before relying on it for any financial, investment or other decision.
