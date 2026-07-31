# Tyumex Terminal — Standard Edition

Desktop market terminal for multi-chart analysis and trading with Binance and MetaTrader 5. The Standard Edition is distributed as a ready-to-install Windows package.

[Русская версия → README.ru.md](README.ru.md)

## Get 28 days of access

Request the Standard Edition through the official Telegram bot:

**[Open @Tyumex_bot →](https://t.me/Tyumex_bot)**

The bot issues access for 28 days and provides the current installer. The public GitHub repository contains the release package, screenshots, and installation notes.

The installer itself can be opened without a code, but the terminal will not load new market data or allow new trades until a valid personal code is activated. Existing positions can still be closed and protected. The code is issued by [@Tyumex_bot](https://t.me/Tyumex_bot) and is not published in GitHub.

- [Download the latest GitHub Release](https://github.com/Tyumex/tyumex-mt5-tools/releases/latest)
- Current package: `TyumexTerminalStandardSetup-1.0.30.exe`
- SHA-256: `ACCCDD3F22DD27180CF81755AE4D345C202C8325E954FBE37DFAAC397F72BA03`

![Tyumex Terminal overview](docs/terminal-overview.png)

## What the terminal provides

- Multiple independent chart panes in one workspace, with layouts for focused or multi-market analysis.
- Binance Spot and Binance USD-M Futures market data.
- Local MetaTrader 5 connections, including configurable broker terminals and symbols.
- Native tick aggregation for short periods such as 20s, 30s, and 45s, as well as standard timeframes.
- Candles, live streaming, volume, market depth-style levels, and session-aware chart overlays.
- Built-in SMA, EMA, RSI, MACD, and Bollinger Bands indicators.
- MT5 trade workflow with risk-based or fixed volume, Stop Loss, Take Profit, Safe Mode, break-even, and position closing controls.

![Tyumex Terminal workspace](docs/terminal-workspace.png)

The Standard Edition is focused on a clean trading workspace and practical chart tools. It is not financial advice and does not guarantee profit.

## Installation on Windows

1. Download `TyumexTerminalStandardSetup-1.0.30.exe` from the [latest release](https://github.com/Tyumex/tyumex-mt5-tools/releases/latest), or request the current build from [@Tyumex_bot](https://t.me/Tyumex_bot).
2. Run the installer. It creates a desktop shortcut and keeps the Standard Edition isolated from other Tyumex installations.
3. Start **Tyumex Terminal Standard**.
4. For Binance charts, choose the exchange and symbol in the chart header.
5. For MT5 charts, open the settings, add the full path to the required 64-bit `terminal64.exe`, and keep that MT5 terminal running and logged in.

The application uses bundled browser assets and does not require a separate Python or Node.js installation for normal use. Internet access is required for Binance data. MT5 data and trading require a locally installed and authorized MetaTrader 5 terminal.

## Important notes

- Enter the exact symbol name used by the selected broker in MT5.
- Buy and Sell actions are sent immediately when the order controls are used; check volume, Stop Loss, and Take Profit before sending an order.
- Never publish broker credentials, account numbers, license keys, or local terminal paths in issues or screenshots.
- The public repository publishes the installer and product documentation; private development files are intentionally not included.

## Support

For access, current builds, activation questions, and feedback, contact [@Tyumex_bot](https://t.me/Tyumex_bot).

Keywords: trading terminal, market terminal, Binance, Binance Futures, MetaTrader 5, MT5, XAUUSD, multi-chart, scalping, tick charts, custom timeframes, technical indicators, risk management.
