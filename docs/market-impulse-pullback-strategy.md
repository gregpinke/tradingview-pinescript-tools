# Market Impulse Pullback Strategy

## Overview

The Market Impulse Pullback Strategy is a demonstration TradingView strategy built to show how momentum-style indicator logic can be converted into systematic entry and exit rules.

It is included in this repository as a portfolio example of Pine Script strategy development rather than as an optimized trading system.

The strategy looks for strong directional impulse candles, waits for a pullback, and enters when price resumes in the original direction.

---

## Purpose

This script is designed to demonstrate:

- conversion of indicator concepts into strategy logic  
- use of systematic entry and exit conditions  
- strategy state management in Pine Script  
- practical backtesting structure for custom TradingView tools  

It is intentionally simplified for clarity and portability across symbols.

---

## Strategy Logic

### Long Setup

A long setup is created when:

- a bullish impulse candle is detected  
- the candle exceeds an ATR-based threshold  
- optional trend filter conditions are satisfied  

After the impulse, the strategy waits for a pullback inside the impulse range.

A long entry is triggered when price shows renewed bullish intent while remaining above the impulse low.

The stop is anchored below the impulse low.

The target is set using a fixed reward-to-risk multiple.

---

### Short Setup

A short setup is created when:

- a bearish impulse candle is detected  
- the candle exceeds an ATR-based threshold  
- optional trend filter conditions are satisfied  

After the impulse, the strategy waits for a pullback inside the impulse range.

A short entry is triggered when price shows renewed bearish intent while remaining below the impulse high.

The stop is anchored above the impulse high.

The target is set using a fixed reward-to-risk multiple.

---

## Position Sizing

This strategy uses a simplified sizing model so it can backtest more reliably across instruments with different prices.

It supports:

- percent of equity sizing  
- fixed quantity sizing  
- optional minimum tradable unit fallback  

This sizing model is included for demonstration and portability. It is not intended to represent precise broker-specific execution.

---

## Key Features

- ATR-based impulse detection  
- pullback entry logic  
- optional EMA trend filter  
- fixed reward-to-risk targets  
- optional opposite-signal exits  
- explicit position sizing controls  
- separate markers for signals and actual fills  

---

## Main Inputs

Typical parameters include:

### Signal Settings
- ATR length  
- impulse threshold multiple  
- pullback window  

### Trend Filter
- EMA filter on/off  
- EMA length  

### Risk Settings
- reward-to-risk multiple  
- opposite signal exit toggle  

### Position Sizing
- order size type  
- percent of equity  
- fixed quantity  
- minimum tradable unit fallback  

### Display
- EMA visibility  
- impulse markers  
- signal markers  
- fill and exit labels  

---

## Interpretation Notes

This strategy is intended as a coding demonstration.

It is useful for showing how a discretionary chart concept can be expressed as:

- objective entry conditions  
- objective stop placement  
- objective target logic  
- backtestable position management  

It should not be interpreted as a finished or production-ready trading system.

---

## Portfolio Note

This script is included as a portfolio example of indicator-to-strategy conversion in Pine Script.

It demonstrates clean strategy structure, explicit sizing logic, and practical backtesting implementation for custom TradingView development work.