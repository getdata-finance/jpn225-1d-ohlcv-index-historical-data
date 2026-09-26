# JPN225 1d OHLCV Index Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-5_340_rows-blue)](https://getdata.finance/datasets/jpn225) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/jpn225)

### -> [**Download the full JPN225 dataset on getdata.finance**](https://getdata.finance/datasets/jpn225)

**JPN225 1d OHLCV index historical data** — ultra high-quality 1d OHLCV for **Nikkei 225**. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

## Table of contents

- [Why this dataset?](#why-this-dataset)
- [Download sample CSV](#download-sample)
- [GitHub Pages preview](#github-pages)
- [Sample vs full dataset](#sample-vs-full-dataset)
- [Timeframes on GetData](#timeframes-on-getdata)
- [Weekly updates](#weekly-updates)
- [Data preview](#data-preview)
- [Schema](#schema)
- [Code examples](#code-examples)
- [Download full data on getdata.finance](#download-full-data-on-getdata)

## Why this dataset?

- **Ultra high-quality 1d OHLCV** for **Nikkei 225** (Index)
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`1d`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/jpn225) · **5,340** `1d` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `1d` sample updated in sync

> **Sample on GitHub** · `JPN225_1d.csv` (732 rows, `2024-05-20` -> `2026-09-25`, 54.35 KB). **Full archive on [getdata.finance](https://getdata.finance/datasets/jpn225)** — **5,340** `1d` rows (full `1m`: 4,718,919), **11 timeframes**, `2008-09-01` -> `2026-09-25`.

## Download sample

**[JPN225_1d.csv](https://github.com/getdata-finance/jpn225-1d-ohlcv-index-historical-data/blob/main/JPN225_1d.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/jpn225-1d-ohlcv-index-historical-data/main/JPN225_1d.csv)) · [GitHub Releases](https://github.com/getdata-finance/jpn225-1d-ohlcv-index-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/jpn225-1d-ohlcv-index-historical-data/](https://getdata-finance.github.io/jpn225-1d-ohlcv-index-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/jpn225](https://getdata.finance/datasets/jpn225)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/jpn225))** |
|---|--:|---|
| Instrument | Nikkei 225 · Index | Nikkei 225 · Index |
| Timeframes | `1d` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 1d rows | 732 | **5,340** |
| Size | 54.35 KB | full ZIP on [getdata.finance](https://getdata.finance/datasets/jpn225) |
| Period | `2024-05-20` -> `2026-09-25` | `2008-09-01` -> `2026-09-25` |
| File | `JPN225_1d.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/jpn225) |
| Coverage report | — | [JPN225 coverage](https://getdata.finance/coverage/jpn225) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`1d` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/jpn225)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W**

GitHub = `1d` sample · [getdata.finance](https://getdata.finance/datasets/jpn225) = all **11** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `1d` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`JPN225_1d.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2024-05-20T00:00:00+00:00 | 38757.94 | 39485.44 | 38705.42 | 39328.01 | 27455 |
| 2024-05-21T00:00:00+00:00 | 39328.01 | 39370.5 | 38760.51 | 38896.09 | 22386.65277 |
| 2024-05-22T00:00:00+00:00 | 38896.09 | 38910.72 | 38460.61 | 38903.2 | 30292 |
| 2024-05-23T00:00:00+00:00 | 38903.2 | 39198.22 | 38423.23 | 38443.23 | 38516.21856 |
| 2024-05-24T00:00:00+00:00 | 38443.23 | 38890.74 | 38375.73 | 38795.75 | 22738.24131 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-09-21T00:00:00+00:00 | 65282.99 | 66842.51 | 65087.99 | 66798 | 45936 |
| 2026-09-22T00:00:00+00:00 | 66798 | 67338.01 | 66207.49 | 67283.01 | 64609 |
| 2026-09-23T00:00:00+00:00 | 67283.01 | 67372.51 | 65912.99 | 66083.01 | 59550 |
| 2026-09-24T00:00:00+00:00 | 66083.01 | 66313.01 | 65337.99 | 65608.01 | 102269 |
| 2026-09-25T00:00:00+00:00 | 65608.01 | 66852.51 | 65608.01 | 66688 | 84800 |

## Schema

| Column | Description |
| --- | --- |
| `datetime` | Bar open timestamp (UTC, ISO-8601). |
| `open` | Opening price of the candlestick bar. |
| `high` | Highest price during the bar. |
| `low` | Lowest price during the bar. |
| `close` | Closing price of the candlestick bar. |
| `volume` | Tick volume (number of price updates) during the bar. |

```text
datetime,open,high,low,close,volume
```

## Code examples

### pandas

```python
import pandas as pd

df = pd.read_csv('JPN225_1d.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('JPN225_1d.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)

class PandasData(bt.feeds.PandasData):
    params = (('datetime', None), ('open', 'open'), ('high', 'high'),
              ('low', 'low'), ('close', 'close'), ('volume', 'volume'))

cerebro = bt.Cerebro()
cerebro.adddata(PandasData(dataname=df))
# cerebro.addstrategy(YourStrategy)
# cerebro.run()
```

### vectorbt

```python
import pandas as pd
import vectorbt as vbt

df = pd.read_csv('JPN225_1d.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='1d')
print(pf.stats())
```

## Download full data

The complete **JPN225** archive on **[getdata.finance](https://getdata.finance/datasets/jpn225)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **5,340** rows at `1d`, plus all other timeframes in the same ZIP.

**[-> Get the full JPN225 dataset on getdata.finance](https://getdata.finance/datasets/jpn225)**

---
*GetData · JPN225 1d OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/jpn225)*
