Market Structure Detector
Overview

The Market Structure Detector highlights key structural turning points and trend events directly on the chart.

The indicator identifies swing highs and swing lows, classifies structural pivots, and marks important structure breaks such as Break of Structure (BOS) and Change of Character (CHoCH).

It translates common discretionary structure concepts into consistent algorithmic detection logic so market structure can be reviewed clearly across instruments and timeframes.

What It Does

The indicator detects confirmed swing pivots using configurable pivot sensitivity.

Once pivots are identified, the script tracks how price interacts with those levels and classifies structural developments such as:

Higher High (HH)
Higher Low (HL)
Lower High (LH)
Lower Low (LL)

When price breaks a relevant structural level, the indicator marks the event as either:

BOS (Break of Structure) – continuation of the current trend
CHoCH (Change of Character) – potential shift in trend direction

Structure levels are drawn and updated dynamically so historical structure can be reviewed visually.

Typical Use Cases

This type of tool can be useful for:

studying trend continuation and failure
identifying structural turning points
reviewing market structure objectively
combining structure with momentum or session tools
building discretionary or systematic trading workflows
Key Features
Pivot-based swing detection
Automatic HH / HL / LH / LL classification
Break of Structure (BOS) identification
Change of Character (CHoCH) detection
Dynamic structure level visualization
Optional filtering of continuation BOS events
Historical structure review
Main Inputs

Typical parameters include:

Structure Logic
Pivot left bars
Pivot right bars
Break confirmation mode (close vs wick)
Event Labels
BOS label visibility
CHoCH label visibility
Continuation BOS filtering
ATR-based label offset settings
Visualization
Swing marker display
Swing classification labels
Structure level visibility
color customization
Interpretation Notes

This indicator does not generate trade signals by itself.

Instead, it provides a structural framework for interpreting price behavior.

Common interpretations include:

BOS sequences indicating trend continuation
CHoCH events indicating possible regime shifts
HH/HL patterns suggesting bullish structure
LH/LL patterns suggesting bearish structure

The tool is most useful when combined with other contextual information such as:

momentum signals
consolidation patterns
higher timeframe levels
session structure
Portfolio Note

This script is included as a public example of custom Pine Script development for market structure analysis tools.

It demonstrates pivot-based structure detection, state-based event classification, and dynamic chart visualization logic for TradingView indicators.