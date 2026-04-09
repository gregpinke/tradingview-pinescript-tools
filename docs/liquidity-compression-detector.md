# Liquidity Compression Detector

## Overview

The Liquidity Compression Detector identifies horizontal consolidation zones where price repeatedly oscillates inside a narrow range.

These zones often form when the market pauses, tests both sides of a local range, and compresses before a larger directional move.

The indicator translates this visual structure into algorithmic detection logic so compression structures can be identified consistently across instruments and timeframes.

---

## What It Does

The indicator looks for price structures that resemble range compression:

- repeated interaction with local highs and lows  
- approximate equality between key pivot points  
- a bounded range that remains valid until broken  

When a valid structure is found, the indicator draws a box around the compression zone and extends it while the structure remains active.

---

## Typical Use Cases

This tool can be used for:

- identifying consolidation before breakout  
- spotting areas of repeated liquidity interaction  
- reviewing historical compression zones  
- building discretionary or systematic breakout workflows  

---

## Key Features

- Pivot-based structure detection  
- Adjustable equality tolerance  
- Dynamic range visualization  
- Historical pattern display  
- Breakout invalidation logic  

---

## Main Inputs

Typical parameters include:

- Pivot length  
- Equality tolerance mode  
- Equality tolerance value  
- Breakout validation settings  
- Box extension preferences  
- Historical display options  

---

## Interpretation Notes

The indicator does not predict direction on its own.

It is intended as a structural context tool and may be used alongside:

- breakout confirmation  
- momentum indicators  
- higher-timeframe levels  
- session context  

---

## Portfolio Note

This script is included as a public example of custom Pine Script development for structure-based market tools.