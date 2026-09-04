# XAGUSD 3d OHLCV Metals Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-2_085_rows-blue)](https://getdata.finance/datasets/xagusd) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/xagusd)

### -> [**Download the full XAGUSD dataset on getdata.finance**](https://getdata.finance/datasets/xagusd)

**XAGUSD 3d OHLCV metals historical data** — ultra high-quality 3d OHLCV for **Silver / US Dollar**. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

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

- **Ultra high-quality 3d OHLCV** for **Silver / US Dollar** (Metals)
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`3d`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/xagusd) · **2,085** `3d` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `3d` sample updated in sync

> **Sample on GitHub** · `XAGUSD_3d.csv` (244 rows, `2024-09-02` -> `2026-09-01`, 25.00 KB). **Full archive on [getdata.finance](https://getdata.finance/datasets/xagusd)** — **2,085** `3d` rows (full `1m`: 5,671,224), **11 timeframes**, `2009-02-23` -> `2026-09-01`.

## Download sample

**[XAGUSD_3d.csv](https://github.com/getdata-finance/xagusd-3d-ohlcv-metals-historical-data/blob/main/XAGUSD_3d.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/xagusd-3d-ohlcv-metals-historical-data/main/XAGUSD_3d.csv)) · [GitHub Releases](https://github.com/getdata-finance/xagusd-3d-ohlcv-metals-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/xagusd-3d-ohlcv-metals-historical-data/](https://getdata-finance.github.io/xagusd-3d-ohlcv-metals-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/xagusd](https://getdata.finance/datasets/xagusd)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/xagusd))** |
|---|--:|---|
| Instrument | Silver / US Dollar · Metals | Silver / US Dollar · Metals |
| Timeframes | `3d` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 3d rows | 244 | **2,085** |
| Size | 25.00 KB | full ZIP on [getdata.finance](https://getdata.finance/datasets/xagusd) |
| Period | `2024-09-02` -> `2026-09-01` | `2009-02-23` -> `2026-09-01` |
| File | `XAGUSD_3d.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/xagusd) |
| Coverage report | — | [XAGUSD coverage](https://getdata.finance/coverage/xagusd) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`3d` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/xagusd)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W**

GitHub = `3d` sample · [getdata.finance](https://getdata.finance/datasets/xagusd) = all **11** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `3d` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`XAGUSD_3d.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2024-09-02T00:00:00+00:00 | 30.58555 | 30.68755 | 27.763 | 28.927 | 499973.66353 |
| 2024-09-05T00:00:00+00:00 | 28.927 | 29.837 | 28.371 | 28.61 | 511199.07946 |
| 2024-09-08T00:00:00+00:00 | 28.61 | 29.309 | 28.424 | 29.2305 | 346228.49818 |
| 2024-09-11T00:00:00+00:00 | 29.2305 | 31.762 | 28.8585 | 31.556 | 658382.13898 |
| 2024-09-14T00:00:00+00:00 | 31.556 | 32.051 | 31.545 | 31.733 | 165118.69703 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-08-20T00:00:00+00:00 | 71.27815 | 74.54815 | 69.94715 | 73.49915 | 1232445.93898 |
| 2026-08-23T00:00:00+00:00 | 68.813 | 69.788 | 67.286 | 68.591 | 1418795 |
| 2026-08-26T00:00:00+00:00 | 68.591 | 71.011 | 65.953 | 66.221 | 1969346 |
| 2026-08-29T00:00:00+00:00 | 66.221 | 67.319 | 65.386 | 66.444 | 613201 |
| 2026-09-01T00:00:00+00:00 | 66.444 | 66.923 | 63.186 | 63.201 | 713720 |

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

df = pd.read_csv('XAGUSD_3d.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('XAGUSD_3d.csv', parse_dates=['datetime'])
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

df = pd.read_csv('XAGUSD_3d.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='3d')
print(pf.stats())
```

## Download full data

The complete **XAGUSD** archive on **[getdata.finance](https://getdata.finance/datasets/xagusd)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **2,085** rows at `3d`, plus all other timeframes in the same ZIP.

**[-> Get the full XAGUSD dataset on getdata.finance](https://getdata.finance/datasets/xagusd)**

---
*GetData · XAGUSD 3d OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/xagusd)*
