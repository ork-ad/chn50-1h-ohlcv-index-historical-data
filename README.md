# CHN50 1h OHLCV Index Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-4_696_rows-blue)](https://ork.ad/) [![Updated](https://img.shields.io/badge/weekly_update-every_Sunday-green)](https://ork.ad/) [![Full data on ork.ad](https://img.shields.io/badge/download-ork.ad-orange)](https://ork.ad/)

### → [**Download the full CHN50 dataset on ork.ad**](https://ork.ad/)

**CHN50 1h OHLCV Stock index historical data** — ultra high-quality 1h OHLCV for **China 50 Index**. Global cash and extended index sessions — Asia, Europe and US coverage, not US-hours only. Clean `time, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

## Table of contents

- [Why this dataset?](#why-this-dataset)
- [Download sample CSV](#download-sample)
- [GitHub Pages preview](#github-pages)
- [Sample vs full dataset](#sample-vs-full-dataset)
- [Timeframes on ork.ad](#timeframes-on-orkad)
- [Weekly updates](#weekly-updates)
- [Data preview](#data-preview)
- [Schema](#schema)
- [Code examples](#code-examples)
- [Download full data on ork.ad](#download-full-data)

## Why this dataset?

- **Ultra high-quality 1h OHLCV** for **China 50 Index** (Stock index)
- **Global cash and extended index sessions — Asia, Europe and US coverage, not US-hours only**
- **Clean CSV schema** — `time, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`1h`) · **13 timeframes** on [ork.ad](https://ork.ad/) · **4,696** `1h` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [ork.ad](https://ork.ad/) every **Sunday**; GitHub `1h` sample updated in sync

> **Sample on GitHub** · `CHN50_1h.csv` (3,849 rows, `2025-10-03` → `2026-07-02`). **Full archive on [ork.ad](https://ork.ad/)** — **4,696** `1h` rows (~0.3 MB), **13 timeframes** (``1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W``), `2025-08-05` → `2026-07-02`.

## Download sample

**[CHN50_1h.csv](https://github.com/ork-ad/chn50-1h-ohlcv-index-historical-data/blob/main/CHN50_1h.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/ork-ad/chn50-1h-ohlcv-index-historical-data/main/CHN50_1h.csv)) · [GitHub Releases](https://github.com/ork-ad/chn50-1h-ohlcv-index-historical-data/releases) when the release workflow is active.

## GitHub Pages

Interactive chart & stats: **[https://ork-ad.github.io/chn50-1h-ohlcv-index-historical-data/](https://ork-ad.github.io/chn50-1h-ohlcv-index-historical-data/)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([ork.ad](https://ork.ad/))** |
|---|--:|---|
| Instrument | China 50 Index · Stock index | China 50 Index · Stock index |
| Timeframes | `1h` (sample) | **13** — `1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W` |
| 1h rows | 3,849 | **4,696** |
| Size | 0.25 MB | ~0.3 MB |
| Period | `2025-10-03` → `2026-07-02` | `2025-08-05` → `2026-07-02` |
| File | `CHN50_1h.csv` | ZIP on [ork.ad](https://ork.ad/) |
| Updates | Weekly (Sunday) — GitHub sample | Weekly (Sunday) — all timeframes |

## Timeframes on ork.ad

This GitHub repository ships a **`1h` evaluation sample** only. On **[ork.ad](https://ork.ad/)**, each full asset archive is delivered as a ZIP with **13 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m** · **3m** · **5m** · **15m** · **30m** · **1H** · **2H** · **4H** · **8H** · **12H** · **16H** · **1D** · **1W**

GitHub = `1h` sample · [ork.ad](https://ork.ad/) = all **13** timeframes above for the same instrument.

## Weekly updates

- **[ork.ad](https://ork.ad/)** — Full datasets on ork.ad are updated every Sunday.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Sunday), in sync with ork.ad.

When a new `1h` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`CHN50_1h.csv`**:

**First rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2025-10-03T01:00:00Z | 15240.742 | 15262.593 | 15207.572 | 15220.092 | 5031.0 |
| 2025-10-03T02:00:00Z | 15220.092 | 15227.572 | 15196.572 | 15200.072 | 1644.0 |
| 2025-10-03T03:00:00Z | 15200.072 | 15200.592 | 15179.082 | 15184.592 | 934.0 |
| 2025-10-03T04:00:00Z | 15184.592 | 15190.582 | 15173.592 | 15176.582 | 308.0 |
| 2025-10-03T05:00:00Z | 15176.582 | 15186.572 | 15147.071 | 15152.072 | 1682.0 |

**Last rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| time | open | high | low | close | volume |
| 2026-07-02T17:00:00Z | 14743.42 | 14748.92 | 14713.41 | 14714.41 | 2695.0 |
| 2026-07-02T18:00:00Z | 14714.41 | 14742.43 | 14711.41 | 14737.93 | 2471.0 |
| 2026-07-02T19:00:00Z | 14737.93 | 14789.91 | 14732.42 | 14788.42 | 2064.0 |
| 2026-07-02T20:00:00Z | 14788.42 | 14816.93 | 14785.91 | 14801.93 | 260.0 |

## Schema

```text
time,open,high,low,close,volume
```

## Code examples

### pandas

```python
import pandas as pd

df = pd.read_csv('CHN50_1h.csv', parse_dates=['time'])
df.set_index('time', inplace=True)
print(df.describe())
print(df.resample('1h').agg({'open': 'first', 'high': 'max',
                              'low': 'min', 'close': 'last', 'volume': 'sum'}).head())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('CHN50_1h.csv', parse_dates=['time'])
df.set_index('time', inplace=True)

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

df = pd.read_csv('CHN50_1h.csv', parse_dates=['time'])
close = df.set_index('time')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='1h')
print(pf.stats())
```

## Download full data

The complete **CHN50** archive on **[ork.ad](https://ork.ad/)** includes **13 OHLCV timeframes** (`1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W`) — **4,696** rows at `1h`, plus all other timeframes in the same ZIP.

**[→ Get the full CHN50 dataset on ork.ad](https://ork.ad/)**

---
*GetData · CHN50 1h OHLCV sample on GitHub · Full historical data on [ork.ad](https://ork.ad/) · 2026-07-04 UTC*