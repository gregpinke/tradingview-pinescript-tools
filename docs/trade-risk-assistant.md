# Trade Risk Assistant

## Overview

The Trade Risk Assistant is a lightweight chart utility for basic position risk planning.

It calculates a simple risk-based size output from account size, percentage risk, and user-measured trade risk.

## What It Does

The script allows the user to enter:

- portfolio or account size
- percentage of capital to risk
- measured risk per trade

It then returns a size value that helps translate risk rules into a practical execution number.

## Typical Use Cases

This type of tool can be useful for:

- quick discretionary trade sizing
- enforcing fixed percentage risk rules
- reducing manual calculation errors
- building custom execution utilities

## Key Features

- Simple account-based risk calculation
- Fast chart-side output
- Minimal input workflow
- Easy to adapt into richer sizing tools

## Main Inputs

Typical inputs include:

- portfolio size
- percent risk per trade
- measured risk value
- output location or display preferences

## Interpretation Notes

This tool is intentionally simple. It is designed as a fast utility, not as a full brokerage-grade risk engine.

It can be extended with features such as:
- long/short mode
- entry and stop inputs
- contract size handling
- leverage-aware calculations
- currency conversion
- table-based UI

## Portfolio Note

This script is included as a public example of Pine Script utility development and trader workflow tooling.