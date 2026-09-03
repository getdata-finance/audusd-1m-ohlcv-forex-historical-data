# AUDUSD 1m OHLCV Forex Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-5_263_593_rows-blue)](https://getdata.finance/datasets/audusd) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/audusd)

### -> [**Download the full AUDUSD dataset on getdata.finance**](https://getdata.finance/datasets/audusd)

**AUDUSD 1m OHLCV forex historical data** — ultra high-quality 1m OHLCV for **Australian Dollar / US Dollar**. Clean `time, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

## Table of contents

- [Why this dataset?](#why-this-dataset)
- [Download sample CSV](#download-sample)
- [Sample vs full dataset](#sample-vs-full-dataset)
- [Timeframes on GetData](#timeframes-on-getdata)
- [Weekly updates](#weekly-updates)
- [Data preview](#data-preview)
- [Schema](#schema)
- [Download full data on getdata.finance](#download-full-data-on-getdata)

## Why this dataset?

- **Ultra high-quality 1m OHLCV** for **Australian Dollar / US Dollar** (Forex)
- **Clean CSV schema** — `time, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`1m`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/audusd) · **5,263,593** `1m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `1m` sample updated in sync

> **Sample on GitHub** · `AUDUSD_1m.csv` (55,440 rows, `2026-07-09` -> `2026-09-02`). **Full archive on [getdata.finance](https://getdata.finance/datasets/audusd)** — **5,263,593** `1m` rows, **11 timeframes**, `2012-06-24` -> `2026-09-02`.

## Download sample

**[AUDUSD_1m.csv](https://github.com/getdata-finance/audusd-1m-ohlcv-forex-historical-data/blob/main/AUDUSD_1m.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/audusd-1m-ohlcv-forex-historical-data/main/AUDUSD_1m.csv))

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/audusd))** |
|---|--:|---|
| Instrument | Australian Dollar / US Dollar · Forex | Australian Dollar / US Dollar · Forex |
| Timeframes | `1m` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 1m rows | 55,440 | **5,263,593** |
| Period | `2026-07-09` -> `2026-09-02` | `2012-06-24` -> `2026-09-02` |
| File | `AUDUSD_1m.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/audusd) |
| Coverage report | — | [AUDUSD coverage](https://getdata.finance/coverage/audusd) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`1m` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/audusd)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes**:

**1m** · **3m** · **5m** · **15m** · **30m** · **1H** · **4H** · **12H** · **1D** · **3D** · **1W**

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples refreshed weekly, in sync with getdata.finance.

## Data preview

First and latest rows from the GitHub sample **`AUDUSD_1m.csv`**:

**First rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-07-09T13:21:00+00:00 | 0.70778 | 0.70783 | 0.70777 | 0.70777 | 109 |
| 2026-07-09T13:22:00+00:00 | 0.70777 | 0.7078 | 0.70775 | 0.7078 | 109 |
| 2026-07-09T13:23:00+00:00 | 0.7078 | 0.70783 | 0.70775 | 0.7078 | 137 |
| 2026-07-09T13:24:00+00:00 | 0.7078 | 0.70783 | 0.70776 | 0.70777 | 101 |
| 2026-07-09T13:25:00+00:00 | 0.70777 | 0.70785 | 0.70777 | 0.70783 | 126 |

**Last rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-09-02T01:56:00+00:00 | 0.7148 | 0.71481 | 0.7147 | 0.71471 | 77 |
| 2026-09-02T01:57:00+00:00 | 0.71471 | 0.71474 | 0.71464 | 0.71464 | 124 |
| 2026-09-02T01:58:00+00:00 | 0.71464 | 0.71472 | 0.71464 | 0.71471 | 123 |
| 2026-09-02T01:59:00+00:00 | 0.71471 | 0.71486 | 0.71471 | 0.71481 | 141 |
| 2026-09-02T02:00:00+00:00 | 0.71481 | 0.71487 | 0.71456 | 0.71456 | 180 |

## Schema

| Column | Description |
| --- | --- |
| `time` | Bar open timestamp (UTC, ISO-8601). |
| `open` | Opening price of the candlestick bar. |
| `high` | Highest price during the bar. |
| `low` | Lowest price during the bar. |
| `close` | Closing price of the candlestick bar. |
| `volume` | Tick volume (number of price updates) during the bar. |

```text
time,open,high,low,close,volume
```

## Download full data

Full AUDUSD archive — 11 timeframes, gap-free, updated weekly:

**[-> Get the full AUDUSD dataset on getdata.finance](https://getdata.finance/datasets/audusd)**
