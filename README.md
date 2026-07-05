# Tyumex Trading Systems — MT5 Tools (Free 1-Month Trial)

**[Русская версия → README.ru.md](README.ru.md)**

Professional MetaTrader 5 tools: a **non-repainting reversal-zones indicator**, a one-click **trade assistant**, and **seconds / Renko / Range charts**. Compiled `.ex5` trial builds are published in [Releases](../../releases) — free, work on any MT5 account until **2026-08-05** (broker time). Full version with account binding: [@Tyumex_bot](https://t.me/Tyumex_bot).

![Tyumex](docs/hero.png)

---

## From the author

I'm releasing my indicator with a free trial because I want feedback. I built it for myself and wasn't thinking about selling it. But since it works — let people try it.

I've been trading for 7 years, 3 of them very actively, and the last year in stable, tangible profit. Over that time I went through everything: used it, threw it away, tried again, threw it away again. 99% of what is commonly called "trading" — indicators, EAs, courses, brokers — is at best an illusion of control.

What actually works, I found myself — by watching the chart for hours, days, years. The market always moves by the same laws. Only two elements matter: the **place** where price can reverse, and the **moment** — how exactly it reverses. When both align, the trade is right. There is nothing else.

This indicator gives you the **place**. Trade those zones the way you know how. The entry moment is a separate topic — we'll get to it.

---

## Products

### 1. Tyumex Zones — reversal zones indicator

Zones where price is likely to reverse. Visible in advance and **never repainted**.

- built in real time, no repainting, no backfitting;
- works on any instrument: forex, futures, stocks, crypto;
- shines on M1 and scalping;
- session-aware (Asia / Europe / America) with key levels;
- alerts on zone touch and breakout;
- works on Renko / seconds / custom charts;
- available for MetaTrader 5, Tiger.Trade and TradingView (this repo ships the MT5 build; TradingView/Tiger access via [@Tyumex_bot](https://t.me/Tyumex_bot)).

![Tyumex Zones](docs/zones_full.png)

### 2. Trade Expert — trade assistant

Keeps your trading scenario in focus and helps execute the setup calmly.

- one-click entries with risk-based lot sizing;
- stop-loss at candle extremum, take-profit in R, partial close;
- auto-breakeven and Safe Mode for discipline;
- trade the structure, not the emotions.

It is an assistant for your system, not a "magic profit button".

![Trade Expert](docs/expert_full.png)

### 3. Tyumex Second Charts — seconds / Renko / Range charts

Charts your broker doesn't give you: seconds, Renko and Range on one engine.

- second-based candles (S5, S10, S20…), Renko and Range bars;
- switch mode and size right from the on-chart panel;
- far more detail and setups inside every minute;
- built via MT5 custom symbols in real time;
- history depth configurable in hours.

![Second Charts](docs/seconds_full.png)

---

## Download (trial until 2026-08-05)

Compiled `.ex5` files are in **[Releases](../../releases)**. Source code is not published.

Trial builds run on **any MT5 account** until `2026-08-05 23:59` (broker time). After that date the product shows a renewal screen — get a new build from [@Tyumex_bot](https://t.me/Tyumex_bot) (7 days bound to your account; 2 months for Tickmill partners).

## Installation (MetaTrader 5)

1. In MT5: **File → Open Data Folder**.
2. Open the **MQL5** folder.
3. Copy the files:
   - `TyumexZones.ex5` → **MQL5\Indicators**
   - `Trade Expert.ex5` → **MQL5\Experts**
   - `TyumexSecondCharts.ex5` → **MQL5\Experts**
4. Back in MT5, right-click in **Navigator** → **Refresh** (or restart the terminal).
5. Drag the product onto a chart:
   - **TyumexZones** and **Trade Expert** — onto the chart you trade;
   - **TyumexSecondCharts** — onto a regular chart of any timeframe (e.g. M1): it opens a separate seconds/Renko/Range chart on top, controlled from the on-chart panel.

For Trade Expert and Second Charts enable **Algo Trading** (button in the MT5 toolbar).

## FAQ

**Why is there no source code?**
This is a commercial product. The repo contains the description and compiled trial builds.

**What happens after 2026-08-05?**
The tool stops drawing and shows a renewal screen. Your terminal and data are not affected.

**How do I get the full version / TradingView / Tiger.Trade?**
Message [@Tyumex_bot](https://t.me/Tyumex_bot) — the bot issues a trial build bound to your account; the manager helps with full access and the TradingView / Tiger.Trade versions.

**Feedback**
This trial exists to gather feedback — share your experience via [@Tyumex_bot](https://t.me/Tyumex_bot) or open an Issue here.

---

Keywords: scalping, indicator, reversal, levels, zones, price action, MT5, MetaTrader 5, Tiger.Trade, TradingView, reversal zones, non-repainting, supply and demand, support resistance, Renko, seconds chart, forex, futures, crypto.

*Trading involves risk. These tools are decision-support instruments, not financial advice and not a guarantee of profit.*
