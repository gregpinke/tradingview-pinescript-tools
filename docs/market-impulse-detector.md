# Market Impulse Detector

## Overview

The Market Impulse Detector highlights strong directional price moves using a multi-factor momentum model.

Instead of relying on candle size alone, the script evaluates whether a move shows characteristics commonly associated with meaningful expansion, such as volatility-adjusted displacement, efficient travel, and short-term follow-through.

## What It Does

The indicator attempts to identify candles or short sequences that stand out from surrounding price action by measuring a combination of factors such as:

- displacement relative to recent volatility
- release from lower-volatility conditions
- directional efficiency
- participation or activity filters
- short-term acceptance after the move

Signals are then classified and displayed visually on the chart.

## Typical Use Cases

This type of tool can be useful for:

- highlighting strong expansion candles
- filtering out weaker momentum bursts
- studying trend initiation and continuation
- combining with consolidation or range tools

## Key Features

- Volatility-aware impulse detection
- Composite scoring model
- Visual signal markers
- Bullish and bearish classifications
- Configurable sensitivity

## Main Inputs

Depending on the script version, common inputs may include:

- ATR length
- compression lookback
- leg window size
- follow-through confirmation bars
- score thresholds
- visualization controls

## Interpretation Notes

This indicator is best used as a momentum classification tool rather than a standalone entry engine.

It can complement:
- consolidation detection
- session tools
- higher-timeframe structure
- discretionary continuation analysis

## Portfolio Note

This script is included as a public example of custom Pine Script development for multi-condition momentum classification.