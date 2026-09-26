# Financial Dataset

Collection of financial, macroeconomic, market, reference and company datasets in CSV and JSON formats.

The repository is updated automatically from multiple public and third-party data sources.

## Data catalog

See **[CATALOG.md](CATALOG.md)** for the human-readable directory of datasets
currently published in this repository.

For programmatic discovery, agents and tooling can use
**[CATALOG.json](CATALOG.json)**.

Both catalogs are generated from the same public dataset definitions and describe
each dataset, its coverage, format and public file location.

## Usage

CSV files can be loaded directly with pandas:

```python
import pandas as pd

df = pd.read_csv("macro-world/fx_d.csv")
```

JSON files can be loaded with the standard library:

```python
import json

with open("stockanalysis/AAPL.json") as f:
    data = json.load(f)
```

Files can also be consumed directly through GitHub raw URLs without cloning the repository.

## Updates

Datasets are refreshed automatically according to the availability and update cycle of their upstream sources.

A dataset may be checked without producing a repository change. Upstream sources may also revise previously published observations, causing historical values to change.

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
