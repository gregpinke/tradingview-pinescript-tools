# TradingView Pine Script Tools

Custom TradingView indicators, strategies, and utilities built in Pine Script for market structure analysis, momentum detection, session mapping, and trade risk planning.

This repository is part of my public portfolio as a Pine Script developer. The focus is on clean, practical tools that can be adapted for custom client work such as indicators, strategy components, alerts, dashboards, and trader utilities.

---

# Indicators

## Liquidity Compression Detector

Detects horizontal compression zones where price repeatedly oscillates within a narrow range. These structures can help identify consolidation and potential breakout areas.

![Liquidity Compression Detector Example](screenshots/compression-detector.png)

**Highlights**

* Pivot-based range detection
* Equality tolerance controls
* Dynamic zone visualization
* Historical structure review

Documentation:
[docs/liquidity-compression-detector.md](docs/liquidity-compression-detector.md)

---

## Market Impulse Detector

Highlights strong directional candles and short impulse sequences using a multi-factor momentum model. Designed to help identify expansion phases following consolidation or low-volatility conditions.

![Market Impulse Detector Example](screenshots/impulse-detector.png)

**Highlights**

* Impulse classification
* ATR-aware displacement logic
* Composite scoring model
* Visual momentum markers

Documentation:
[docs/market-impulse-detector.md](docs/market-impulse-detector.md)

---

## Market Sessions & HTF Levels

Displays key market sessions and higher-timeframe reference levels directly on the chart. Useful for traders who rely on session structure and major opens as contextual guides.

![Session Levels Example](screenshots/session-levels.png)

![Session Levels Example 2](screenshots/session-levels2.png)

**Highlights**

* Session overlays
* Daily / weekly / monthly / quarterly levels
* Historical level display options
* Intraday chart utility

Documentation:
[docs/market-sessions-htf-levels.md](docs/market-sessions-htf-levels.md)

---

## Trade Risk Assistant

A practical chart utility for calculating position risk from account size, percentage risk, and trade stop distance.

![Trade Risk Assistant Example](screenshots/risk-assistant.png)

**Highlights**

* Account-based risk sizing
* Clear chart-side display
* Fast position sizing workflow
* Adaptable utility indicator

Documentation:
[docs/trade-risk-assistant.md](docs/trade-risk-assistant.md)

---

# Strategies

## Market Impulse Pullback Strategy

A demonstration strategy showing how momentum-style indicator logic can be converted into systematic entry and exit rules.

The strategy detects impulse candles, waits for a pullback, and enters when price resumes in the original direction.

![Strategy Example](screenshots/strategy-example.png)

![Strategy Backtest Example](screenshots/strategy-example2.png)

**Highlights**

* ATR-based impulse detection
* Pullback entry logic
* EMA trend filter option
* Fixed reward-to-risk exits
* Explicit cross-symbol position sizing model

Documentation:
[docs/market-impulse-pullback-strategy.md](docs/market-impulse-pullback-strategy.md)

---

# Repository Structure

```
tradingview-pinescript-tools/

├── indicators/
│   ├── liquidity-compression-detector.pine
│   ├── market-impulse-detector.pine
│   ├── market-sessions-htf-levels.pine
│   └── trade-risk-assistant.pine
│
├── strategies/
│   └── market-impulse-pullback-strategy.pine
│
├── docs/
│   ├── liquidity-compression-detector.md
│   ├── market-impulse-detector.md
│   ├── market-sessions-htf-levels.md
│   ├── trade-risk-assistant.md
│   └── market-impulse-pullback-strategy.md
│
├── screenshots/
│   ├── compression-detector.png
│   ├── impulse-detector.png
│   ├── risk-assistant.png
│   ├── session-levels.png
│   ├── session-levels2.png
│   ├── strategy-example.png
│   └── strategy-example2.png
│
└── README.md
```

---

# Purpose

This repository demonstrates practical Pine Script development, including:

* indicator development
* strategy implementation
* chart-based UI design
* market data visualization
* reusable logic for custom TradingView tools

It is **not intended as trading advice** or as a complete trading system.

---

# Custom Work

I build custom Pine Script tools such as:

* custom indicators
* alert systems
* indicator-to-strategy conversions
* session tools
* trading dashboards
* risk calculators
* signal visualization tools

---

# Notes

Some scripts in this repository are simplified or generalized for public portfolio use.

Public documentation focuses on implementation concepts and user functionality rather than proprietary trading interpretation.

## Custom Pine Script Development

I build custom TradingView tools including:

• indicators  
• strategy conversions  
• alerts  
• dashboards  
• risk tools  

If you need a custom Pine Script project or modifications to an existing script, feel free to open an issue or reach out via GitHub.